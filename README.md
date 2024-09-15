# Customer Segmentation Using Unsupervised Learning

## Overview
This project aims to segment customers based on their transactional behavior and demographics using unsupervised machine learning techniques. The goal is to identify distinct customer groups to enhance marketing strategies, increase customer loyalty, and maximize satisfaction.

## Dataset
The dataset consists of the following tables:
- **Customers**: Contains customer demographic information (gender, city).
- **Transactions**: Contains details of customer transactions, including coupon usage.
- **Genders** and **Cities**: Auxiliary tables providing descriptive names for gender and city IDs.

## Project Structure

├── Customer-Segmentation-Project/ ├── README.md # Project overview and description ├── data/ │ └── E-commerce_data.xlsx # Dataset ├── notebooks/ │ └── customer_segmentation.ipynb # Jupyter notebook with code ├── visualizations/ │ └── cluster_visualizations.png # Visualizations of clustering results └── requirements.txt # List of dependencies


## Approach
The project involves the following steps:
1. **Data Loading and Preprocessing**: Merging customer demographic and transactional data.
2. **Feature Engineering**: Creating features based on customer coupon usage and demographics.
3. **Modeling**: Using K-Means clustering to segment customers into different groups.
4. **Evaluation**: Evaluating the model using Silhouette Score and Inertia.
5. **Analysis**: Analyzing each customer segment and providing marketing recommendations.

## Key Findings
- **Segment 1**: Customers with low transaction frequency and few burnt coupons. Recommendation: Provide higher-value coupons to increase engagement.
- **Segment 2**: Customers with high engagement and frequent coupon usage. Recommendation: Offer loyalty rewards to retain these customers.

## Setup
To run this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/Customer-Segmentation-Project.git
cd Customer-Segmentation-Project
pip install -r requirements.txt
```

## Open the Jupyter notebook and run the analysis:
```bash
jupyter notebook notebooks/customer_segmentation.ipynb
```

## Dependencies
1. **pandas**
2. **scikit-learn**
3. **matplotlib**
4. **seaborn**
