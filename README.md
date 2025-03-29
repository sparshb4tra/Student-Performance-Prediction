# 📚 Student Performance Prediction

## 🎯 Project Overview
**Understanding the Problem Statement**  
This project examines how various factors, such as gender, ethnicity, parental education, lunch type, and test preparation courses, influence students' test scores.  

Higher education institutions aim to deliver quality education, and uncovering patterns in educational data is key to achieving this goal. Insights from data can predict course enrollments, identify flaws in teaching methods, detect unfair practices in online exams, and forecast student performance. This project applies data mining techniques to extract this knowledge.  

Focusing on a classification task, the project evaluates student performance across subjects using methods like decision trees and probabilistic classification. These techniques reveal valuable insights into students' abilities and help identify dropouts or students needing extra support, allowing educators to provide tailored guidance and counseling.


This project leverages a dataset of **2,392 high school students** to analyze the factors influencing academic performance. By examining **demographics, study habits, parental involvement, extracurricular activities, and GPA**, we aim to develop predictive models for student success.

## 📊 Dataset Overview

The dataset provides a rich set of features to explore and model academic performance:

- **Student Information**: Unique ID, age, gender, and ethnicity.
- **Study Habits**: Weekly study time, absences, and tutoring status.
- **Parental Involvement**: Levels of parental support.
- **Extracurricular Activities**: Participation in sports, music, volunteering, etc.
- **Academic Performance**: GPA and categorized grade classes.

## 🏆 Target Variable: `GradeClass`

Students are classified based on GPA:

- **0**: 'A' (GPA ≥ 3.5)
- **1**: 'B' (3.0 ≤ GPA < 3.5)
- **2**: 'C' (2.5 ≤ GPA < 3.0)
- **3**: 'D' (2.0 ≤ GPA < 2.5)
- **4**: 'F' (GPA < 2.0)

## 🔍 Key Insights & Goals

- Identify key **factors influencing student success**.
- Develop **predictive models** to forecast student performance.
- Provide actionable insights for **educators and policymakers**.

## 🚀 Getting Started

### 📥 Installation & Requirements

1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/student-performance-prediction.git
   cd student-performance-prediction
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the notebook to explore and train models:
   ```sh
   jupyter notebook Student_Performance_Prediction.ipynb
   ```

## 📂 Dataset Structure

| Feature             | Description                                                        |
| ------------------- | ------------------------------------------------------------------ |
| `StudentID`         | Unique identifier for each student                                 |
| `Age`               | Age of the student (15-18)                                         |
| `Gender`            | 0: Male, 1: Female                                                 |
| `Ethnicity`         | 0: Caucasian, 1: African American, 2: Asian, 3: Other              |
| `ParentalEducation` | 0: None, 1: High School, 2: Some College, 3: Bachelor's, 4: Higher |
| `StudyTimeWeekly`   | Hours spent studying weekly (0-20)                                 |
| `Absences`          | Number of school absences (0-30)                                   |
| `Tutoring`          | 0: No, 1: Yes                                                      |
| `ParentalSupport`   | 0: None, 1: Low, 2: Moderate, 3: High, 4: Very High                |
| `Extracurricular`   | 0: No, 1: Yes                                                      |
| `Sports`            | 0: No, 1: Yes                                                      |
| `Music`             | 0: No, 1: Yes                                                      |
| `Volunteering`      | 0: No, 1: Yes                                                      |
| `GPA`               | Scale from 2.0 to 4.0                                              |
| `GradeClass`        | Target variable (0 = A, 1 = B, ..., 4 = F)                         |

## 📈 Machine Learning Approach

- **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling features.
- **Exploratory Data Analysis (EDA)**: Identifying patterns and correlations.
- **Model Selection**: Evaluating classification models like Logistic Regression, Decision Trees, and Random Forest.
- **Performance Metrics**: Accuracy, Precision, Recall, and F1-score.

## 💡 Future Enhancements

- **Feature Engineering**: Extracting new insights from existing data.
- **Deep Learning Models**: Exploring neural networks for better predictions.
- **Real-World Implementation**: Adapting the model for school administrators.

## ⚖️ License & Attribution

This dataset, provided by **Rabie El Kharoua**, is licensed under **CC BY 4.0**, allowing usage with proper attribution. This synthetic dataset was created for educational purposes and is ideal for machine learning research.

## 🤝 Contributing

Want to improve this project? Feel free to **fork, contribute, or submit issues!**

## ⭐ Support

If you find this project helpful, **give it a star ⭐ on GitHub!**


