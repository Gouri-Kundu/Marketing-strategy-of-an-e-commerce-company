# E-Commerce Purchase Prediction using Decision Tree

## Project Overview

This project focuses on predicting whether a visitor to an e-commerce website will make a purchase based on their browsing behavior during a session.

An e-commerce company aims to better understand user behavior and improve its marketing strategies. By analyzing session-level data, this model helps identify high-intent users, enabling more targeted and efficient decision-making.

---

## Problem Statement

The objective is to build a **classification model** that predicts the likelihood of a user completing a purchase (`Revenue`) based on their interaction with the website.

* Dataset contains **12,330 user sessions**
* Each session represents a unique visitor
* The data includes both **numerical and categorical features**
* The dataset is **imbalanced**, so performance is evaluated using **F1 Score**
* Benchmark F1 Score: **0.55**

---

## Dataset Description

The dataset includes the following key features:

* **Administrative / Informational / ProductRelated**: Number of pages visited
* **Duration Features**: Time spent on different types of pages
* **BounceRates & ExitRates**: Indicators of user engagement
* **PageValues**: Value of pages leading to a purchase
* **SpecialDay**: Closeness to special events (e.g., holidays)
* **Month, OperatingSystems, Browser, Region, TrafficType**: Categorical features
* **VisitorType**: New or returning visitor
* **Weekend**: Whether the session occurred on a weekend
* **Revenue (Target Variable)**: Indicates whether a purchase was made

---

## Approach

### 1. Exploratory Data Analysis (EDA)

* Analyzed distribution of features
* Checked for missing values and data imbalance
* Explored relationships between features and target variable

---

### 2. Data Preprocessing

* Handled categorical variables
* Applied necessary transformations
* Prepared data for model training

---

### 3. Model Building

* Implemented a **Decision Tree Classifier**
* Applied **pruning techniques** to reduce overfitting and improve generalization

---

### 4. Model Evaluation

* Used **F1 Score** as the evaluation metric due to class imbalance
* Compared performance with the given benchmark

---

## Results

* Model: **Decision Tree Classifier**
* Evaluation Metric: **F1 Score**
* Achieved performance meets/exceeds the benchmark requirement of **0.55**

---

## Tech Stack

* **Python**
* **Pandas, NumPy** – Data handling
* **Matplotlib, Seaborn** – Visualization
* **Scikit-learn** – Model building and evaluation

---

## Project Structure

```
├── MARKETING STRATEGY OF AN e-COMMERCE COMPANY.ipynb   # Main implementation
├── README.md                                          # Project documentation
├── requirements.txt                                   # Dependencies
```

---

## How to Run

1. Clone the repository

```
git clone https://github.com/Gouri-Kundu/Marketing-strategy-of-an-e-commerce-company.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Open the notebook

```
jupyter notebook
```

Or directly view the notebook here:
 https://github.com/Gouri-Kundu/Marketing-strategy-of-an-e-commerce-company/blob/main/MARKETING%20STRATEGY%20OF%20AN%20e-COMMERCE%20COMPANY.ipynb

---

## Key Takeaways

* Built a classification model for a real-world business use case
* Learned handling of **imbalanced datasets**
* Applied **Decision Tree with pruning**
* Used **F1 Score** for reliable evaluation

---

## Future Scope

* Experiment with advanced models
* Improve feature engineering
* Deploy model using web frameworks

---

## Contact

Feel free to connect for discussions or collaboration.

- Email: gourikundu1808@gmail.com  
- LinkedIn: www.linkedin.com/in/gouri-kundu

---
