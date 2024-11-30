# DSA-210-Project

## **Lines of Code Written and Study Hours Analysis**

### **Motivation**

The number of lines of code written is often closely tied to the time dedicated to studying and practicing coding. Understanding the relationship between study hours and the amount of code written can offer valuable insights into how consistent effort contributes to coding progress. As someone passionate about improving coding skills, this project aims to explore how **study hours** impact **lines of code written** over time. By analyzing this data, the goal is to identify trends, measure the effectiveness of study patterns, and ultimately provide a foundation for better learning strategies.

Key questions I aim to answer:
- Does the number of lines of code written depend on the hours spent studying each day?
- What is the relationship between study time and progress in writing code?
- Can we predict the number of lines of code written based on the hours studied?

### **Dataset Description**

The dataset consists of information I have tracked over **45 days**, capturing the number of hours I studied each day and the corresponding number of lines of code I wrote for my **React project**. The study hours are affected by factors such as **abroad travels**, **school exam weeks**, and other personal commitments. Notably, **the last 15 days** of the 45-day period coincide with exam weeks, during which my study hours and code-writing progress decreased significantly due to the need to focus on school exams.

Here’s a breakdown of the dataset fields:

1. **Study Hours Data**
   - **Source**: Tracked personally over 45 days.
   - **Fields**:
     - `Days Studied`: The number of days (1 through 45).
     - `Hours Studied`: The number of hours I studied each day, ranging from 0 to 6 hours. On days where I studied for 0 hours, no lines of code were written.

2. **Lines of Code Written Data**
   - **Source**: Based on my personal progress in my React project.
   - **Fields**:
     - `Lines of Code Written`: The number of lines of code I wrote each day. On days where I studied for 0 hours, I wrote 0 lines of code.

### **Example Data**:

| Days Studied | Hours Studied | Lines of Code Written |
|--------------|---------------|-----------------------|
| 1            | 3             | 120                   |
| 2            | 5             | 150                   |
| 3            | 2             | 80                    |
| 4            | 6             | 180                   |
| 5            | 0             | 0                     |
| 6            | 4             | 130                   |
| 7            | 6             | 200                   |
| 8            | 1             | 60                    |
| 9            | 0             | 0                     |
| 10           | 3             | 110                   |
| 11           | 4             | 140                   |
| 12           | 5             | 170                   |
| 13           | 2             | 70                    |
| 14           | 3             | 100                   |
| 15           | 6             | 210                   |
| 16           | 0             | 0                     |
| 17           | 4             | 160                   |
| 18           | 5             | 190                   |
| 19           | 6             | 220                   |
| 20           | 0             | 0                     |
| 21           | 2             | 90                    |
| 22           | 1             | 40                    |
| 23           | 4             | 120                   |
| 24           | 5             | 180                   |
| 25           | 3             | 110                   |
| 26           | 6             | 230                   |
| 27           | 0             | 0                     |
| 28           | 4             | 140                   |
| 29           | 3             | 100                   |
| 30           | 5             | 190                   |
| 31           | 6             | 240                   |
| 32           | 0             | 0                     |
| 33           | 2             | 80                    |
| 34           | 4             | 130                   |
| 35           | 3             | 90                    |
| 36           | 1             | 40                    |
| 37           | 5             | 200                   |
| 38           | 0             | 0                     |
| 39           | 3             | 110                   |
| 40           | 6             | 230                   |
| 41           | 5             | 190                   |
| 42           | 2             | 70                    |
| 43           | 4             | 150                   |
| 44           | 6             | 210                   |
| 45           | 0             | 0                     |

### **Data Collection Process**

- The **study hours** for each day were tracked manually. I made sure to log the hours spent on studying every day. However, these hours were affected by various factors, such as **abroad travels** and particularly **school exam preparation**.
- During **exam weeks**, which were the last 15 days of the 45-day period, my study hours and lines of code written were noticeably reduced. I had to focus more on my school exams, which meant less time available for coding practice.
- On some days, I couldn’t study at all due to other personal commitments or exhaustion. In such cases, the study hours were recorded as **0**, and I wrote **0 lines of code** on those days.

### **Project Plan**

### 1. **Data Collection**
   - Track daily study hours for 45 days.
   - Note the number of lines of code written each day for my React project.
   - Log any disruptions (like exams or travels) that affect study hours.

### 2. **Data Preprocessing**
   - Clean and structure the data for analysis.
   - Handle missing or inconsistent values where study hours may have been impacted by travel or other factors.

### 3. **Exploratory Data Analysis (EDA)**
   - Visualize the relationship between `Hours Studied` and `Lines of Code Written` using scatter plots.
   - Calculate the **correlation coefficient** to quantify the relationship.
   - Explore trends in study patterns, especially the effect of exam weeks on progress.

### 4. **Modeling and Prediction**
   - Apply **linear regression** to model the relationship between `Hours Studied` and `Lines of Code Written`.
   - Predict the number of lines of code written for a given study time using the regression model.
   - Evaluate the model’s performance and refine it if necessary.

### 5. **Visualization and Reporting**
   - Create interactive visualizations using libraries like **Matplotlib** or **Seaborn** to present the findings.
   - Summarize insights and conclusions about the effectiveness of study hours on writing code, particularly during exam weeks.

### 6. **Next Steps**
   - Expand the dataset to include more days or additional features like study type (e.g., theory vs. practice).
   - Explore machine learning models to predict future progress based on past study patterns.

### **Dependencies**

- **Pandas**: For data manipulation and structuring.
- **Numpy**: For generating random numbers.
- **Matplotlib / Seaborn**: For data visualization.
- **Scikit-learn**: For linear regression modeling.

### **Conclusion**

By analyzing the relationship between study time and the number of lines of code written for my React project, this project provides insights into the effectiveness of consistent study habits and highlights the impact of interruptions (like school exams or travels). With these findings, I aim to develop strategies for more efficient learning, helping others improve their coding skills over time.

