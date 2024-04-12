Social Media Impact on Mental Health Analysis
----------
Introduction
------
This project aims to analyze the impact of social media usage on various mental health factors, including ADHD, anxiety, self-esteem, and depression. The analysis is based on a survey dataset that collects information on social media usage, demographic characteristics, and mental health-related questions.

Dataset
--------
The dataset used in this project is called "social_media.csv" and contains the following columns:

Age,
Gender,
Relationship Status,
Occupation,
Social Media User?,
Platforms Used,
Hours Per Day,
ADHD Q1,
ADHD Q2,
ADHD Q3,
ADHD Q4,
Anxiety Q1,
Anxiety Q2,
Self Esteem Q1,
Self Esteem Q2,
Self Esteem Q3,
Depression Q1,
Depression Q2,
Depression Q3,

Data Preprocessing
------
1. The data preprocessing steps include:

2. Renaming the columns to more descriptive names.

3. Handling missing or null values, such as normalizing the "Self Esteem Q2" column.

4. Aggregating the survey questions into composite scores for ADHD, Anxiety, Self-Esteem, and Depression.

5. Handling the "Hours Per Day" column by converting the text values to numeric values.

6. Addressing the "Social Media User?" column by replacing "No" answers with "Yes".

7. Categorizing the "Platforms Used" column into broader categories: Social Networks (SN), Media Sharing (MS), and Discussion Forums (DF).

Data Visualization
---
The project includes various data visualization techniques to explore the relationships between the variables:

1. Age distribution by occupation

2. Age group frequency

3. Gender frequency

4. Occupation frequency

5. Relationship status distribution

6. Hours per day vs. total mental health score

7. Hours per day vs. occupation

8. Total score by platforms used

9. Occupation vs. anxiety score

Model Evaluation
-----
The project implements and evaluates several machine learning models to predict the mental health scores:

1.Random Forest Classifier

2.Logistic Regression

3.Decision Tree Classifier

4.Support Vector Machine (SVM)

5.The models are trained and evaluated using accuracy scores. The results are visualized in a bar graph.

Requirements
--
The project requires the following Python libraries:

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

SciPy

These libraries can be installed using pip:

