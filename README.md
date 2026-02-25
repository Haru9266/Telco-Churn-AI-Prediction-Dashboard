# Telco-Churn-AI-Prediction-Dashboard
An end-to-end churn prediction project using Artificial Neural Networks (ANN) and Python, featuring a professional Power BI Dashboard for actionable business insights


## 📡 Telco Customer Churn Prediction & AI-Powered Dashboard
## 📌 Project Overview
Customer churn is a major challenge in the telecom industry. This project provides an end-to-end solution to identify "At-Risk" customers. I developed an Artificial Neural Network (ANN) model to predict churn with high accuracy and built a Power BI Dashboard to translate complex data into actionable business insights.

### 🖼️ Project Showcase
## 📊 Interactive Power BI Dashboard
<img width="1920" height="1080" alt="6-Proj-Power-BI-1" src="https://github.com/user-attachments/assets/9e8dd326-3b43-4142-9f7c-c262dda67eeb" />

 The final dashboard featuring KPI cards, churn trends, and segment analysis.


 ### 📊 Exploratory Data Analysis (EDA)
Before building the model, I analyzed the target variable distribution.
<img width="1920" height="1080" alt="6-Proj-Churn distribution" src="https://github.com/user-attachments/assets/4dc329df-182c-4ad9-892d-83c72d9080b2" />

*Insight: Visualizing the ratio of churned vs. retained customers.*


# Model Development (ANN)
I built an Artificial Neural Network with multiple layers. Here is the training code:

<img width="1920" height="886" alt="6-Proj-Model Summary-ANN" src="https://github.com/user-attachments/assets/22755e1f-eae5-4b5d-9df4-7cf1b482c08f" />


## 🧠 Model Training Progress
To ensure the model was learning correctly, I tracked the accuracy over 50 epochs.

<img width="1920" height="1080" alt="6-Proj-Model acuracy" src="https://github.com/user-attachments/assets/0faa84a9-9f8b-4989-84a8-6158abed7e36" />


Observation: The graph shows steady growth, reaching a Baseline Accuracy of 0.8211.

Model Evaluation (Results)
I used a Confusion Matrix and a Classification Report to verify the predictions.

<img width="1920" height="891" alt="6-Proj-Heatmap" src="https://github.com/user-attachments/assets/b712ab35-d311-46ea-9a6a-886f41cc626e" />

<img width="1920" height="1080" alt="6-Poj-ANN PERFORMANCE SUMMARY" src="https://github.com/user-attachments/assets/5b016fcf-be4a-4f58-a0f8-8755b64e7b47" />

 These metrics confirm the model's ability to identify churners correctly.

## 🛠️ Tech Stack
Programming: Python (Pandas, NumPy, Matplotlib, Seaborn)

Deep Learning: TensorFlow / Keras (Artificial Neural Networks)

Data Engineering: Excel, Power Query

Business Intelligence: Microsoft Power BI (DAX, Interactive UI)

# Phase 2: Data Engineering & BI (Power BI)
Power Query: Cleaned and transformed the Python model output for visualization.

DAX Measures: Created custom measures for Churn Rate %, Total Customers, and Revenue Impact.

UI/UX Design: Implemented a modern Dark/Teal theme with 3D shadow effects for a premium user experience.

## 🚀 Key Business Insights
 Contract Risk: Customers on Month-to-Month contracts have the highest churn rate.

 Service Impact: Fiber Optic users are leaving faster, suggesting possible pricing or   service quality issues.

 AI Retention: The model successfully flags at-risk customers, allowing the marketing   team to offer targeted discounts before they leave.

# 📂 Repository Structure
Pro-6-Telco Customer Churn.ipynb: Full Python code for EDA & ANN modeling.

processed_telco_data.csv: Cleaned dataset with churn predictions.

Telco_Churn_Dashboard.pbix: Power BI source file.
