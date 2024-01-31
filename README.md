# Analyzing Sleep Disorder in Workers

## Table of Contents
  - Project Overview

  - Tools

  - Data Cleaning
    
  - Exploratory Data Analysis

  - Supervised Machine Learning

  - Insights

### Project Overview
A sleep disorder is a medical condition that affects an individual's ability to have a healthy and restorative night's sleep. Sleep is an essential part of our daily routine, and disturbances in this natural process can have profound impacts on physical, mental, and emotional well-being. There are various types of sleep disorders, each characterized by distinct symptoms and underlying causes.
This Supervised Machine learning data science project aims to generate insights and creates a model that effectively predicts predict which patterns are at the hishest risk of sleep disorder and enable healthcare providers to intervene proactively to prevent sleep disorder.

### Tools
 - Python - Data Analysis
 - Matplotlib - For Data Visualizations
 - Seaborn - For Data Visualizations
 - Numpy
 - Pandas
 - Scikit-learn
 - Jupyter notebook - Coding Environment 

### Data Cleaning
In the data preparation phase, i performed the following tasks;

1. Data loading
2. Data Validation
3. Data cleaning
4. Handling Missing Values

### Exploratory Data Analysis
EDA involved exploring the Patient Sleep Disorder Data to answer key questions such as;

 - What is the distribution of Sleep duration by Occupation.
 - What is the distribution of Sleep quality by Occupation.
 - What is the influence of Physical activity on the Quality of Sleep.
 - What is the impact of sleep disoreder on the the quality of sleep.
 - Does Age affects the quality of sleep of an individual.
    
### Supervised Machine Learning
Supervised machine learning is a type of machine learning where the algorithm is trained on a labeled dataset, meaning that the input data is paired with corresponding output labels. The goal of supervised learning is to learn a mapping or relationship between input features and their corresponding output labels, allowing the algorithm to make predictions or classifications on new, unseen data. .  Linear SVC and Logistic Regression achieve the highest accuracy scores, indicating their effectiveness in classification tasks.

### Insights
1.Accountants, on average, enjoy a sleep duration of approximately 7.11 hours. This group exhibits a low degree of variability in sleep duration, as indicated by a small standard deviation.

2.Doctors report an average sleep duration of approximately 6.97 hours, with slightly more variability compared to accountants.

3.Engineers have the highest average sleep duration, around 7.99 hours, with a moderate level of variability.

4.Occupations like Manager and Sales Representative possess a limited amount of data, resulting in less precise insights.

5.Engineers demonstrate the highest sleep quality, with an average duration of roughly 8.41 hours. This group exhibits minimal variability in sleep quality, as indicated by a low standard deviation.

6.Doctors maintain a mean sleep quality of about 6.65 hours, signifying a moderate level of variation in sleep patterns.

7.Nurses display a broader range of sleep quality, with a mean duration of approximately 7.37 hours. Notably, this group has a standard deviation of approximately 1.55, suggesting a more diverse range of sleep experiences.

8.The application of the scipy ttest_ind method indicates a positive association between increased physical activity and improved sleep quality.

9.Utilizing the pinguion anova method, the report underscores the significant role of sleep disorders in shaping individuals' sleep experiences.

10.Middle-aged adults, on average, exhibit the highest sleep quality, characterized by relatively low variability.

11.Elderly individuals report the highest average sleep quality, albeit with slightly more variability.

12.Young adults and older adults fall in between, with their sleep quality averages and variability positioned within the spectrum of the other groups.

13.In predicting patient categorization into one of three groups (No Disorder, Insomnia, Sleep Apnea), Linear SVC and Logistic Regression achieve the highest accuracy scores, indicating their effectiveness in classification tasks.
