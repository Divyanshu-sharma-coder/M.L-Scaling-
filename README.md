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


#  Normalisation 
📐 Feature Normalization Explained (L1, L2, Min-Max)

This section explains different normalization techniques used in Machine Learning and why they are crucial, especially when working with models sensitive to feature magnitudes or sparse data.


---

🔧 1. Min-Max Normalization

x' = \frac{x - x_{\min}}{x_{\max} - x_{\min}}

Scales values to a fixed range, usually [0, 1]

Useful when minimum and maximum values are known

Sensitive to outliers


> 🧠 Best for: Image data (pixel values), sensor data




---

🔧 2. L1 Normalization

x' = \frac{x}{\|x\|_1}, \quad \text{where} \quad \|x\|_1 = \sum |x_i|

Scales the vector so that the sum of absolute values = 1

Maintains sparsity (good for high-dimensional sparse data)


> 🧠 Best for: Text features (e.g., Bag-of-Words, TF-IDF)




---

🔧 3. L2 Normalization

x' = \frac{x}{\|x\|_2}, \quad \text{where} \quad \|x\|_2 = \sqrt{\sum x_i^2}

Scales vector to unit length

Important when using distance-based models (e.g., cosine similarity, KNN)


> 🧠 Best for: Word embeddings, similarity calculations




---

💡 Why Normalize?

💥 Prevent features with large ranges from dominating the model

🧠 Helps gradient-based models converge faster

🚀 Improves model accuracy, training speed, and stability
