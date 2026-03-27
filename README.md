**Student Performance Analysis Using Data Science (250 Students Dataset)**



**1.Overview**

In today’s education system, understanding student performance is essential for improving academic outcomes and providing personalized support. This project, titled “Student Performance Analysis”, focuses on analyzing the academic data of 250 students using data science techniques.

The project aims to explore how different factors such as subject marks, attendance percentage, and internal assessment scores contribute to a student’s overall performance. By applying data preprocessing, exploratory analysis, and machine learning algorithms, meaningful insights are generated.

Additionally, a predictive model is developed to estimate student performance, which can be useful for educators to identify students who may require extra attention.

**2. Dataset Description**

The dataset used in this project is synthetically generated to simulate a real-world academic environment. It contains 250 student records, each representing an individual student.

**Dataset Features:**
Student_ID: Unique identifier assigned to each student
Name: Student name generated using the Faker library
Gender: Male or Female
Department: CSE, IT, or ECE
Year: Academic year (1st, 2nd, 3rd)
Maths Marks: Scores between 50 and 100
Science Marks: Scores between 50 and 100
English Marks: Scores between 40 and 100
Attendance (%): Percentage between 50 and 100
Internal Marks: Scores between 2 and 25

The dataset is designed to closely resemble real academic data used in educational institutions.

**3. Objectives of the Project**

The main objectives of this project include:

To analyze student academic performance using structured data
To identify key factors that influence student success
To perform data cleaning and preprocessing
To conduct exploratory data analysis (EDA)
To develop a machine learning model for performance prediction
To generate insights that can help improve teaching strategies
**4. Project Highlights**
Creation of a realistic dataset using Faker
Implementation of complete data preprocessing pipeline
Detailed exploratory analysis with multiple perspectives
Development of predictive machine learning models
Visualization of data for better understanding
Generation of actionable insights
**5. Data Preprocessing**

Data preprocessing is a critical step that ensures the dataset is clean, consistent, and suitable for analysis.

**Steps Performed:**
**1.Handling Missing Values:**
Missing values are identified using isnull() and handled appropriately using techniques like forward fill or mean substitution.
**2.Removing Duplicates:**
Duplicate entries are removed to maintain data integrity.
**3.Encoding Categorical Variables:**
Text-based columns such as Gender, Department, and Year are converted into numerical values using Label Encoding.
**4.Feature Scaling:**
Numerical features are standardized using StandardScaler to ensure uniformity in data distribution.
**5.Feature Selection:**
Irrelevant columns such as Student_ID and Name are removed before modeling.
These preprocessing steps improve the quality of data and enhance model performance.

**6. Exploratory Data Analysis (EDA)**

EDA is performed to understand the structure and relationships within the dataset.

**Key Analyses:**
*Distribution of marks across different subjects
*Department-wise comparison of performance
*Gender-based academic trends
*Relationship between attendance and academic scores
*Correlation analysis between features
**Insights from EDA:**
*Students with higher attendance generally score better
*Internal marks have a strong impact on final performance
*Slight variations exist across departments
*EDA provides a deeper understanding of the dataset and guides model building.

**7. Data Visualization**

Visualization techniques are used to present insights clearly and effectively.

**Types of Visualizations:**
**Bar Charts:** Compare subject-wise marks
**Pie Charts:** Show gender and department distribution
**Scatter Plots:** Analyze attendance vs marks relationship
**Heatmaps:** Display correlations between variables

👉 Visualization enhances understanding and communication of results.

**8. Tools and Technologies Used**

The project is implemented using the following tools and libraries:

Python – Core programming language
Pandas – Data manipulation and analysis
NumPy – Numerical computations
Matplotlib – Basic data visualization
Seaborn – Advanced visualization
Scikit-learn – Machine learning algorithms
Faker – Synthetic data generation
**9. Results and Findings**

The analysis and model implementation led to the following conclusions:

Attendance plays a significant role in academic performance
Internal marks strongly influence final results
Students from different departments show slight performance variation
The machine learning model provides accurate and reliable predictions

👉 These findings can help improve academic strategies.

**10. Pipeline Workflow**

The project follows a structured pipeline:

Data Generation
Data Collection and Loading
Data Cleaning
Data Preprocessing
Exploratory Data Analysis
Model Training
Model Evaluation
Prediction Generation
**11. Generating Predictions**

The trained model can be used to predict student performance:

Input new student data (marks, attendance, etc.)
Model processes the input
Output is predicted performance score

👉 This helps identify students who may need academic support.

**12. Future Enhancements**

The project can be improved in several ways:

Use real-world academic datasets
Apply advanced algorithms like XGBoost or Neural Networks
Include additional features such as study hours and extracurricular activities
Develop a web-based application
Integrate dashboards using Power BI or Tableau
**13. Applications**

This project has practical applications in education:

Monitoring student progress
Identifying weak students
Supporting teachers in decision-making
Enhancing academic performance strategies
**14. Limitations**
Dataset is synthetic and may not reflect real-world complexity
Limited number of features
Small dataset size (250 students)

**OUTPUT SCREENSHOTS**

<img width="843" height="587" alt="Screenshot 2026-03-27 100029" src="https://github.com/user-attachments/assets/2018e402-b11b-4889-8d10-db682929d8f3" />

<img width="665" height="575" alt="image" src="https://github.com/user-attachments/assets/0d50b270-5a9b-4b00-b473-abd9f1ba20dc" />

<img width="682" height="587" alt="image" src="https://github.com/user-attachments/assets/cd718558-2367-4a39-a1c0-9765d65466eb" />

<img width="809" height="582" alt="image" src="https://github.com/user-attachments/assets/c4ed8911-3323-4f5e-b1f7-df2ed77552aa" />

<img width="811" height="578" alt="image" src="https://github.com/user-attachments/assets/9f68f9ab-dbf5-4ee6-ac97-2ecdffb2c3c1" />

<img width="842" height="570" alt="image" src="https://github.com/user-attachments/assets/1a7561c0-c0f2-48b4-8485-ea68ca562019" />

<img width="1134" height="782" alt="image" src="https://github.com/user-attachments/assets/4593799b-222b-46d2-ba43-e7962f93cc02" />

<img width="798" height="606" alt="image" src="https://github.com/user-attachments/assets/ea7b1582-ff23-4429-bd3c-7a7c06e49d3e" />











**15. Author Information**

Name: KASTHURI.T
Course: BCA
Project Title: Student Performance Analysis
Year: 2026

**16. Conclusion**

This project demonstrates the effective use of data science and machine learning techniques in analyzing student performance. 
By transforming raw data into meaningful insights, it provides valuable support for improving academic outcomes.

The predictive model developed in this project can assist educators in identifying trends and making informed decisions, ultimately 
contributing to better educational systems.




