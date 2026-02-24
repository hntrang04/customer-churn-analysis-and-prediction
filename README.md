# Customer Churn Analysis and Prediction in E-commerce

## 1. Overview

This project presents an end-to-end **data science workflow** to address the problem of **customer churn prediction** in the e-commerce domain.

Customer retention is a critical factor for sustainable business growth. By identifying customers who are likely to churn at an early stage, businesses can proactively design effective retention strategies.

The project uses the *E-commerce Customer Churn Analysis and Prediction* dataset from Kaggle and applies techniques ranging from **data preprocessing**, **exploratory data analysis (EDA)**, **feature engineering**, to **training and comparing multiple machine learning models**.  
The final outcome includes not only a high-performing predictive model but also **interactive dashboards and visualization products** that translate data into actionable business insights.



## 2. Project Objectives

The main objectives of this project are:

- **Analyze and identify** key factors influencing customer churn behavior.
- **Build and compare** multiple machine learning models to select the most effective one.
- **Propose data-driven business recommendations** to reduce churn based on analytical insights.



## 3. Project Structure

      ├── 1.Dataset/       # Raw and cleaned datasets (.csv)
      ├── 2.Preprocessing/ # Data preprocessing notebooks
      ├── 3.EDA/           # Exploratory Data Analysis notebooks
      ├── 4.Visualization/ # Power BI files, Flourish links, website demo source code
      ├── 5.Modeling/      # Model training and evaluation notebooks
      ├── 6.Report/        # Final report and presentation
      └── README.md        # Project documentation


## 4. Methodology

### 4.1 Data Preprocessing

- **Data cleaning:** Standardizing inconsistent categorical values (e.g., "Phone" vs. "Mobile Phone").
- **Missing value handling:** Applying appropriate imputation strategies (median, conditional imputation).
- **Outlier treatment:** Using the **IQR method** and **capping techniques** to handle extreme values.

### 4.2 Exploratory Data Analysis (EDA)

- Conducted **univariate and multivariate analysis** to discover trends, patterns, and churn-related insights.
- Insights were visualized through **interactive Power BI dashboards**.

### 4.3 Feature Engineering & Selection

- **Feature creation:** Introduced `DevicePerTenure` to capture customer technology adoption behavior.
- **Feature selection:** Combined **correlation analysis**, **Chi-squared tests**, and **Cramér’s V** to remove irrelevant features and reduce multicollinearity.

### 4.4 Modeling

- Built and compared **8 machine learning models**:
  - Logistic Regression
  - KNN
  - SVM
  - Random Forest
  - Gradient Boosting
  - XGBoost
  - LightGBM
  - MLP
- Used **Pipelines** for scaling (`StandardScaler`) and encoding (`OneHotEncoder`).
- Addressed class imbalance using `class_weight` and **SMOTE**.
- Evaluated models with **10-fold Stratified Cross-Validation**.

### 4.5 Model Evaluation

- Evaluation metrics included `Accuracy`, `ROC-AUC`, and a strong focus on **`F1-score`**, **`Precision`**, and **`Recall`** for the churn class to reflect business impact.



## 5. Key Results

- **EDA Insights:** High churn rates were observed among new customers (0–6 months), customers purchasing fashion-related products, and customers with complaints.
- **Best-performing model:** **XGBoost** achieved the best overall performance.



## 6. Visualization Products

- **Power BI Dashboard:** A system of **5 interactive report pages** providing a 360-degree view of customer churn, from executive overview to model performance.
- **Flourish Data Story:**  
  https://public.flourish.studio/story/3520181/  
  An interactive storytelling experience illustrating the customer churn journey using visualizations such as **Parliament Charts** and **Sankey Diagrams**.
- **Website Demo:**  
  https://pttqdl-webdemo.vercel.app/  
  A demo web application built with **React & TypeScript**, allowing users to upload CSV files and generate analytical visualizations dynamically.



## 7. Academic Information

- **University:** University of Information Technology – VNU HCMC  
- **Faculty:** Faculty of Information Science and Engineering
- **Course:** Data Analysis and Visualization (IE313.Q11)  
- **Instructor:** MSc. Phạm Nguyễn Phúc Toàn  



## 8. My Contribution

- Performed data preprocessing and feature engineering.
- Built, trained, and evaluated machine learning models (**LightGBM, MLP**).
- Designed interactive visualizations using **Power BI** and **Flourish**.
- Authored the project report and presentation slides.



## 9. Contact
**Huỳnh Ngọc Trang**  
- **Email:** hntrang04@gmail.com  
- **LinkedIn:** [Trang Huynh Ngoc](https://www.linkedin.com/in/trang-huynh-ngoc-18128b353/)
