# HR-Job-Change-Insights
## Objective
The goal of this project is to analyze the factors influencing job change decisions in employees. We will preprocess the data, encode categorical variables, perform exploratory data analysis (EDA), and derive insights about employee behavior.

**Dataset**: [Here](https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists?select=aug_train.csv)

### Data Preprocessing
- Handling Missing Values
- Handling Outliers
- Encoding Categorical Variables

### Exploratory Data Analysis(EDA):

1️⃣ Job Change Distribution
- Barplot: Show the proportion of employees who changed jobs (Target = 1) vs. those who stayed (Target = 0).
- **Insight**: Understand the general job change trend in the dataset.
    
2️⃣ Job Change vs. Gender
- Barplot (hue = gender): Compare Target distribution across different genders.
- **Insight**: Identify whether male, female, or other employees are more likely to switch jobs.
    
3️⃣ Job Change Based on Last New Job
- Barplot: Analyze how long ago employees last changed jobs (last_new_job) and its impact on Target.
- **Expectation**: Employees with longer gaps may be less likely to change jobs again.
    
4️⃣ Job Change Based on Experience
- Boxplot/Bar Plot: Compare experience distribution for those who changed jobs vs. those who didn’t.
- **Insight**: Employees with less experience may switch jobs more frequently.
    
5️⃣ Job Change Based on Training Hours
- Boxplot/: Analyze whether employees with more training hours are less likely to leave.
- **Expectation**: Higher training hours may correlate with higher job retention.

### Conclusion

This analysis provides valuable insights into the factors affecting job change decisions. The findings can help businesses design strategies to improve employee retention by focusing on key influencing variables such as experience, training hours, and job stability.

