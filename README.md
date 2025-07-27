### 🛍️ Customer Segmentation with KMeans Clustering

This repository features a Jupyter notebook that applies the KMeans clustering algorithm to segment mall customers. The primary aim is to discover distinct customer groups by analyzing their demographics and spending behavior.

#### 📌 Project Objective:
Cluster customers into similar groups to enable personalized marketing strategies, using the following attributes:

- 🎂 **Age**  
- 💸 **Annual Income (k$)**  
- 💳 **Spending Score (1–100)**

---

### 🔧 Features

🔹 **Data cleaning and preprocessing**  
🔹 **Label encoding for categorical values**  
🔹 **Feature selection and engineering**  
🔹 **Elbow method to find optimal clusters**  
🔹 **KMeans clustering and analysis**  

---

#### 🔍 Multiple Visualizations Included:
- 📉 **Elbow Method Plot**  
- 📊 **2D & 3D Cluster Visualizations**  
- 🔥 **Heatmap**  
- 🎯 **Gender & Age distribution across clusters**  
- 🔄 **Pairwise Feature Relationships**

---

### 🛠️ Workflow

🔧 Data Preprocessing  
- Renamed columns for clarity  
- Encoded Gender to numeric  
- Handled missing values (if any)  

 🧮 Clustering Preparation  
- Selected features: **Age**, **Annual Income**, **Spending Score**  
- Scaled values *(optional)*  
- Determined optimal **K** using the **Elbow Method**  

🤖 Model Training  
- Applied `KMeans(n_clusters=5)`  
- Assigned cluster labels to the dataset  

 📊 Evaluation  
- No external accuracy/loss metrics *(unsupervised learning)*  
- Evaluated clusters using visualizations and group statistics  

---

### 🧠 Methodolog
🧹 Data Preprocessing & Cleaning  
- Handled missing values  
- Standardized column names for consistency  

🔢 Label Encoding  
- Converted categorical variables like **Gender** into numerical format  

 🎯 Feature Selection  
- Chose key features: **Age**, **Annual Income**, and **Spending Score**  

 🔍 Elbow Method  
- Used the **Elbow Curve** to determine the optimal number of clusters (**K**)  

 🔄 KMeans Clustering  
- Applied **KMeans** with `K=5` to segment customers into meaningful groups  

🏷️ Cluster Labeling & Analysis  
- Assigned cluster labels to the dataset  
- Visualized patterns across different customer groups  

💾 Export Results  
- Saved the final clustered dataset as `clustered_customers.csv`  

