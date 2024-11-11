# Customer Churn Analysis and Prediction Using Machine Learning

## **Project Overview**
This project analyzes customer churn data for **PowerCo**, a major energy utility company focused on retaining its customers. The goal is to understand the factors driving customer churn and develop a predictive model to help PowerCo identify high-risk customers and implement preventive actions.

## **Table of Contents**
- [Project Overview](#project-overview)
- [Business Understanding & Hypothesis Framing](#business-understanding--hypothesis-framing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Findings and Recommendations](#findings-and-recommendations)
- [Technologies Used](#technologies-used)

## **Business Understanding & Hypothesis Framing**
PowerCo aims to understand why customers are churning to develop effective retention strategies. The primary hypothesis is that **price sensitivity** may be the most influential factor for customer churn. Through this analysis, I explored various factors affecting churn and validate the hypothesis.

## **Exploratory Data Analysis**
Created visualizations to highlight key trends and factors potentially contributing to churn. This exploration provided valuable insights into customer behaviors and identified initial indicators for churn.

## **Feature Engineering**
- Applied feature engineering techniques to test the hypothesis and enrich the dataset for deeper analysis.
- Built new features tailored to PowerCo's data to improve model prediction accuracy.

## **Modeling**
- Developed a predictive model using the **Random Forest** algorithm to classify and predict churn probability.
- Optimized the model, achieving an **accuracy of 90%** in predicting customer churn.

## **Findings and Recommendations**
The analysis identified that **net margin** and **12-month consumption** are the primary drivers of customer churn, indicating that customers are more likely to leave based on their overall financial engagement and usage patterns. While **price sensitivity** does contribute to churn, it appears as a weaker factor rather than a main driver.

To address the hypothesis, "Is churn driven by customers' price sensitivity?"—the results from feature importance analysis suggest that **price sensitivity is a minor contributor to churn** rather than a significant influencing factor.

## **Technologies Used**
- **Python**: For data manipulation, analysis, and modeling
- **Pandas & NumPy**: For data handling and preprocessing
- **Matplotlib & Seaborn**: For data visualization
- **Scikit-Learn**: For model building and evaluation

---

