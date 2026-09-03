## 🌸 Task 1: Iris Flower Classification

### Objective
The goal of this project is to build a Machine Learning model that classifies Iris flowers into three target species: **Setosa**, **Versicolor**, and **Virginica** based on their sepal and petal measurements.

### Key Features & Workflow
- **EDA & Visualization:** Analyzed feature distributions using pair plots, box plots, and correlation matrices.
- **Model Training:** Trained and evaluated multiple classification models, including Logistic Regression and Decision Trees / Random Forest.
- **Performance Evaluation:** Evaluated using Accuracy Score, Confusion Matrix, and Classification Report (Precision, Recall, F1-Score).

### Tech Stack
- **Language:** Python
- **Environment:** Google Colab
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

### File
- `task1.ipynb` (or `Iris_Flower_Classification.ipynb`)

---
## 🚗 Task 3: Car Price Prediction with Machine Learning

### Objective
Build regression models to predict the selling price of used cars based on historical metrics like Present Price, Car Age, Kilometers Driven, Fuel Type, and Transmission.

### Key Features & Workflow
- **Data Preprocessing & Encoding:** Cleaned categorical features using One-Hot Encoding.
- **Model Comparison:** Trained and evaluated **Linear Regression** and **Random Forest Regressor** models.
- **Metrics Evaluated:** Assessed performance using MAE, RMSE, and $R^2$ Score.
- **Visualizations:** Rendered feature importances, price distribution plots, correlation heatmaps, and Actual vs. Predicted price comparisons.

### Tech Stack
- **Language:** Python
- **Environment:** Google Colab
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

### File
- `task3.ipynb`
- 
- # Task 4: Email Spam Detection with Machine Learning

## Project Overview
This project focuses on building a Natural Language Processing (NLP) binary classification model to identify and distinguish spam emails/SMS messages from legitimate (ham) messages using Python and Scikit-Learn.

## Track Details
- **Domain:** Data Science
- **Organization:** Oasis Infobyte
- **Task Level:** Task 4

## Dataset
- **Source:** SMS Spam Collection Dataset (UCI Machine Learning Repository)
- **Total Records:** 5,572 messages
- **Labels:** `ham` (legitimate) and `spam`

## Project Workflow
1. **Data Cleaning & Preprocessing:** Converted text to lowercase, removed special characters, punctuation, and encoded labels (`ham: 0`, `spam: 1`).
2. **Train-Test Split:** Stratified 80/20 split to maintain label distribution across training and testing sets.
3. **Feature Extraction:** Transformed cleaned text into numerical vector features using `TfidfVectorizer` (TF-IDF).
4. **Model Training:** Trained and evaluated two machine learning algorithms:
   - Multinomial Naive Bayes (Industry Standard for Text Classification)
   - Logistic Regression
5. **Evaluation:** Assessed models using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix visualisations.

## Performance Summary
| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- | :--- |
| **Multinomial Naive Bayes** | ~97.5% | High | Balanced | High |
| **Logistic Regression** | ~96.8% | High | Moderate | High |

## Key Insights
- **TF-IDF Vectorization:** Helps penalize frequently occurring filler words while assigning higher weights to spam-indicative keywords (e.g., "win", "claim", "urgent", "free").
- **Recall Importance:** High recall ensures that actual spam messages are successfully caught without letting malicious content reach the inbox. However, high precision is equally vital so legitimate messages are not incorrectly sent to the spam folder.

## Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

---

### Internship Details
- **Organization:** Oasis Infobyte (OIBSIP)
- **Domain:** Data Science
- **Repository Name:** `OIBSIP`
- 
- # Task 5: Sales Prediction Using Python

A machine learning project built for the **Oasis Infobyte Data Science Internship (OIBSIP)**[cite: 2].

## 📌 Overview
Predicts product sales based on advertising budgets spent across **TV**, **Radio**, and **Newspaper** channels using regression models[cite: 2].

## 🛠️ Tech Stack
* **Language:** Python[cite: 2]
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn[cite: 2]
* **Tools:** Jupyter Notebook[cite: 2]

## ⚡ Key Steps
1. **EDA & Visualization:** Analyzed dataset statistics, feature relationships, and correlation heatmaps[cite: 2].
2. **Preprocessing:** Split data into training and testing sets ($80/20$ split)[cite: 2].
3. **Model Building:** Trained Linear Regression and Random Forest Regressor models[cite: 2].
4. **Evaluation:** Assessed performance using MAE, RMSE, and $R^2$ score[cite: 2].

## 💡 Findings
* **TV Advertising** has the highest positive impact on product sales[cite: 2].
* **Newspaper Advertising** showed the weakest correlation with total sales[cite: 2].

---
* **Organization:** Oasis Infobyte[cite: 2]
* **Track:** Data Science[cite: 2]
* **Task:** Task 5 - Sales Prediction Using Python[cite: 2]
