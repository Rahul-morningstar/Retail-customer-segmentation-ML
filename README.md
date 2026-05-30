# Retail Customer Segmentation using K-Means Clustering

## Project Overview
An end-to-end unsupervised machine learning project that segments
customers of a UK-based online retailer into distinct groups using
RFM (Recency, Frequency, Monetary) Analysis and K-Means Clustering.

## Problem Statement
Identify meaningful customer segments from transactional data to
enable personalised marketing strategies and improve customer retention.

## Dataset
- **Source:** UCI Machine Learning Repository — Online Retail Dataset
- **Size:** ~541,909 transactions | Dec 2010 – Dec 2011
- **Features:** InvoiceNo, StockCode, Quantity, InvoiceDate,
  UnitPrice, CustomerID, Country

## Tech Stack
- Python 3.10
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (KMeans, StandardScaler, PCA, silhouette_score)
- Google Colab

## Project Steps
1. Problem Statement Definition
2. Data Collection
3. Data Preprocessing (missing values, cancellations, outliers)
4. Exploratory Data Analysis (EDA)
5. Feature Engineering — RFM Analysis
6. K-Means Clustering (Elbow + Silhouette method)
7. Cluster Interpretation & Segment Naming
8. Marketing Recommendations

## Customer Segments Identified
| Segment | Profile |
|---|---|
| Champions | Recent, frequent, high spenders |
| Loyal Customers | Regular buyers with decent spend |
| At-Risk Customers | Previously active, now dormant |
| New/Occasional Buyers | Recent but infrequent buyers |

## Results
- Optimal clusters: k = 4
- Evaluation: Silhouette Score > 0.35

## How to Run
1. Open the `.ipynb` file in Google Colab
2. Run all cells (Runtime > Run All)
3. Dataset loads automatically from UCI URL

## Author
Your Name — **https://www.linkedin.com/in/rahul-kumar-726154186/**
