# PRODIGY_ML_02
Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.

# 🧠 Task-02: Customer Segmentation using K-Means Clustering

This repository contains the implementation of a **K-Means Clustering model** to group customers of a retail store based on their **Age**, **Annual Income**, and **Spending Score**.  
The project helps identify distinct customer segments to enable targeted marketing strategies and better business decisions.

---

## 📌 Objective
- Apply **K-Means Clustering** to segment customers into distinct groups.  
- Analyze **customer behavior patterns** using their spending and income.  
- Visualize clusters to understand customer segmentation clearly.

---

## 📂 Dataset
The dataset used for this task is from Kaggle:  
**[Customer Segmentation Tutorial in Python](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)**  

**File Used:** `Mall_Customers.csv`

**Features Used:**
- `Age`
- `Annual Income (k$)`
- `Spending Score (1–100)`

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**

---

## 🚀 Steps Involved
1. Import and explore the dataset  
2. Perform data preprocessing and feature selection  
3. Use the **Elbow Method** to find the optimal number of clusters  
4. Apply **K-Means Clustering algorithm**  
5. Visualize the clusters using 2D and 3D plots  
6. Analyze and interpret each customer segment  

---

## 📊 Results
- The optimal number of clusters determined: **5**  
- Customers were successfully grouped into five meaningful segments:
  - 🏆 **Premium Customers** — High income, high spending  
  - 💰 **Budget Customers** — Low income, low spending  
  - 👥 **Average Customers** — Medium income, medium spending  
  - 🧓 **Conservative Spenders** — High income, low spending  
  - ⚡ **Impulsive Buyers** — Low income, high spending  

- Visualizations clearly show the separation between customer groups.  
- The model helps businesses tailor marketing strategies for each group.

---

## 📜 License
This project is created as part of the **Prodigy Infotech Machine Learning Internship**.

---

## 👩‍💻 Author
**Manshi Singh**  
🎓 B.Tech in Computer Science and Engineering (AI & ML Specialization)  
💼  Machine Learning Intern @ Prodigy Infotech  

---

⭐ *If you found this project helpful, don’t forget to star this repository!*
