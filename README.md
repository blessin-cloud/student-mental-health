# student mental health analysis
### Table Of Content
  -  [Project overview](project-overview)
  -  [Data source](data-source)
  -  [Tools](tools)
  -  [Data cleaning and preparation](data-cleaning-and-preparation)
  -  [Exploratory data analysis](exploratory-data-analysis)
  -  [Data analysis](data-analysis)
  -  [Results](results)
  -  [Recommendations](recommendations)
  -  [References](references)

### Project overview
To understand the key drivers of student burnout and to support early intervention strategies, mental health programs, and academic policy adjustments
### Data Source
 The primary dataset used for this analysis is 'the student mental health and burnout dataset.csv' file from kaggle
  - [download here](https://www.kaggle.com/datasets/sehaj1104/student-mental-health-and-burnout-dataset)
### Tools
 - Excel- Data cleaning
 - Power Bi -Data Visualization and Creating Reports
### Data Cleaning And Preparation
In the initial phase of data preparation, i did the following:
1. Data loading and Inspection
2. handle missing values
3. Standardization of text values
4. check for duplicates
### Exploratory Data Analysis
Eda seeks to find out the following:
1. Analyze student data to identify patterns associated with burnout level.
2. Examine the relationship between academic performance, psychological factors and lifestyle habits.
3. Identify high risk student groups across different demographics and academic programs.
### Data Analysis
      some basic features include:
          --- power Bi
                    totalstudents= countrows('student_mental_health_burnout')
                    averagestress= average(student_mental_health_burnout[stress])
          ---
### Results
1. The burnout rate is higher in students above 24 years by 33.41%
2. The burnout rate is higher in female students by 33.42%
3. The burnout level is higher in students with cgpa(6-7.5) by 33.37%
4. The highest burnout level across the population is low by 50,270
5. The burnout rate is higher in student with poor quality sleep by 33.48%
### Recommendations
1. The management can organize a lecture on sleep routines for students
2. The management can pay more attention to female students, students with medium cgpa and students above 24 years.
### References
Kaggle student mental health and burnout dataset.
