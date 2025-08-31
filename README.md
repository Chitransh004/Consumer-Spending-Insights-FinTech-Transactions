# Consumer-Spending-Insights-FinTech-Transactions
This project contains a detailed analysis of **financial transactions for August 2025**. The goal is to clean, analyze, visualize, and generate insights from the dataset to support business decisions.

The project includes:

- Data cleaning & validation
- Revenue analysis by category, payment mode, and customers
- Advanced exploratory data analysis (EDA) and visualizations
- Summary report in PDF
- Dashboard in Excel
- Identification of unusual or high-value transactions

---

## Dataset
- **File:** `data/Fintech_Transactions_50k.csv`  
- **Size:** 50,000 rows × 15 columns  
- **Columns:**
  - TransactionID
  - Date
  - CustomerID
  - Amount
  - Category
  - PaymentMode
  - MerchantID
  - BranchID
  - Notes
  - Status
  - Location
  - DeviceID
  - Campaign
  - TaxAmount
  - DiscountAmount

---

## Steps Performed
1. **Data Cleaning**
   - Removed duplicate transactions
   - Handled missing values
   - Corrected negative amounts (except refunds)
   - Converted `Date` column to datetime

2. **Basic Analysis**
   - Calculated total revenue
   - Revenue breakdown by `Category` and `PaymentMode`
   - Identified top 10 customers, merchants, and branches

3. **Advanced EDA & Visualization**
   - Revenue distribution, log-transformed distribution
   - Daily revenue trend with 7-day moving average
   - Category vs PaymentMode revenue (stacked bar)
   - Correlation heatmap between Amount, TaxAmount, DiscountAmount
   - Top campaigns, devices, and branches
   - Refund and failed transaction analysis
   - High-value transactions (top 1%)

4. **Reporting**
   - 1-page PDF summary with key metrics, insights, recommendations
   - Excel dashboard with multiple sheets

---

## Key Insights
- **Top Revenue Category:** Clothing  
- **Top Payment Mode:** Card  
- **Top Customer:** C1466 (₹4,170.41 revenue)  
- **Refund Rate:** ~X% (calculated in notebook)  
- **High-value Transactions:** Top 1% contribute disproportionately to total revenue  
- **Daily Revenue Trend:** Peaks observed mid-month and on weekends  
- **Campaign Performance:** ‘Festive Offer’ and ‘New Launch’ most effective  

---

## How to Use
1. Open `notebooks/Fintech_Transactions_Analysis.ipynb` in Jupyter Notebook or VS Code.  
2. Run all cells to reproduce data cleaning, analysis, and visualizations.  
3. Check `outputs/` folder for cleaned dataset, charts, Excel dashboard, and PDF report.  

---

## Tools & Libraries
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Author
**Chitransh / Your Name**  
Data Analyst | Financial Data Analysis Project

