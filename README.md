# **🛒 Online Shoppers Purchasing Intention – Machine Learning Project**

A complete end-to-end Machine Learning classification workflow

This project predicts whether an online visitor will make a purchase using real session-based behavioral data of online shoppers.
It includes EDA, preprocessing, model training, evaluation, comparison, and insights.

# 📌**Project Overview**

The goal of this project is to build a machine learning model that can classify purchase intention based on user website behavior features such as:

Administrative pages visited

Informational/Product pages visited

Bounce Rates

Exit Rates

Page Values

Visitor Type

Weekend Indicator

Special Day Indicator

## The workflow includes:

✔ Importing dependencies
✔ Loading & exploring dataset
✔ Exploratory Data Analysis (EDA)
✔ Data preprocessing
✔ Model training
✔ Model comparison
✔ Final insights

## **📂 Dataset Information**

Dataset: Online Shoppers Purchasing Intention

## **🎯 Target Variable: Revenue**

1 → User made a purchase

0 → No purchase

📊 Dataset Size

Rows: 12,330

Columns: 18

🔑 Key Features

Administrative / Duration

Informational / Duration

ProductRelated / Duration

BounceRates

ExitRates

PageValues

SpecialDay

OperatingSystem

Browser

Region

TrafficType

VisitorType

Weekend

## 🧠 **Machine Learning Workflow**
1️⃣ Importing Dependencies

Libraries used:

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

2️⃣ Load Dataset

The dataset is loaded and checked for:

Shape

Columns

Data types

Null values

Summary statistics

3️⃣ Exploratory Data Analysis (EDA)

Performed using:

Distribution plots

Bar charts

Correlation heatmap

Revenue-based comparisons

EDA insights:

Important numeric variables

Visitor behavior patterns

Features strongly influencing purchases

4️⃣ Data Preprocessing

**Includes:**

✔ Encoding Categorical Variables

Label Encoding / One-Hot Encoding as needed.

✔ Feature Scaling

StandardScaler for numeric features.

✔ Train-Test Split
Train: 80%
Test: 20%


With stratify to preserve class balance.

## **🤖 Machine Learning Models** Used
🔹 Logistic Regression

Baseline classification model.

🔹 K-Nearest Neighbors (KNN)

Distance-based classification.

🔹 Decision Tree Classifier

Captures non-linear patterns.

🔹 Random Forest Classifier

Ensemble model — best performance.

## 📊 **Model Evaluation Metrics**

Each model was evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

## 🏆 Best Performing Model: **Random Forest**

✔ Highest Accuracy (~92%)
✔ Best generalization on test data
✔ Identified top predictors of purchase behavior

## ⭐**Top Important Features**

ProductRelated

PageValues

ExitRates

BounceRates

VisitorType

Weekend

## 📈 **Final Insights**

🔹 Higher product-related engagement increases likelihood of purchase
🔹 High exit/bounce rates reduce chance of buying
🔹 Returning visitors are more likely to convert
🔹 PageValues strongly predict purchase probability
🔹 Weekend visitors show slightly higher conversions

## 🧪 **How to Run This Project**
1️⃣ 1️⃣ Clone the Repository 
  ```bash
git clone https://github.com/sagar-analytics/Online-Shoppers-Purchase-Intention-ML.git
cd Online-Shoppers-Purchase-Intention-ML
```
2️⃣ Install Required Libraries
pip install numpy pandas seaborn matplotlib scikit-learn

3️⃣ Open the Notebook

You can run the notebook in:

Google Colab

Jupyter Notebook

VS Code

4️⃣ Run All Cells

The notebook will:

Load dataset

Perform EDA

Preprocess data

Train ML models

Show evaluation metrics

Display feature importance


## 👤 **Author**

**SAGAR SS :**
Data Analyst | Python | Machine Learning
6-Month Internship Experience
