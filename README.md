<p align="center">
  <img src="Retail_Customer_Transaction_and_Fraud_Pattern_Analysis_Banner.png" width="100%">
</p>

![License: Proprietary](https://img.shields.io/badge/License-Proprietary-red.svg)


# Retail Customer Transaction & Fraud Pattern Analysis

### 🔍 Business Case:
A fintech/retail company wants to analyze customer transactions to:
- Identify high-value customers 💰  
- Analyse suspicious patterns 🚨  
- Provide business teams a dashboard for actionable insights 📊

---

### 🛠️ Tools Used:
- **SQL** – Data cleaning, joins, fraud flag analysis  
- **Power BI** – KPI dashboards, top performers, fraud analytics  
- **Python (Pandas, Seaborn)** – Fraud patterns, customer & regional insights  

---

### 📂 Project Components:

| File/Folder | Description |
|-------------|-------------|
| `📁 Raw_Data/` | Original source data – `customers.csv`, `transactions.csv`, `merchants.csv` |
| `📁 Cleaned_Data/` | Final cleaned & merged file – `Customer_Transaction_Merged_Cleaned.csv` |
| `Retail_Insights_SQL_Priya_Dutta.sql` | SQL queries for EDA & fraud analysis |
| `Retail_Customer_Transaction_and_Fraud_Pattern_Analysis_SQLQueries_Priya_Dutta.txt` | SQL queries for EDA & fraud analysis in text format|
| `Retail_Insights_Fraud_Analysis.txt` | EDA insights summary from SQL analysis |
| `Retail_Fraud_Insights_Detailed.txt` | In-depth fraud analysis report |
| `Retail_Insights_Dashboard.pbix` | Final Power BI dashboard |
| `Retail_Insights_Dashboard.pdf` | Exported PDF of Power BI dashboard |
| `Retail_Fraud_Transaction_Analysis_Priya_Dutta.ipynb` | Python notebook (fraud detection & heatmap) |
| `Retail_Fraud_Transaction_Analysis_Priya_Dutta.pdf` | Exported PDF of Python notebook |
| `README.md` | Project overview, resume lines, and interview pitch |
| `LICENSE` | MIT License for open-source use |
| `Retail_Customer_Transaction_and_Fraud_Pattern_Analsis_Banner.png` | GitHub project banner (displayed in repo) |

---

📲 **Note:** PDF preview may not load on mobile. Please download to view full report.

---

### 💡 Key Features:
- Total Revenue, Orders, and Avg Transaction KPIs  
- Fraud analysis by region, payment method, city, category  
- Top 5 customers & merchants  
- Monthly sales trend 📈  
- Regional heatmaps 🔥 (Python)  
- Interactive filters for deeper insights  

---

### 🧠 SQL Analysis Summary:
- Cleaned & joined 3 datasets  
- Performed fraud count, fraud % by region, merchant type, etc.  
- Used `CASE`, `GROUP BY`, `JOIN`, and aggregation functions  
- Derived insights like top regions, categories, fraud-prone areas  

---

### 📊 Power BI Dashboard Pages:
1. **Business Overview** – Revenue, avg transaction, category insights  
2. **Top Performers** – Top customers, merchants, monthly trend  
3. **Fraud Analytics** – Region-wise fraud %, payment-type breakdown, city fraud map  

---

### 🔎 About the `IsFraud` Column

The `IsFraud` column was already present in the dataset and served as a binary label:

- `1` = Fraudulent Transaction  
- `0` = Genuine Transaction

We did not generate this label using machine learning. Instead, this project focuses on **fraud pattern analysis using SQL, Power BI, and Python** to highlight suspicious activity, high-risk regions, and fraud-prone categories.  

---

> This allows the analysis to be extended later into predictive modeling when machine learning is incorporated.

### 🐍 Python Insights:
- Used pandas to load & clean merged dataset  
- Performed fraud analysis by Region
- Top 5 cities by Revenue  
- Visualized fraud % by Region (Seaborn)  
- Heatmap: Fraudulent transactions by Region & Category 🔥  

---

### 💼 Resume Description (2–3 lines):
> **Retail Customer Transaction and Fraud Pattern Analysis** using SQL, Python, and Power BI. Built an end-to-end project to analyse fraud patterns, top customers/merchants, and visualize insights through a dynamic dashboard.

---

### 🗣️ Interview Elevator Pitch:
> “This project simulates a real-world fintech scenario. I started with SQL to clean and analyze 7500 customer transactions. Then, I used Power BI to create a professional dashboard for decision-makers. Finally, I added a Python notebook for fraud analysis and visual exploration using Seaborn and Matplotlib. The project reflects how I can combine data engineering, analytics, and visualization tools to solve real business problems.”

---

### 📌 Why This Project Stands Out:
- ✅ End-to-end ownership of analysis → dashboard → insights  
- ✅ Realistic business goals: customer value + fraud risk  
- ✅ Great for GitHub, LinkedIn, and interview presentation  

---

## 📈 Sample Insights

> Based on 7,500 transaction records from 6 regions & 6 product categories:

- **Top Revenue Region**: East (₹5.15 Cr), followed by South and North  
- **Most Fraud-Prone Region**: West (5.05% fraud rate)  
- **Top Customer**: `CUST0387` with ₹6.24 Lakhs in spending  
- **High Fraud by Category**: Beauty and Home Decor  
- **Preferred Payment Methods**: Netbanking & Wallet showed higher fraud counts  
- **Fraud Risk Heatmap**: Visualized across category and region using Python  

---

## 🧑‍💼 Author

**Priya Dutta**  
🎓 Executive Certification in Data Science with AI Specialization (IIT Guwahati via AnalytixLabs)  
🎓 MBA in Marketing & Finance  
📍 Betul, M.P. | Open to Remote Work & Relocation  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/priya-dutta-b2541b14b)

---

## 💬 Resume Project Line

Developed an end-to-end retail customer transaction and fraud pattern analysis project using SQL, Python, and Power BI. Cleaned & joined multi-source data (7,500+ records), analyzed fraud trends, and built a dashboard showing region-wise revenue, top customers, and suspicious patterns.

---

### 📄 License  
This project is proprietary and protected by copyright law.
Unauthorized copying, distribution, or reuse is strictly prohibited.
