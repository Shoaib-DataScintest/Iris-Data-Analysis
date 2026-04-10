# Iris Dataset — Exploratory Data Analysis & Classification

## Project Overview

This project presents a comprehensive **Exploratory Data Analysis (EDA)** and **machine learning classification pipeline** on the Iris dataset. The objective is to analyze feature relationships, identify key patterns, and build a predictive model to classify iris flower species based on measurable attributes.

This work reflects a **data analyst workflow**, combining statistical exploration, visualization, and model evaluation in a structured and reproducible manner.

---

##  Objectives

* Understand dataset structure and feature characteristics
* Perform data cleaning and validation
* Conduct in-depth exploratory data analysis (EDA)
* Identify key feature relationships and distributions
* Build and evaluate a classification model
* Extract actionable insights from data

---

##  Dataset Description

The Iris dataset is a well-known dataset in machine learning containing **150 observations** of iris flowers across three species:

* Setosa
* Versicolor
* Virginica

### Features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

### Target Variable:

* Species (categorical)

---

##  Data Preprocessing

* Verified absence of missing values
* Checked and removed duplicate records
* Ensured correct data types for analysis

---

##  Exploratory Data Analysis (EDA)

The following analyses were performed:

* **Univariate Analysis**
  Distribution of individual features using histograms and KDE plots

* **Bivariate Analysis**
  Scatter plots and boxplots to analyze relationships and class separation

* **Multivariate Analysis**
  Pairplots to observe interactions between multiple features

* **Correlation Analysis**
  Heatmap to identify relationships between numerical features

### Key Observations:

* Strong correlation between **petal length and petal width**
* Clear separability of species based on petal measurements
* Overlap observed in sepal-based features

---

##  Model Development

A **Random Forest Classifier** was implemented due to its:

* Ability to capture non-linear relationships
* Robustness against overfitting
* Built-in feature importance evaluation

### Workflow:

* Feature-target split
* Train-test split (80/20)
* Model training
* Prediction on test data

---

##  Model Evaluation

Evaluation metrics used:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Cross-validation

### Results:

* Achieved high classification accuracy (~95–100%)
* Minimal misclassification between similar species
* Consistent performance across cross-validation

---

##  Feature Importance

Feature importance analysis revealed:

* **Petal length** as the most significant predictor
* Petal-related features dominate classification performance
* Sepal features contribute less comparatively

---

##  Key Insights

* Petal measurements provide strong discriminatory power between species
* Setosa class is perfectly separable, while slight overlap exists between Versicolor and Virginica
* The dataset is highly structured, enabling effective classification with simple models

---

##  Limitations

* Small dataset size (150 samples)
* Lacks real-world noise and missing values
* Model performance may vary on more complex datasets

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

##  How to Run

```bash
pip install -r requirements.txt
```

```bash
jupyter notebook
```

Open the notebook file and run all cells sequentially.

---

##  Project Structure

```
iris-eda-internship/
│
├── iris_analysis.ipynb
├── README.md
└── requirements.txt
```
---

##  Screenshoots

<img width="1057" height="709" alt="image" src="https://github.com/user-attachments/assets/b2b7ce7d-441f-44f6-9837-1d075d71e71b" />
<img width="1643" height="724" alt="image" src="https://github.com/user-attachments/assets/41d089e0-3cd7-471c-83d6-a7c1bd7d103b" />
<img width="807" height="700" alt="image" src="https://github.com/user-attachments/assets/7378ece0-65ac-4e11-b8d9-e80a4c5a058d" />



---


---

##  Conclusion

This project demonstrates a complete data analysis pipeline, from raw data exploration to model evaluation. The findings highlight the importance of feature selection and confirm that **petal-based features are critical for accurate classification**.

---

## Repository Link

https://github.com/Shoaib-DataScintest/Iris-Data-Analysis

---

##  Author

Muhammad Shoaib Inksar
(Data Analyst | Machine Learning Enthusiast)
