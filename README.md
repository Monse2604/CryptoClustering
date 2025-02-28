CryptoClustering: Unsupervised Learning for Cryptocurrencies
Project Overview
This project applies K-Means Clustering and Principal Component Analysis (PCA) to analyze whether cryptocurrencies are influenced by 24-hour and 7-day price changes. Using unsupervised learning, we aim to identify patterns and optimize clustering through dimensionality reduction.

Key Steps
Data Preprocessing: Load crypto_market_data.csv, normalize data with StandardScaler(), and explore key statistics.
Finding Optimal k: Use the elbow method to determine the best number of clusters.
K-Means Clustering: Train and visualize clusters based on price change percentages.
Dimensionality Reduction with PCA: Reduce features to three principal components and analyze explained variance.
Optimized Clustering with PCA: Perform clustering again on the reduced dataset and compare results.
Visualization: Use hvPlot for interactive scatter plots of clusters.
Technologies Used
Python (pandas, NumPy, scikit-learn, hvPlot)
Jupyter Notebook for analysis and visualization
Usage
Clone the repository:
bash
Copiar
Editar
git clone https://github.com/your-username/CryptoClustering.git
cd CryptoClustering
Install dependencies:
bash
Copiar
Editar
pip install -r requirements.txt
Run Crypto_Clustering.ipynb in Jupyter Notebook.# CryptoClustering
This is the homework for the challenge 
