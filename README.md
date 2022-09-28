# Cryptocurrencies


Using unsupervised machine learning to classify a portfolio of currently tradable cryptocurrencies

---

## Resources
- [crypto_data.csv](https://github.com/lnshewmo/Cryptocurrencies/blob/main/Resources/crypto_data.csv)
- Jupyter Notebook
- Libraries: pandas, numpy, hvplot, plotly, sklearn

## Overview

1 - The `crypto_data.csv` dataset was cleaned and preprocessed in order to perform PCA (Principal Component Analysis).

2 - The resulting dataframe was reduced to 3 dimensions using PCA.

![pca](https://github.com/lnshewmo/Cryptocurrencies/blob/main/Resources/PCA.png)

3 - K-Means analysis was performed using the PCA data to determine the number of clusters (4) and create a prediction model.

![elbow](https://github.com/lnshewmo/Cryptocurrencies/blob/main/Resources/elbow.png)

4 - Visualizations were created to show:
  
  - K-means clustering in 3D
  
  ![3D](https://github.com/lnshewmo/Cryptocurrencies/blob/main/Resources/3d_clusters.png)
  
  - a table sortable by feature

  ![hvtable](https://github.com/lnshewmo/Cryptocurrencies/blob/main/Resources/hv_table.png)
  
  - a scatterplot of coin supply vs coins mined

  ![2D](https://github.com/lnshewmo/Cryptocurrencies/blob/main/Resources/2d_clusters.png)






