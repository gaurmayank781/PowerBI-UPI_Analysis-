# UPI Transaction Analysis Dashboard

## Overview
This project presents an in-depth analysis of UPI transactions using an interactive dashboard. The dashboard provides insights into transaction trends, success and failure rates, transaction categories, distribution of amounts, and monthly patterns. It is designed to help businesses and financial analysts make data-driven decisions based on digital payment trends.

## Features
- **Total Transaction Analysis**: Displays total amount, success, and failure rates.
- **Bank-wise Analysis**: Allows filtering by sender and receiver banks.
- **Transaction Categories**: Breakdown of transactions into travel, shopping, bill payments, food, and others.
- **Amount Distribution**: Categorizes transactions into small, medium, and large amounts.
- **Monthly Trends**: Tracks transaction volume across months.
- **Geospatial Insights**: Displays transaction hotspots on a map.

## Key Questions & Insights
### 1. What is the total transaction volume and success rate?
- **Total Amount Processed:** 19.87M
- **Total Transactions:** 20,000
- **Successful Transactions:** 16,000 (80%)
- **Failed Transactions:** 4,000 (20%)

### 2. What are the major transaction categories?
- **Top Categories by Amount:**
  - Travel: 4.0M
  - Shopping: 4.0M
  - Others: 4.0M
  - Bill Payment: 3.9M
  - Food: 3.9M

### 3. How is the transaction amount distributed?
- **Small Transactions:** 25.11%
- **Medium Transactions:** 25.65%
- **Large Transactions:** 49.25%

### 4. How do transactions vary by month?
- **Peak Months:** February (1.69M), October (1.69M)
- **Lowest Activity Month:** June (653K)
- **Overall Trend:** Fluctuating with peaks in early and late months.

### 5. How are transactions distributed geographically?
- **High Activity Regions:** Major cities like Mumbai, Delhi, and Bangalore.
- **Low Activity Regions:** Rural areas with fewer transactions.

## Technologies Used
- **Data Visualization**: Power BI
- **Database**: MySQL
- **Programming**: Python (Pandas, Matplotlib, Seaborn)
- **Dashboard Deployment**: Power BI Service

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/gaurmayank781/PowerBI(UPI_Analysis).git
   ```
2. Open the Power BI dashboard file (`upi_dashboard.pbix`).
3. Connect to your database and update the queries as needed.
4. Explore the interactive dashboard.

## Future Improvements
- Integrate live UPI transaction data using APIs.
- Enhance predictive analytics for fraud detection.
- Add customer segmentation analysis for targeted insights.

## Dashboard
![Screenshot 2025-04-03 at 6 43 58 PM](https://github.com/user-attachments/assets/3a0af86c-ccf8-4981-8f54-77e3443ccb03)

## Contributors
- **Mayank Gour** - Data Analyst

For any questions or suggestions, feel free to open an issue or reach out!

