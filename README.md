# **CryptoClustering: Unsupervised Learning for Cryptocurrencies**

## **Project Overview**
This project applies **K-Means Clustering** and **Principal Component Analysis (PCA)** to analyze whether cryptocurrencies are influenced by **24-hour and 7-day price changes**. Using unsupervised learning, we aim to identify patterns and optimize clustering through dimensionality reduction.

## **Key Steps**
### **1. Data Preprocessing**
- Load `crypto_market_data.csv` into a DataFrame.
- Normalize the data using `StandardScaler()`.
- Perform exploratory data analysis (EDA) to understand distributions.

### **2. Finding the Optimal k**
- Use the **elbow method** to determine the best number of clusters.
- Visualize the elbow curve for selection.

### **3. K-Means Clustering**
- Train the K-Means model with the optimal *k*.
- Assign clusters to each cryptocurrency based on price change percentages.
- Visualize clusters using **hvPlot**.

### **4. Dimensionality Reduction with PCA**
- Reduce features to **three principal components**.
- Analyze the explained variance for each component.

### **5. Optimized Clustering with PCA**
- Perform clustering again on the reduced dataset.
- Compare results with the original clustering.
- Visualize PCA clusters.

## **Technologies Used**
- **Python** (pandas, NumPy, scikit-learn, hvPlot)
- **Jupyter Notebook** for analysis and visualization

## **Installation & Usage**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/CryptoClustering.git
   cd CryptoClustering
