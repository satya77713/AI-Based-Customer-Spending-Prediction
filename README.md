# 🚀 AI-Based Customer Spending Prediction

## 📌 Project Overview

AI-Based Customer Spending Prediction is a Machine Learning project that classifies customers into three spending categories: Low, Medium, and High.

The project uses customer demographic and income-related information to understand spending patterns and build predictive classification models.

This project demonstrates a complete beginner-friendly Machine Learning workflow, from data cleaning and exploratory data analysis to model training, evaluation, and prediction.

**Internship:** Veda Technology  
**Track:** AI & ML  
**Task:** 32 – AI-Based Customer Spending Prediction

## 🎯 Project Objectives

- Understand customer demographic and spending-related data.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Perform feature engineering.
- Visualize customer spending patterns.
- Build machine learning classification models.
- Compare model performance.
- Predict customer spending categories.
- Identify important features influencing predictions.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Joblib

## 📊 Dataset Information

**Dataset Name:** Mall Customers Dataset  
**File Name:** `Mall_Customers.csv`

The dataset contains customer information, including:

| Column | Description |
|---|---|
| CustomerID | Unique customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Customer annual income |
| Spending Score (1-100) | Customer spending score |

### Target Variable

A new target column called `Spending_Category` is created using the spending score.

| Spending Score | Category |
|---|---|
| 1–40 | Low |
| 41–60 | Medium |
| 61–100 | High |

These categories are created during feature engineering and are not provided directly in the original dataset.

## ⚙️ Project Workflow

### 1. Data Loading
- Load the dataset using Pandas.
- Explore the first few records.
- Understand dataset dimensions and structure.

### 2. Data Cleaning
- Check missing values.
- Identify duplicate records.
- Remove duplicate entries.
- Handle missing values.

### 3. Exploratory Data Analysis (EDA)
- Analyze customer age distribution.
- Explore annual income distribution.
- Examine spending category distribution.
- Understand relationships between age, income, and spending score.

### 4. Feature Engineering
- Create Low, Medium, and High spending categories.
- Encode categorical variables.
- Scale numerical features.
- Prepare features for model training.

### 5. Machine Learning Models

**Logistic Regression**
- Implemented as a baseline classification model.
- Used to predict customer spending categories.

**Random Forest Classifier**
- Uses multiple decision trees.
- Helps identify important customer characteristics.

### 6. Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

### 7. Model Comparison

Compare Logistic Regression and Random Forest to understand their classification performance.

### 8. Customer Prediction

Developed a prediction function that accepts customer information, such as gender, age, and annual income, and predicts the spending category.

### 9. Feature Importance

Analyze the importance of customer features using the Random Forest model.

## 📈 Data Visualizations

The project includes the following visualizations:

1. Customer Spending Category Distribution
2. Customer Age Distribution
3. Annual Income Distribution
4. Annual Income vs Spending Score
5. Age vs Spending Score
6. Model Performance Comparison
7. Confusion Matrix
8. Feature Importance

## 📁 Project Structure

```text
AI-Based-Customer-Spending-Prediction/
│
├── Mall_Customers.csv
│
├── Cleaned_Customer_Data.csv
│
├── Customer_Spending_Prediction.ipynb
│
├── Customer_Spending_Model.pkl
│
├── Model_Comparison.csv
│
├── Feature_Importance.csv
│
└── README.md
```

## 🚀 Installation and Execution

### Step 1: Clone the Repository

```bash
git clone https://github.com/satya77713/AI-Based-Customer-Spending-Prediction.git
```

### Step 2: Navigate to the Project Folder

```bash
cd AI-Based-Customer-Spending-Prediction
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter joblib
```

### Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Project

Open `Customer_Spending_Prediction.ipynb` and execute all cells.

Make sure the dataset is available in the same directory.

## 💡 Key Learnings

Through this project, I gained practical experience in:

- Python programming.
- Data cleaning and preprocessing.
- Exploratory Data Analysis.
- Feature engineering.
- Data visualization.
- Machine Learning classification.
- Model evaluation.
- Customer spending analysis.
- Predictive analytics.

## 🎓 Internship Details

- **Organization:** Veda Technology
- **Program:** AI & ML Internship
- **Day:** 32
- **Project:** AI-Based Customer Spending Prediction

## 👨‍💻 Author

**Satya**

GitHub: [@satya77713](https://github.com/satya77713)

## 📝 Conclusion

This project demonstrates how Machine Learning techniques can be used to analyze customer information and classify spending behavior.

By implementing Logistic Regression and Random Forest, the project provides practical experience in developing classification models, evaluating their performance, and understanding customer spending patterns.

⭐ If you find this project useful, please consider giving it a star!

