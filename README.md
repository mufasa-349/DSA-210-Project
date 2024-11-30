# DSA-210-Project

# LeetCode Problems Solved and Study Hours Analysis

## **Motivation**

The number of problems solved on coding platforms like LeetCode is often closely tied to the time dedicated to studying. Understanding the relationship between study hours and problem-solving success can offer valuable insights into how consistent effort contributes to progress. As someone passionate about improving coding skills, this project aims to explore how **study hours** impact **LeetCode problems solved** over time. By analyzing this data, the goal is to identify trends, measure the effectiveness of study patterns, and ultimately provide a foundation for better learning strategies.

Key questions I aim to answer:
- Does the number of problems solved depend on the hours spent studying each day?
- What is the relationship between study time and progress in problem-solving?
- Can we predict the number of problems solved based on the hours studied?

## **Dataset Description**

The dataset consists of information I have tracked over **45 days**, capturing the number of hours I studied each day and the corresponding number of LeetCode problems I solved. The study hours are affected by factors such as **abroad travels**, **school exam weeks**, and other personal commitments. Notably, **the last 15 days** of the 45-day period coincide with exam weeks, during which my study hours and LeetCode progress decreased significantly due to the need to focus on school exams.

Here’s a breakdown of the dataset fields:

1. **Study Hours Data**
   - **Source**: Tracked personally over 45 days.
   - **Fields**:
     - `Days Studied`: The number of days (1 through 45).
     - `Hours Studied`: The number of hours I studied each day, ranging from 0 to 6 hours. On days where I studied for 0 hours, no LeetCode problems were solved.

2. **LeetCode Problems Solved Data**
   - **Source**: Based on my personal progress.
   - **Fields**:
     - `LeetCode Problems Solved`: The number of LeetCode problems I solved each day. On days where I studied for 0 hours, I solved 0 problems.

### **Example Data**:

| Days Studied | Hours Studied | LeetCode Problems Solved |
|--------------|---------------|--------------------------|
| 1            | 3             | 12                       |
| 2            | 5             | 15                       |
| 3            | 2             | 8                        |
| 4            | 6             | 18                       |
| 5            | 0             | 0                        |
| 6            | 4             | 13                       |
| 7            | 6             | 20                       |
| 8            | 1             | 6                        |
| 9            | 0             | 0                        |
| 10           | 3             | 11                       |
| 11           | 4             | 14                       |
| 12           | 5             | 17                       |
| 13           | 2             | 7                        |
| 14           | 3             | 10                       |
| 15           | 6             | 21                       |
| 16           | 0             | 0                        |
| 17           | 4             | 16                       |
| 18           | 5             | 19                       |
| 19           | 6             | 22                       |
| 20           | 0             | 0                        |
| 21           | 2             | 9                        |
| 22           | 1             | 4                        |
| 23           | 4             | 12                       |
| 24           | 5             | 18                       |
| 25           | 3             | 11                       |
| 26           | 6             | 23                       |
| 27           | 0             | 0                        |
| 28           | 4             | 14                       |
| 29           | 3             | 10                       |
| 30           | 5             | 19                       |
| 31           | 6             | 24                       |
| 32           | 0             | 0                        |
| 33           | 2             | 8                        |
| 34           | 4             | 13                       |
| 35           | 3             | 9                        |
| 36           | 1             | 4                        |
| 37           | 5             | 20                       |
| 38           | 0             | 0                        |
| 39           | 3             | 11                       |
| 40           | 6             | 23                       |
| 41           | 5             | 19                       |
| 42           | 2             | 7                        |
| 43           | 4             | 15                       |
| 44           | 6             | 21                       |
| 45           | 0             | 0                        |

## **Data Collection Process**

- The **study hours** for each day were tracked manually. I made sure to log the hours spent on studying LeetCode every day. However, these hours were affected by various factors, such as **abroad travels** and particularly **school exam preparation**.
- During **exam weeks**, which were the last 15 days of the 45-day period, my study hours and LeetCode progress were noticeably reduced. I had to focus more on my school exams, which meant less time available for LeetCode study.
- On some days, I couldn’t study at all due to other personal commitments or exhaustion. In such cases, the study hours were recorded as **0**, and I solved **0 problems** on those days.

## **Project Plan**

### 1. **Data Collection**
   - Track daily study hours for 45 days.
   - Note the number of LeetCode problems solved each day.
   - Log any disruptions (like exams or travels) that affect study hours.

### 2. **Data Preprocessing**
   - Clean and structure the data for analysis.
   - Handle missing or inconsistent values where study hours may have been impacted by travel or other factors.

### 3. **Exploratory Data Analysis (EDA)**
   - Visualize the relationship between `Hours Studied` and `LeetCode Problems Solved` using scatter plots.
   - Calculate the **correlation coefficient** to quantify the relationship.
   - Explore trends in study patterns, especially the effect of exam weeks on progress.

### 4. **Modeling and Prediction**
   - Apply **linear regression** to model the relationship between `Hours Studied` and `LeetCode Problems Solved`.
   - Predict the number of problems solved for a given study time using the regression model.
   - Evaluate the model’s performance and refine it if necessary.

### 5. **Visualization and Reporting**
   - Create interactive visualizations using libraries like **Matplotlib** or **Seaborn** to present the findings.
   - Summarize insights and conclusions about the effectiveness of study hours on problem-solving success, particularly during exam weeks.

### 6. **Next Steps **
   - Expand the dataset to include more days or additional features like study type (e.g., theory vs. practice).
   - Explore machine learning models to predict future progress based on past study patterns.

## **Dependencies**

- **Pandas**: For data manipulation and structuring.
- **Numpy**: For generating random numbers.
- **Matplotlib / Seaborn**: For data visualization.
- **Scikit-learn**: For linear regression modeling.

## **Conclusion**

By analyzing the relationship between study time and problem-solving output on LeetCode, this project provides insights into the effectiveness of consistent study habits and highlights the impact of interruptions (like school exams or travels). With these findings, I aim to develop strategies for more efficient learning, helping others improve their coding skills over time.
