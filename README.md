🎓 Online MOOC Course Completion Prediction

📘 Project Overview
This project predicts whether a learner will complete an online course (MOOC) based on demographic and engagement data. Using machine learning techniques, it identifies learners who are likely to drop out or successfully complete a course.
This project demonstrates data preprocessing, feature engineering, and classification modeling using PySpark and Scikit-Learn.

🧠 Problem Statement
Many learners enroll in MOOCs but fail to complete them. The goal of this project is to build a predictive model that can estimate the probability of course completion using learner data such as:
Clickstream activity
Assessment scores
Time spent on platform
Demographic details

🧰 Technologies Used
Category	Tools/Libraries
Language	Python
Environment	Google Colab / Jupyter Notebook
Framework	PySpark, Scikit-learn
Data Analysis	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Model	Support Vector Machine (SVM)
Version Control	Git & GitHub
⚙️ Project Workflow

Data Loading – Load MOOC dataset into a Spark DataFrame.
Data Cleaning – Handle null and missing values.
Feature Engineering – Encode categorical variables and scale numerical ones.
Model Building – Train an SVM classifier to predict completion probability.
Model Evaluation – Evaluate using accuracy and F1-score.
Insights – Identify which factors impact learner completion the most.

📊 Dataset
Source: Kaggle - Predict Online Course Engagement Dataset
Target Variable: completed (1 = Completed, 0 = Not Completed)

🚀 How to Run
Clone the repository:
git clone https://github.com/Harshx02/Online_MOOC_Completion.git
cd Online_MOOC_Completion

Open the notebook:
jupyter notebook Online_Course_Completion.ipynb or open directly in Google Colab.
Run all cells sequentially to reproduce results.

📈 Results
Achieved high accuracy and balanced F1-score.
Identified that engagement metrics like time-on-platform and quiz attempts strongly predict completion.
