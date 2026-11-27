# Customer Segmentation Analysis | OIBSIP Task 2

## Project Overview
This project focuses on Customer Segmentation Analysis using Python, RFM (Recency, Frequency, Monetary) analysis and K-Means clustering.

The objective is to identify different customer groups based on their purchasing behaviour and provide business recommendations for customer retention, loyalty and targeted marketing.

## Internship Details
- **Organization:** Oasis Infobyte
- **Track:** Data Analytics
- **Task:** Task 2 – Customer Segmentation Analysis
- **Project Type:** Exploratory Data Analysis and Machine Learning

## Objectives
- Understand customer purchasing behaviour.
- Calculate Recency, Frequency and Monetary values.
- Identify customer groups using K-Means clustering.
- Visualize customer clusters.
- Develop business recommendations based on customer segments.

## Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Excel

## Dataset
The project uses the Online Retail transaction dataset.

The dataset contains customer IDs, invoice details, transaction dates, product information, quantities and prices.

The original transaction data was cleaned and transformed into customer-level RFM metrics.

## Project Workflow

### 1. Data Collection and Inspection
- Loaded the Online Retail dataset.
- Examined dataset dimensions and data types.
- Checked missing values and duplicate records.

### 2. Data Cleaning
- Removed duplicate records.
- Handled missing Customer IDs.
- Removed invalid transactions.
- Excluded cancelled invoices.
- Converted date and customer ID columns.
- Calculated transaction revenue.

### 3. RFM Analysis
Calculated:
- **Recency:** Days since the customer's latest purchase.
- **Frequency:** Number of unique transactions.
- **Monetary:** Total customer spending.

Additional metrics included Average Purchase Value and Customer Lifetime Value proxy.

### 4. Customer Segmentation
- Standardized RFM features using StandardScaler.
- Applied K-Means clustering.
- Used the Elbow Method to examine cluster selection.
- Evaluated clustering using the Silhouette Score.

### 5. Data Visualization
- Customer Recency Distribution
- Purchase Frequency Distribution
- Customer Monetary Distribution
- Elbow Method
- Customer Cluster Scatter Plots
- Customer Distribution by Cluster

## Key Results

| Metric | Result |
|---|---:|
| Cleaned transactions | 392,692 |
| Unique customers | 4,338 |
| Unique invoices | 18,532 |
| Total revenue | £8,887,208.89 |
| Average transaction value | £22.63 |
| Number of clusters | 4 |
| Silhouette Score | 0.6162 |

### Customer Segmentation Results

The current segmentation code assigns customers to two final business segments:

- Potential Customers: 4,121
- Loyal Customers: 217

The four K-Means clusters are retained in the results dataset.

## Business Recommendations
1. Offer exclusive rewards to high-value customers.
2. Develop loyalty programs for frequent purchasers.
3. Create re-engagement campaigns for inactive customers.
4. Provide personalized offers to potential customers.
5. Monitor customer purchasing behaviour regularly.

## Project Files
- Python notebook containing the complete analysis.
- Customer segmentation results CSV.
- Screenshots of analysis and visualizations.
- Output reports and charts.

## Conclusion
This project demonstrates how RFM analysis and K-Means clustering can be used to understand customer purchasing patterns.

The resulting customer groups can help businesses improve customer retention, develop targeted marketing strategies and make data-driven business decisions.

## Author
**T.A. Kiruba Raam Kumar**

Data Analytics Intern | Oasis Infobyte
