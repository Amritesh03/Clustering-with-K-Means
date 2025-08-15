# K-Means Clustering – Customer Segmentation

## 📌 Objective
The goal of this project is to perform **unsupervised learning** using the **K-Means clustering algorithm** to segment customers based on their purchasing behavior.

---

## 📂 Dataset
**Name:** Mall Customers Dataset  
**Source:** [Kaggle - Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)  
**Description:** The dataset contains customer details including `Annual Income` and `Spending Score` which will be used for clustering.

---

## 🛠 Tools & Libraries
- **Python**
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Steps Performed
1. **Data Loading & Exploration**
   - Loaded dataset using Pandas.
   - Checked for missing values and dataset statistics.

2. **Data Preprocessing**
   - Selected `Annual Income (k$)` and `Spending Score (1-100)` features.
   - Scaled data using `StandardScaler` for better clustering performance.

3. **Finding Optimal K (Elbow Method)**
   - Plotted inertia values for `k = 1 to 10`.
   - Selected the optimal K based on the “elbow” point in the curve.

4. **Model Training**
   - Applied K-Means clustering with the chosen number of clusters.
   - Assigned cluster labels to each customer.

5. **Evaluation**
   - Used **Silhouette Score** to evaluate cluster quality.

6. **Visualization**
   - Plotted customer segments with different colors for each cluster.

---

## 📈 Results
- **Optimal Clusters:** *Determined using Elbow Method.*
- **Silhouette Score:** Indicates good separation between clusters.
