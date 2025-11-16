 ### <img width="758" height="458" alt="image" src="https://github.com/user-attachments/assets/7e909856-f705-4dd9-984d-07711d5ec4e2" />

 
# METROBANK CASESTUDY
This project focuses on helping MetroBank, a leading financial institution, uncover insights about its customers, branches, transactions, and service experience through data.
With growing competition and an increasing number of customer complaints, the management wanted to understand what drives performance across different segments, and identify areas that require strategic improvement.
That’s where I came in as the data analyst, tasked with cleaning, analyzing, and visualizing the bank’s data to build an interactive Excel dashboard that tells the complete story behind its operations and customer experience.

---

## 🎯 Project Overview

The goal of this project is to transform raw banking data into a **visually interactive dashboard** that helps business stakeholders:

- Understand customer demographics and segmentation  
- Track account balances, product distribution, and credit exposure  
- Explore transaction trends and spending behavior  
- Monitor branch efficiency and operational performance  
- Evaluate customer complaints and fraud cases for service improvement  

---
## 📁 What This Repository Includes

## 📂 Data Files  

**Raw Data (Uncleaned):**  
- Customer data  
- Accounts data
- transaction data   
- Branch performance data  
- Complaint and fraud report data  

## 📸 Dashboard Screenshots  

- High-quality visuals of the interactive Excel dashboard  
- Showcases dynamic filters, KPIs, and analytical summaries across key areas  

## 📊 Final Excel Dashboard File (.xlsx)  

- Contains the **interactive Excel dashboard** with connected data models and slicers  
- Includes KPIs, trend charts, and automated calculations for performance tracking  
- Fully interactive and optimized for presentation or decision-making use  

---

## 🧾 Insights & Recommendations  

- Comprehensive findings derived from the dashboard analysis  
- Includes customer profiling, account performance, transaction trends, branch profitability, and customer experience insights  
- Strategic recommendations clearly detailed in this README to support actionable decisions

---

## 🧩 Tools & Techniques

**Microsoft Excel | Power Query | Pivot Tables | Slicers | Charts | Conditional Formatting | Interactive Design**

---

## 🧠 Dashboard Highlights

- Dynamic slicers for **Region, Gender and Date**
- KPI cards summarizing **Revenue, Total Accounts, and Average Balances**
- Interactive visuals for **Transaction Type, Channel Preference, and Complaint Trends**
- Automated calculations for **Resolution Time, Service Efficiency, and Fraud Exposure**
- Clean, dashboard-style layout optimized for **business presentation**

---

## 📈 Key Insights

- **Customer Overview:** MetroBank serves a balanced customer base (51% female, 49% male) with an average age of 46 and an average tenure of 5 years. Most customers fall within the *Retail segment*, which, although smaller in average income, represents the largest customer count.
<img width="758" height="458" alt="image" src="https://github.com/user-attachments/assets/04e5678c-5423-4e44-9e69-697589bd5705" />



- **Income & Loyalty:** Customers with *Premium* and *High-income* tiers make up a significant share of total revenue. A majority of clients are “Established” or “Loyal,” indicating strong retention and trust in the bank’s services.  

- **Account & Credit Profile:** Checking and savings accounts dominate the product portfolio, accounting for nearly 70% of total accounts. The overall credit score averages around **580**, and loan approvals are typically tied to higher credit scores.  

- **Transaction Behavior:** A total of **5,000 transactions** valued at **$25.07M** were recorded, with an average transaction amount of **$5,010**. Activity is evenly distributed across channels (POS, Online, Branch, ATM), but *POS and Online* lead in both transaction volume and value, reflecting the growth of digital banking.  

- **Merchant Activity:** Major merchants such as *Airbnb, Apple, and Target* dominate customer spending, accounting for the highest transaction values. Credit card customers show a stronger presence in “Payment” transactions compared to non-credit users.  

- **Branch Performance:** MetroBank operates **20 branches** with a total revenue of **$59.4M** and a profit margin of **64%**. *Branch 12* is the top performer by profit, while *Branch 1* and *Branch 17* currently operate at a loss, suggesting room for operational optimization.
<img width="872" height="503" alt="image" src="https://github.com/user-attachments/assets/1e885492-1afd-4dec-b0bc-5d561ef9c660" />



