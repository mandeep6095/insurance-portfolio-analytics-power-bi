# 📊 Insurance Portfolio Analytics  – Power BI Project

_A deep-dive analytical solution for insurance portfolio performance, designed to strengthen decision-making across policy management, premium collection, sales tracking, and customer retention._

---

## 📌 Table of Contents
<a href="#overview">Overview</a>  
<a href="#dashboard-previews">Dashboard Previews</a>  
<a href="#tools--technologies">Tools & Technologies</a>  
<a href="#data-model">Data Model</a>  
<a href="#research-questions--insights">Research Questions & Insights</a>  
<a href="#key-findings">Key Findings</a>  
<a href="#results--conclusions">Results & Conclusions</a>  
<a href="#author--contact">Author & Contact</a>

---

## <a id="overview"></a>🎯 Project Overview
This Power BI project delivers end-to-end analytics for insurance companies, transforming raw policy and premium data into strategic insights through interactive dashboards and KPIs. It supports business teams in tracking policy distribution, revenue trends, sales performance, underwriting efficiency, and loan utilization.

---

## <a id="dashboard-previews"></a>📌 Dashboard Previews

### 🔹 Executive Dashboard
High-level KPIs — total policies, active policies, lapse rate, premium collection, average policy size, growth trends, and top-performing states/agents.

### 🔹 Policy Portfolio Dashboard
Policy tenure distribution, geographic coverage, policy types, and region-wise segmentation.

### 🔹 Premium & Revenue Dashboard
Premium trends over time, payment frequency behavior, maturity amounts, and quarterly liabilities forecast.

### 🔹 Sales Performance Dashboard
Sales hierarchy analytics — zonal → regional → agent level, with premium growth and customer acquisition trends.

### 🔹 Loan & Underwriting Dashboard
Loan-eligible policies, available loan amounts, underwriting expenses, and expense-ratio analysis.

### 🔹 Policy Performance Dashboard
Deep insights into sum assured distribution, protection plan comparison, and lapse rate drivers.

---

## <a id="tools--technologies"></a>🛠️ Tools & Technologies
| Category | Tool |
|---------|------|
| Dashboard Development | Power BI Desktop |
| Calculations | DAX |
| Data Transformation | Power Query |
| Data Modeling | Star Schema with Fact & Dimension Tables |

---

## <a id="data-model"></a>📂 Data Model
The analytics solution is powered by a structured star-schema model:

| Table Type | Table Name | Description |
|-----------|-------------|-------------|
| Fact | **FCT Insurance_Policy_Table** | Policy transactions |
| Dimension | **DM Customer_Detail_Table** | Customer master |
| Dimension | **DM Policy_Type** | Policy master |
| Dimension | **DM Policy_Protection_Plan** | Protection plan master |
| Dimension | **Date** | Time intelligence |
| Dimension | **DM Insurance_Agent_Table** | Agent master |
| Dimension | **DM Regional_Manager** | Regional hierarchy |
| Dimension | **DM Zonal_Manager** | Zonal hierarchy |
| Dimension | **Region** | State/region mapping |

---

## <a id="research-questions--insights"></a>🔍 Research Questions & Insights

| Business Focus | Key Questions |
|----------------|--------------|
| Retention & Lapse Rates | What drives policy lapse? Does tenure/payment frequency affect persistence? |
| Sales Performance | Which regions/agents generate the highest premium? How to optimize agent productivity? |
| Premium & Revenue | How does premium vary by policy type and payment frequency? Any seasonal demand patterns? |
| Underwriting | How do underwriting costs influence profitability? Which products incur higher costs? |
| Loan Utilization | What % of policies are loan-eligible vs utilized? Does loan eligibility influence retention? |

---

## <a id="key-findings"></a>📌 Key Findings

### 📍 Portfolio Health
- **73.7% policies active**
- **Lapse rate only 1.08%** → strong retention

### 📍 Geographic Insights
- North & Central regions dominate premium generation
- **Top 5 states contribute ~50% total coverage**
- East (15.16%) and West (10.18%) regions remain underpenetrated → **growth opportunity**

### 📍 Product Mix & Tenure
- Whole Life policies have **highest tenure (23.53 years)**
- Monthly payment frequency = **60–65% of collections**, but increases operational costs

### 📍 Operational Efficiency
- Underwriting expense ratio = **0.4% (well below industry standards)**

### 📍 Loan Utilization
- **3,559 loan-eligible policies**
- **₹3,292.7M loan amount available**
- Loan benefit improves retention, yet **underutilized** — customers require better awareness

### 📍 Premium Trends & Future Liabilities
- Quarterly premium collection declined **66% from 2016 peak**
- Maturity liabilities concentrated:
  - **>20 years:** ₹17,455.9M
  - **15–20 years:** ₹10,358.59M
  - **10–15 years:** ₹5,018.21M

---

## <a id="results--conclusions"></a>📌 Results & Conclusions

The insurance portfolio demonstrates:

✔ **Healthy customer retention (1.08% lapse)**  
✔ **Exceptional underwriting efficiency (0.4% expenses)**  
✔ **Strong performance in North & Central markets**  

However, the premium decline since 2016 signals an urgent need for:
- Geographic expansion
- Product innovation to restore growth
- Better promotion of loan features
- Shift toward quarterly/annual payment incentives to reduce cost burden

---

## <a id="author--contact"></a>👤 Author & Contact

**Mandeep Singh**  
Business Intelligence / Data Analyst  

📧 Email – mandeepsandhu055@email.com  
🔗 LinkedIn – https://www.linkedin.com/in/mandeep-sandhu-data-analyst/ 

---
