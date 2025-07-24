📊 Standardization using Scikit-Learn on Social Network Ads Dataset

This project demonstrates how to apply feature standardization using StandardScaler from Scikit-learn, using the Social_Network_Ads dataset. Standardization is a critical preprocessing step in machine learning that improves model accuracy and performance.


---

📁 Dataset Details

Name: Social_Network_Ads.csv

Source: Assumed to be from Kaggle or a typical ML dataset repository

Features:

Age

EstimatedSalary


Target:

Purchased (binary classification: 0 or 1)




---

📌 Key Objectives

✔️ Load and explore the dataset

✔️ Check for null/missing values

✔️ Visualize feature distributions before and after scaling

✔️ Apply StandardScaler to Age and EstimatedSalary

✔️ Compare the effects of scaling using plots

✔️ Explain why standardization matters in model building



---

🛠️ Tech Stack

Python 3.x

Pandas

NumPy

Scikit-learn

Seaborn

Matplotlib



---

📈 Why Standardization?

Standardization rescales features to:

📉 Mean = 0

📈 Standard Deviation = 1


This is vital when:

Features have different units or scales

Using distance-based models like KNN, SVM, or Logistic Regression

Improving model convergence and performance
