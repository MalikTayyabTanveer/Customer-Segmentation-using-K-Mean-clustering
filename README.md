# Customer Segmentation Using K-Means Clustering

## Project Overview
This project focuses on segmenting customers based on their purchasing behavior using K-Means clustering. By analyzing features such as purchase frequency and monetary value, we aim to identify distinct customer groups, allowing businesses to tailor their marketing strategies and improve customer engagement and retention.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [K-Means Clustering](#k-means-clustering)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributors](#contributors)
- [License](#license)

## Introduction
Customer segmentation is a powerful tool for businesses to better understand their customer base and optimize their marketing efforts. In this project, we used K-Means clustering to segment customers, providing insights into different purchasing behaviors and helping businesses target their strategies effectively.

## Dataset
The dataset used in this project includes the following columns:
- `InvoiceNo`: Invoice number
- `StockCode`: Product code
- `Description`: Product description
- `Quantity`: Quantity of each product
- `InvoiceDate`: Date of invoice
- `UnitPrice`: Price per unit of product
- `CustomerID`: Unique identifier for each customer
- `Country`: Country of the customer

## Exploratory Data Analysis (EDA)
EDA was performed to understand the dataset and extract insights on:
- Purchase frequency
- Monetary value of purchases
- Product preferences

Visualizations and statistical analysis were used to uncover patterns and relationships within the data.

## K-Means Clustering
K-Means clustering was employed to group customers based on their purchase frequency and monetary value. The key steps involved:
- Data normalization using `StandardScaler`
- Determining the optimal number of clusters using the Elbow Method
- Applying K-Means clustering to the dataset
- Visualizing the customer segments

## Results
The clustering analysis revealed three distinct customer segments:
1. **Cluster 0**: Low purchase frequency and low monetary value
2. **Cluster 1**: High purchase frequency and medium monetary value
3. **Cluster 2**: High monetary value with varying purchase frequency

These segments provide valuable insights for targeted marketing and resource allocation.

## Conclusion
This project demonstrates the effectiveness of K-Means clustering in customer segmentation, offering businesses a data-driven approach to better understand their customers and tailor their strategies accordingly. The insights gained can lead to improved customer satisfaction, higher retention rates, and increased revenue.

## Contributors
- **[Tayyab Tanveer](https://www.linkedin.com/in/tayyab-tanveer-b000282b3)** - Lead Developer
- **[Fatima](https://www.linkedin.com/in/fatima-shafiq-3945601b1)** - Contributor

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
