# EDA and Feature Engineering: Student Performance Indicator

## 1) Problem Statement
The objective of this project is to understand how students' performance (test scores) is affected by various factors such as Gender, Ethnicity, Parental Level of Education, Lunch, and Test Preparation Course.

## 2) Data Collection
- **Dataset Source**: [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977)
- **Dataset Details**: The dataset consists of 8 columns and 1000 rows.

## 3) Dataset Information
- **gender**: Sex of the students (Male/Female)
- **race/ethnicity**: Ethnicity of the students (Group A, B, C, D, E)
- **parental level of education**: Parents' final education (Bachelor's degree, some college, master's degree, associate's degree, high school)
- **lunch**: Having lunch before the test (standard or free/reduced)
- **test preparation course**: Test preparation course status (complete or not complete)
- **math score**: Students' scores in Math
- **reading score**: Students' scores in Reading
- **writing score**: Students' scores in Writing

## 4) Exploratory Data Analysis (EDA)
The analysis includes various steps to understand and visualize the data. Here are the key steps and insights derived from the analysis:

### Data Summary
- The dataset contains 1000 rows and 8 columns.
- There are no missing values in the dataset.
- No duplicate values were found.

### Feature Analysis
- **Numerical Features**: `math_score`, `reading_score`, `writing_score`
- **Categorical Features**: `gender`, `race/ethnicity`, `parental level of education`, `lunch`, `test preparation course`

### Derived Features
- **Total Score**: Sum of `math_score`, `reading_score`, and `writing_score`.
- **Average Score**: Average of the total score.

### Visualizations and Insights
1. **Distribution of Average Scores**:
   - Histograms of average scores show the overall distribution and the distribution by gender.
   - **Insight**: Female students tend to perform better than male students.

2. **Impact of Lunch on Performance**:
   - Histograms showing average scores with a hue of lunch type.
   - **Insight**: Standard lunch helps students perform better in exams, regardless of gender.

3. **Parental Level of Education**:
   - Histograms showing average scores with a hue of parental education.
   - **Insight**: Parental education generally does not affect student performance. However, male students with parents holding an associate's or master's degree tend to perform better.

4. **Race/Ethnicity and Performance**:
   - Histograms showing average scores with a hue of race/ethnicity.
   - **Insight**: Students from groups A and B tend to perform poorly in exams, irrespective of gender.

5. **Correlation Analysis**:
   - A heatmap showing the correlation between math, reading, writing scores, total score, and average score.
   - **Insight**: Strong correlation between the scores in different subjects.

## Conclusion
This project analyzed the impact of various factors on students' performance using the given dataset. Key factors such as gender, lunch type, and race/ethnicity showed significant influence on performance. However, parental education had a varied impact, more pronounced for male students with higher parental education.

This analysis can help educators and policymakers to identify and support underperforming groups, ensuring equal opportunities for all students.
