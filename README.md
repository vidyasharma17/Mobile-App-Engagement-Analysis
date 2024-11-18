# Mobile App Engagement and User Behavior Analysis

## Overview
This project focuses on analyzing mobile app user engagement and behavior patterns to derive actionable insights for product growth, user retention, and feature prioritization. It leverages **SQL**, **Python**, and **Machine Learning** techniques to explore user data, segment users, and predict engagement levels. The analysis is supplemented with compelling visualizations to effectively communicate insights.

---

## Objectives
- Analyze app engagement metrics to understand user activity patterns.
- Segment users into distinct behavioral clusters using **K-Means clustering**.
- Predict user behavior classes using a **Random Forest classifier**.
- Identify key drivers of user engagement through **feature importance analysis**.
- Provide actionable recommendations for product and marketing strategies.

---

## Technologies Used
### Programming Languages
- Python
- SQL

### Libraries and Tools
- **Data Manipulation**: Pandas, NumPy
- **Visualization**: Seaborn, Matplotlib
- **Machine Learning**: Scikit-learn
- **Clustering**: K-Means
- **Dashboarding**: Tableau (optional dashboards)

---

## Dataset
The dataset used in this project includes the following features:

### App Usage Metrics
- **App Usage Time (min/day)**
- **Screen On Time (hours/day)**
- **Data Usage (MB/day)**
- **Battery Drain (mAh/day)**

### User Demographics
- **Age**
- **Gender**
- **Device Model**
- **Operating System**

### User Behavior Class
- A target variable representing **user engagement level**.

---

## Project Workflow
### 1. Data Preprocessing
- Removed missing values and duplicates.
- Encoded categorical variables using **one-hot encoding**.
- Scaled features for clustering and machine learning.

### 2. SQL Analysis
- Queried engagement metrics:
  - Average app usage time by behavior class.
  - Distribution of operating systems among users.
  - High data-consuming users.
- Performed cohort analysis for retention metrics (optional).

### 3. Exploratory Data Analysis (EDA)
- Visualized relationships between:
  - App usage time and screen-on time.
  - Engagement metrics across different age groups and operating systems.

### 4. K-Means Clustering
- Clustered users into three segments based on app engagement metrics:
  - **Cluster 0**: Highly engaged users with high data consumption.
  - **Cluster 1**: Moderately engaged users with balanced metrics.
  - **Cluster 2**: Low engagement users at risk of churn.

### 5. Random Forest Classification
- Trained a supervised model to predict **User Behavior Class**.
- Hyperparameter tuning improved model performance.
- Evaluated the model with accuracy and feature importance.

### 6. Visualizations
- Visualized clustering patterns and engagement metrics using **scatterplots** and **boxplots**.
- Highlighted key drivers of engagement through feature importance plots from the Random Forest model.

### 7. Recommendations
- **Retention Strategies**: Focus on re-engaging low-engagement users.
- **Growth Strategies**: Encourage moderately engaged users to transition into highly engaged users.
- **Loyalty Programs**: Reward highly engaged users to maintain satisfaction.

---


