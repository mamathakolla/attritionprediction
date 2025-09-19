📊 Employee Attrition Prediction using KNN
📌 Project Overview

This project focuses on predicting employee attrition (whether an employee is likely to leave the company) using Machine Learning. Employee attrition is a critical issue for organizations, and predictive analytics can help HR departments take proactive steps to improve retention.

📂 Dataset

The dataset contains employee-related attributes such as:

Age, Department, Education, Job Role

Monthly Income, Years at Company, Work-Life Balance

Job Satisfaction, Overtime, etc.

The target variable is Attrition (Yes/No).

⚙️ Methodology

Data Preprocessing

Handled categorical variables using Label Encoding.

Applied feature scaling to normalize numerical attributes.

Split the dataset into 70% training and 30% testing.

Machine Learning Model

K-Nearest Neighbors (KNN):

KNN is a simple, yet effective classification algorithm that predicts the class of a sample based on the majority vote of its nearest neighbors.

Distance metric: Euclidean distance.

Tuned the value of k for optimal performance.

Model Evaluation

Accuracy Score to measure prediction performance.

Confusion Matrix to analyze false positives/negatives.

Compared different k values to identify the most effective setting.

📊 Results

The KNN model achieved good accuracy in predicting employee attrition.

Performance depended on the choice of k; optimal results were obtained with a tuned value.

The model helps in identifying employees at risk of leaving, enabling data-driven HR decisions.

🚀 Technologies Used

Python

Pandas, NumPy (data preprocessing)

Scikit-learn (model training & evaluation)

Matplotlib / Seaborn (data visualization)
