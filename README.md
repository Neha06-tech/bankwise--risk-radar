# 🏦 Risk Radar: Banking Sector Risk Analysis Dashboard

An interactive **Power BI dashboard** designed to help banks and financial institutions **analyze client risk** and make smarter, data-driven **loan approval decisions**.

---

## 🎯 Objective

To identify and minimize **lending risks** using client demographic, financial, and behavioral data. This project empowers loan officers and analysts with real-time insights into client segmentation, risk scoring, and trend forecasting.

---

## 📌 Problem Statement

Financial institutions often face heavy losses due to loan defaults. This dashboard helps:

- **Predict loan repayment likelihood**
- **Categorize clients** into Low/Medium/High risk
- **Guide approval decisions**
- **Improve portfolio risk management**

---

## ✅ Key Features

### 🔍 Risk Analytics
- **Client Risk Categorization**: Pie chart view of Low, Medium, and High-risk clients
- **Loan vs. Income Band**: Average loan amount per income category (bar chart)
- **Correlation Heatmap**: Relationships between key numerical variables (income, age, credit score, etc.)
- **Client Acquisition Trend**: Track client growth over time and lending trends
- **Property vs. Loan Amount**: Scatter chart comparing properties owned and loan size

### 🧠 Interactive Filters
- Nationality  
- Gender  
- Occupation  
- Loyalty Tier  
- Fee Structure  
- Period of Joining  

---

## 📊 Dashboard KPIs

| Metric              | Value         |
|---------------------|---------------|
| **Total Clients**   | 5,247         |
| **Total Loans**     | $2.8B         |
| **Total Deposits**  | $4.2B         |
| **Total Fees**      | $125M         |
| **Risk Split**      | 50% Low, 30% Medium, 20% High |
| **Overall Risk Score** | 2.8 / 10   |

---

## 🗂️ Dataset Overview

This dashboard uses **multiple interlinked tables**:

### Primary Table
- `Banking.csv`: Contains client profiles, income, loans, deposits, account balances, and risk weights

### Supporting Tables
- `Gender.csv` – Gender definitions (`GenderId`)
- `BR.csv` – Banking Relationship types (`BRId`)
- `IA.csv` – Investment Advisor mapping (`IAId`)
- `ClientBankingLinks.csv` – Many-to-many client-banking mapping
- `Period.csv` – Time data for trend visualizations

---

## 🛠 Tech Stack

- **Tool Used**: Power BI  
- **Data Source**: CSV files (pre-cleaned and normalized)  
- **Visualization Techniques**:
  - Pie, Bar, Line, and Scatter charts
  - Slicers and dynamic filtering
  - Conditional formatting for risk flags
  - DAX for custom metrics and calculations  

---

## 👤 Target Audience

- **Loan Officers**
- **Risk Managers**
- **Credit Analysts**
- **Portfolio Managers**

This dashboard enables quick evaluation of loan applications and overall client health, helping institutions reduce default risk and improve lending efficiency.

---

## 📈 Future Enhancements

- Live database/API integration for real-time analytics  
- Predictive modeling using ML (integration with Python/R)  
- Role-based access control (manager vs analyst views)  
- Export options for report generation  
- Integration with CRM or ERP platforms  

---

## 🚀 How to Use

1. Open the Power BI `.pbix` file  
2. Click **Refresh** to load the latest data  
3. Use the sidebar filters to segment the client base  
4. Explore each visualization to assess risk levels and correlations  

---

## 📝 License

This project is open-source under the **MIT License**. Feel free to use, modify, or build upon it with credit.

---

## 🤝 Contributing

1. Fork this repo  
2. Create a new branch (`feature/risk-visualization`)  
3. Commit your changes  
4. Open a pull request – we'd love your contributions!

---

## 📬 Support

Need help or have questions? [Open an issue](https://github.com/Neha06-tech/bankwise--risk-radar/issues)

