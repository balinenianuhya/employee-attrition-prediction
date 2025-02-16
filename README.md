# 🏢 Employee Attrition Prediction

## 📌 Project Overview
Employee attrition is a major concern for businesses, impacting productivity and costs. This project aims to predict whether an employee will leave the company based on work engagement, job role, and demographic factors. 

Using **machine learning**, we analyze key features such as **satisfaction level, monthly hours, promotions, and salary levels** to identify employees at risk of leaving.

## 📂 Dataset
- **Source:** Internal/Simulated HR dataset  
- **Total Records:** 1,000 employees  
- **Features:**  
  - **Age** (Employee’s age)  
  - **Gender** (Male/Female)  
  - **Department** (HR, IT, Sales, etc.)  
  - **Job Title** (Specific role within the company)  
  - **Satisfaction Level** (Work satisfaction on a scale of 0-1)  
  - **Average Monthly Hours** (Hours worked per month)  
  - **Years at Company** (Total tenure in years)  
  - **Promotion in Last 5 Years** (0 = No, 1 = Yes)  
  - **Salary Level** (Low, Medium, High)  
  - **Attrition** (Target variable: 1 = Left, 0 = Stayed)  

## 🔍 Steps Taken
1. **Data Preprocessing**
   - Checked for missing values and handled categorical encoding.
   - Scaled numerical features for model performance.

2. **Exploratory Data Analysis (EDA)**
   - Visualized attrition rates across different factors.
   - Correlation heatmap to understand feature relationships.
   - Analyzed trends in satisfaction level and working hours.

3. **Feature Engineering**
   - One-hot encoding for categorical variables.
   - Normalization of numerical data.

4. **Model Training**
   - Trained machine learning models:  
     - **Logistic Regression**  
     - **Decision Tree**  
     - **Random Forest**  
   - Split dataset into 80% training and 20% testing.

5. **Evaluation**
   - Compared models using **Accuracy, Precision, Recall, and F1-score**.
   - Plotted **Confusion Matrix** to analyze predictions.

## 📊 Results
- **Best Performing Model:** Random Forest  
- **Accuracy:** 89%  
- **Precision:** 87%  
- **Recall:** 85%  
- **F1-Score:** 86%  

The model successfully identifies employees who are likely to leave with high accuracy.

## 🚀 How to Run
1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/employee-attrition.git
   cd employee-attrition


