
# 🛍️ Customer Segmentation using KMeans Clustering

This project applies **unsupervised machine learning** to segment mall customers based on their behavior and demographics using the **KMeans clustering algorithm**.

It helps businesses identify different customer personas for personalized marketing strategies.

---

## 📊 Dataset

- **Name**: Mall Customer Segmentation Data
- **Source**: [GitHub - Tirthajyoti/Machine-Learning-with-Python](https://github.com/tirthajyoti/Machine-Learning-with-Python)
- **Direct Link**: [CSV File](https://raw.githubusercontent.com/tirthajyoti/Machine-Learning-with-Python/master/Datasets/Mall_Customers.csv)
- **Features**:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🧠 Problem Statement

To understand customer behavior and group similar customers together using clustering. This helps in:

- Personalized marketing
- Product recommendation strategies
- Business decision making

---

## 🚀 Project Pipeline

1. **Data Collection**
   - Loaded dataset directly from GitHub using `pandas.read_csv()`.

2. **Exploratory Data Analysis (EDA)**
   - Gender distribution
   - Age, income, and spending score distributions
   - Income vs. spending score visualizations

3. **Data Preprocessing**
   - Categorical to numeric conversion (Gender)
   - Feature scaling using `StandardScaler`

4. **Model Building**
   - Elbow Method to determine the optimal number of clusters
   - Applied `KMeans` clustering

5. **Evaluation**
   - Used `silhouette score` for model evaluation
   - Cluster visualization using `seaborn` scatter plots

---

## 📈 Results

| Metric             | Value               |
|--------------------|---------------------|
| Optimal Clusters   | 5                   |
| Evaluation Metric  | Silhouette Score ~0.27191023466188324 |
| Outcome            | Identified 5 distinct customer segments |

---

## 🛠️ Tech Stack

- Python
- Google Colab
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

**License & Dataset Usage**
This project is for educational purposes only.
