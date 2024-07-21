# CryptoClustering

## Project Overview

This project focuses on clustering cryptocurrencies based on their price change percentages over various time periods using K-Means clustering. The goal is to identify patterns and group similar cryptocurrencies together. Principal Component Analysis (PCA) is also used to enhance the clustering process by reducing dimensionality.

## Dataset

The dataset used for this analysis is a CSV file named `crypto_market_data.csv`, located in the `Resources` directory.

## Prerequisites

Make sure you have the following libraries installed:

- **Pandas**
- **Hvplot**
- **Scikit-learn**
- **Warnings**

## Conclusion

Applying PCA for dimensionality reduction resulted in more compact clusters, indicating that a reduced set of features can effectively represent the data for clustering. This approach simplifies the model while retaining essential information.
