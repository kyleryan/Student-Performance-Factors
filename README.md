## **Student Performance Factors Analysis** by Kyle Ryan

## **Context:**  

In many instances, **school funding is tied to student performance benchmarks**, often the only way for a school or district to secure funding is by **improving student performance on standardized tests**.

## **Objective:**  

I will be exploring the dataset provided with the goal to determine which factors affect the student performance **(exam score)**, and come up with strategies to potentially increase these factors in the real world.

## **EDA Methodology:**

1) Import required libraries  
2) Load dataset CSV as pandas dataframe  
3) Perform an initial data check  
4) Clean data (if needed)  
5) Data exploration  
    A) Identify Outliers  
    B) Univariate Analysis  
    C) Bivariate Analysis  
    D) Correlation Analysis  
    E) Chi-squared Test  
    F) Data Transformation (mapping categorical values to numeric / normality testing)  
6) OLS Regression Modeling  
7) Making Predictions  
8) Conclusions

## **Data Dictionary:**

* **Hours_Studied**: Number of hours spent studying per week.
* **Attendance**: Percentage of classes attended.
* **Parental_Involvement**: Level of parental involvement in the student's education (Low, Medium, High).
* **Access_to_Resources**: Availability of educational resources (Low, Medium, High).
* **Extracurricular_Activities**: Participation in extracurricular activities (Yes, No).
* **Sleep_Hours**: Average number of hours of sleep per night.
* **Previous_Scores	Scores**: Scores from previous exams.
* **Motivation_Level**: Student's level of motivation (Low, Medium, High).  
* **Internet_Access**: Availability of internet access (Yes, No).  
* **Tutoring_Sessions**: Number of tutoring sessions attended per month.  
* **Family_Income**: Family income level (Low, Medium, High).  
* **Teacher_Quality**: Quality of the teachers (Low, Medium, High).  
* **School_Type**: Type of school attended (Public, Private).  
* **Peer_Influence**: Influence of peers on academic performance (Positive, Neutral, Negative).  
* **Physical_Activity**: Average number of hours of physical activity per week.  
* **Learning_Disabilities**: Presence of learning disabilities (Yes, No).  
* **Parental_Education_Level**: Highest education level of parents (High School, College, Postgraduate).  
* **Distance_from_Home**: Distance from home to school (Near, Moderate, Far).  
* **Gender**: Gender of the student (Male, Female).  
* **Exam_Score**: Final   exam score.
