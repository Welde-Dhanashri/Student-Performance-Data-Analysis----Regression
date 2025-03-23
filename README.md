# 📊 Student Performance Analysis
A comprehensive analysis of student performance using various attributes to identify key factors affecting their academic outcomes.

# 📌 Objective
* Perform Exploratory Data Analysis (EDA) on the student performance dataset.
* Identify patterns, trends, and key factors affecting student outcomes.
* Detect and handle missing values and outliers.
* Visualize relationships between variables for insights.

# 📂 Dataset Overview
* Source: xAPI-Edu-Data.csv
* gender: Gender of the student (e.g., Male, Female)
* NationalITy: Nationality of the student
* PlaceofBirth: Where the student was born
* StageID: The stage or level of education the student is in
* GradeID: The grade the student is in
* SectionID: The section the student belongs to
* Topic: The subject the student is studying
* Semester: The semester during which data was recorded
* Relation: Parent’s relationship status
* raisedhands: Number of times the student raised their hand in class
* VisITedResources: Number of resources the student accessed for learning
* AnnouncementsView: Number of announcements the student viewed
* Discussion: Number of discussions the student took part in
* ParentAnsweringSurvey: Whether the student’s parent answered a survey (Yes/No)
* ParentschoolSatisfaction: How satisfied the parent is with the school
* StudentAbsenceDays: Number of days the student was absent
* Class: Performance classification (e.g., "Good", "Average", "Bad") Days

# 📊 Analysis Process

## Data Loading:
* Read the dataset using pandas.

## Data Exploration:
* Shape, Columns, and Data Types

## Summary Statistics
* First and Last Five Rows

## Data Cleaning & Preprocessing:
* Checking and Handling Missing Values
* Detecting Outliers using Box Plots

## Data Visualization:
* Distribution of Student Grades
* Correlation Matrix
* Box Plots for Outlier Detection

## Insights & Findings:
* Participation frequency impacts grades.
* Absenteeism correlates with lower performance.
* Parent's education level influences student success.

# 📈 Technologies Used
* Python (pandas, numpy, seaborn, matplotlib)
* Jupyter Notebook