- **Customer Experience & Risk:** MetroBank recorded **800 total complaints**, of which **59% were resolved** and **41% remain unresolved**, with an **average resolution time of 30 days**. The most common issues were **Charges Dispute (23%)**, **Fraud (18%)**, and **Service Delay (20%)**. Although fraud does not dominate total complaints, it remains a critical risk area — with around **38% of fraud cases still open or in progress**. Non-credit card customers reported more service delays and fraud issues, while **high-value customers** lodged the highest number of complaints, indicating a potential **retention risk** that requires focused attention.  


---

## 💡 Recommendations

### 1) Digital & Channel Strategy
- **Prioritize digital experience** (POS/Online): improve uptime monitoring, optimize authentication, and streamline checkout/payment flows.  
- **Action:** Run a monthly funnel review for Online/POS failure points.  
- **KPI Targets (90 days):** +10–15% increase in successful online transactions; <0.5% failed-payment rate.

### 2) Disputes & Merchant Management
- **Reduce “Charges Dispute” (23%)** through clearer descriptors and merchant integrations.  
- **Actions:**  
  - Enforce standardized merchant naming; build rules to auto-flag duplicate charges.  
  - Enable self-service dispute initiation with required evidence templates.  
- **KPIs:** 20% reduction in dispute volume; 25% faster dispute cycle time.

### 3) Fraud Risk & Resolution
- **Shrink open fraud backlog** (~38% of fraud cases unresolved).  
- **Actions:**  
  - Triage SLA: P1 fraud within **48h**, P2 within **7 days**; auto-escalation after breach.  
  - Implement anomaly rules (unusual merchant, atypical location/time/amount).  
- **KPIs:** Reduce unresolved fraud rate to **<15%**; cut average fraud resolution time to **≤14 days**.

### 4) High-Value Customer Retention
- **Dedicated care path** for high-value customers (who report the most issues).  
- **Actions:**  
  - Priority queue for complaints, direct RM contact, and proactive callbacks post-resolution.  
  - Quarterly “service health” reviews for top-value cohorts.  
- **KPIs:** 30% reduction in complaints per high-value customer; churn in this segment **<1%/qtr**.

### 5) Branch Optimization
- **Address loss-making branches (BR001, BR017).**  
- **Actions:** adjust staffing to revenue per staff benchmarks; shift low-value transactions to digital; pilot shared-service staffing between nearby branches.  
- **KPIs:** Bring both branches to break-even in **2 quarters**; +15% Revenue/Staff in underperformers.

### 6) Product Depth & Cross-Sell
- **Grow multi-product relationships** (e.g., Checking + Savings + Card).  
- **Actions:** targeted offers for Millennials and high-balance cohorts; financial-literacy mini series for new/low-income customers.  
- **KPIs:** +25–30% increase in multi-product customers; +10% lift in savings balances.

### 7) Complaint Management Efficiency
- **Reduce overall resolution time (30 days).**  
- **Actions:**  
  - Unified intake form with category auto-tagging (Fraud/Service/Technical/Dispute).  
  - Weekly backlog review by owning department; SLA dashboard with red/amber/green flags.  
- **KPIs:** Resolution rate **≥80%**; average time to resolve **≤14–21 days**; backlog down **30%** in 60 days.


---

## 🏁 Outcome

This project showcases the end-to-end process of building an **interactive Excel dashboard**, from raw data transformation to insight communication.  
It reflects the ability to apply design thinking, analytical reasoning, and business understanding to solve real-world data problems.

---

## 📂 Data Source  

The datasets used in this project were provided by ** FREEDOM OBOH ** as part of a practical assignment under the **Let's Talk Excel Program**.  
They include realistic banking data covering customers, accounts, transactions, branches, and complaints.  

All cleaning, analysis, and visualizations were performed independently using **Microsoft Excel** for educational and project-based learning purposes.

---
## 👩‍💼 About the Analyst  

Prepared by **Dorcas Akinnibosun** — *Data Analyst*

Focused on turning data into clear, actionable insights to support better decision-making.
