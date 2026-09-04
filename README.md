
# 💻 Software Developer Salary Prediction

> A data-driven machine learning project that explores developer salary trends and predicts salary outcomes using data preprocessing, exploratory data analysis, feature engineering, and Linear Regression.

## 📌 About the Project

This project analyzes software developer salary data to understand the factors that influence salary and build a predictive model for salary estimation.

The analysis focuses on factors such as **experience level, job role, and location**, using data preprocessing and exploratory data analysis to identify patterns and relationships within the dataset.

A **Linear Regression** model is then trained to predict salary based on the selected features.

## 🎯 Objectives

- Analyze the dataset using data preprocessing and EDA
- Identify important factors affecting developer salaries
- Explore relationships between experience and salary
- Detect and handle duplicate, inconsistent, and missing values
- Perform feature engineering
- Build a machine learning model for salary prediction
- Evaluate the model using regression metrics

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Linear Regression
   ↓
Model Evaluation
   ↓
Salary Prediction
````

## 📊 Exploratory Data Analysis

The project includes several EDA techniques:

* Correlation analysis
* Experience vs Salary analysis
* Salary distribution
* Outlier detection
* Correlation heatmap
* Visualization of relationships between variables

The analysis indicates a **positive relationship between experience and salary**, while experience and job role are identified as important factors influencing salary.

## 🧹 Data Preprocessing

The dataset was prepared for analysis and modelling through:

* Duplicate value detection and removal
* Handling inconsistent values
* Handling missing values
* Selection of relevant features
* Removal of irrelevant or redundant features

These steps were performed to improve data quality and prepare the dataset for machine learning.

## 🤖 Machine Learning Model

### Linear Regression

A Linear Regression model was implemented to predict developer salaries from the selected input features.

The dataset was divided into training and testing sets so that the model could be evaluated on unseen data. Feature scaling was also applied before model training.

## 📈 Model Evaluation

The model was evaluated using:

* **R² Score**
* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**

Actual and predicted salary values were also compared visually to understand the model's predictive performance.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📁 Project Structure

```text
software-developer-salary-prediction/
│
├── devs_salary_prediction.ipynb
├── data_dictionary.csv
├── project-report.pdf
├── train.csv
├── test.csv
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

> **Dataset note:** `train.csv` and `test.csv` originate from a Kaggle dataset. Their inclusion and redistribution are subject to the original dataset's license and terms.

## 📌 Results & Insights

The analysis found that:

* Developer experience has a positive relationship with salary.
* Job role and experience are important factors affecting salary.
* Salary distributions contain variation that can be explored through EDA.
* Linear Regression provides a baseline approach for salary prediction.

The project report describes the resulting model as providing meaningful salary estimation and insights for data-driven decision-making.

## 🚀 Future Improvements

Possible extensions include:

* Experimenting with advanced machine learning algorithms
* Using larger and more diverse datasets
* Comparing multiple regression models
* Improving feature engineering
* Deploying the prediction model as a web application

## 📚 References

* Kaggle
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## 👩‍💻 Author

**Sabitha G**

BSc Computer Science with Cognitive Systems

```
