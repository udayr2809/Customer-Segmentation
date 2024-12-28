# Customer Segmentation  

## Overview  
This project focuses on segmenting mall customers into distinct groups using clustering techniques. The goal is to help the marketing team target customers effectively by analyzing demographics (age, gender, income) and shopping behavior (spending score).  

## Problem Statement  
Identify key customer segments to enable personalized marketing strategies. Specifically, determine the most valuable customer groups based on their spending score and income levels.  

## Methodology  
- **Data Preprocessing**: Cleaned and prepared the dataset for analysis.  
- **Exploratory Data Analysis (EDA)**: Visualized patterns and relationships in the data using Python libraries.  
- **Clustering**: Applied K-Means clustering to group customers based on:  
  - Age  
  - Annual Income (k$)  
  - Spending Score (1-100)  
- **Key Insights**:  
  - **Cluster 1**: High-income, high-spending customers (60% women), ideal for premium marketing.  
  - **Cluster 2**: Moderate-income, moderate-spending customers, suited for sales events and promotions.  

## Results  
- Identified actionable customer segments to guide marketing strategies.  
- Enhanced understanding of demographic and behavioral patterns in the customer base.  

## Technologies Used  
- **Python**: Data processing, analysis, and visualization.  
- **Libraries**: Pandas, Seaborn, Matplotlib, Scikit-learn.  

## How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/mall-customer-segmentation.git
   ```
2. Install required libraries:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook and run the cells to reproduce the analysis.  

## Dataset  
The dataset contains 200 records of mall customers with the following features:  
- **CustomerID**  
- **Gender**  
- **Age**  
- **Annual Income (k$)**  
- **Spending Score (1-100)**  
