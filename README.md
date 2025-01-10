# **DSA-210-Project**

## **Lines of Code Written and Study Hours Analysis**

### **Motivation**

The relationship between study hours and the number of lines of code written is a key aspect of understanding coding productivity and progress. This project explores how dedicated study time impacts coding output, using data collected over 45 days. By analyzing this data, the project aims to uncover trends, measure study effectiveness, and create a foundation for better learning strategies. 

This analysis is part of my learning journey as a developer, and the results directly relate to my React project: [Inversense](https://www.inversense.co). Through this project, I aim to answer key questions such as:
- How do study hours influence the number of lines of code written?
- Can we identify patterns in study time and code-writing progress?
- Is it possible to predict coding output based on study hours?

---

### **Dataset Overview**

The dataset contains daily logs of study hours and lines of code written for a React project over a 45-day period. External factors such as exam weeks and travels have influenced study time, especially in the last 15 days, during which study hours and coding output were significantly reduced.

#### **Data Fields**
1. **Days Studied**: Sequential day numbers from 1 to 45.
2. **Hours Studied**: Daily study hours, ranging from 0 to 6. On days with no study hours, no lines of code were written.
3. **Lines of Code Written**: The number of lines of code written each day, ranging from 0 to 240.

#### **Full Dataset**

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

---

### **Code Overview**

#### **Data Preprocessing**
- **File:** `data_preprocessing.ipynb`
- This script loads the raw dataset, explores its structure, and cleans the data for analysis.
- Key Steps:
  - Loading the dataset
  - Generating basic statistics
  - Saving the cleaned dataset for further analysis

#### **Exploratory Data Analysis (EDA)**
- **File:** `eda.ipynb`
- Key visualizations:
  1. **Correlation Heatmap:** Shows the relationship between study hours and lines of code written.
  2. **Box Plot:** Visualizes the distribution of lines of code for different study hours.
  3. **Cumulative Line Plot:** Tracks cumulative study hours vs. cumulative lines of code written over 45 days.
  4. **Scatter Plot:** Displays the direct relationship between study hours and lines of code.

#### **Modeling**
- **File:** `mdoelling.ipynb`
- Linear regression was applied to predict lines of code written based on study hours.
- Key Steps:
  - Splitting the dataset into training and test sets
  - Training a linear regression model
  - Evaluating the model with an R² score
  - Saving the trained model for future use

#### **Regression Visualization**
- **File:** `visualization.ipynb`
- A scatter plot with the regression line was created to visualize the model’s fit and include the R² score on the graph.

---

### **Limitations and Future Work**

- **Limitations:**
  - The dataset covers only 45 days, which may not capture long-term trends.
  - The analysis assumes a linear relationship, potentially overlooking non-linear patterns.
  - Exam weeks and travel disruptions affected consistency in study hours.

- **Future Work:**
  - Collect a larger and more detailed dataset, including study type (e.g., theory vs. practice).
  - Use advanced formulas and methods to generate more detailed visualizations.
  - Develop a more robust React app integrating libraries like **GLVis** to analyze and visualize data dynamically, with backend code for handling complex workflows.

---

### **Technologies Used**
- **Python**: For data analysis, visualization, and modeling.
- **Pandas / NumPy**: For data manipulation.
- **Matplotlib / Seaborn**: For visualizations.
- **Scikit-learn**: For linear regression modeling.
- **Joblib**: For saving and loading trained models.

---

