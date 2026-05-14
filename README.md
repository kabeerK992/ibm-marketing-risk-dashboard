# IBM Watson Insurance Marketing & Risk Analysis

**Business Problem:** How can an auto insurance company identify high-value customers, reduce churn, and allocate marketing spend more effectively across channels and regions?

This Power BI dashboard analyzes 9,134 customer records from the IBM Watson Auto Insurance dataset to answer that question — covering customer lifetime value, claim risk, marketing response, and geographic performance.

---

## Dashboard Overview

| Area | What It Answers |
|---|---|
| Customer Lifetime Value (CLV) | Which customers are most valuable — and why? |
| Marketing Performance | Which channels and offers actually convert? |
| Risk Analysis | Which segments file the most claims? |
| Geographic Insights | Where is the company over- and under-performing? |

---

## Key Business Insights & Recommendations

### 1. Complaint-Free Customers Are 2–3x More Likely to Renew
Customers with zero open complaints respond significantly better to renewal offers across all channels.

**Recommendation:** Concentrate Offer 1 and Offer 2 renewal campaigns on complaint-free segments. Spending equally across all customers wastes budget on low-conversion groups. Expected improvement: 15–20% increase in renewal rate.

---

### 2. Premium Coverage Customers Have Higher CLV — But Also Higher Claim Costs
Despite filing more claims, Premium coverage customers generate substantially higher lifetime value than Basic or Extended segments.

**Recommendation:** Retain Premium customers aggressively — but introduce a loyalty-based deductible structure to reduce claim frequency without losing this high-value segment. Do not cut marketing spend here.

---

### 3. Agent and Web Channels Drive the Most Renewals
These two channels outperform Branch and Call Center for policy renewals across all policy types.

**Recommendation:** Reallocate marketing budget away from Branch and Call Center for renewal campaigns. Use those channels only for first-time acquisition where personal contact adds value.

---

### 4. Luxury SUV and Sports Car Owners File Higher Claims — But Carry Higher Premiums
This segment is high-risk and high-revenue simultaneously.

**Recommendation:** Do not deprioritize this segment. Instead, pair them with Premium coverage offers and monitor claim frequency closely. A claims alert threshold per vehicle class would help flag early patterns.

---

## Dataset

- **Source:** IBM Watson Analytics — Auto Insurance Sample Data
- **Records:** 9,134 customers | 24 features
- **States:** Washington, Arizona, Nevada, California, Oregon
- **Coverage Types:** Basic, Extended, Premium
- **Vehicle Classes:** Two-Door, Four-Door, SUV, Luxury SUV, Sports Car, Luxury Car

---

## Tools Used

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard development |
| DAX | Calculated measures and KPIs |
| Power Query (M) | Data cleaning and transformation |

---

## Repository Structure

```
├── IBM_Watson_Marketing-Customer-Value-Analysis.csv   # Source dataset
├── IBM_Marketing___Risk_Analysis_Dashboard.pbix       # Power BI file
└── README.md
```

---

## How to Open

1. Download `IBM_Marketing___Risk_Analysis_Dashboard.pbix`
2. Open in Power BI Desktop (free)
3. If data doesn't load, go to `Transform Data → Data Source Settings` and update the CSV path

---

## Author

**Kabeer Khan** — Data Analyst  
📧 kabeerk992@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/kabeer-khan-analyst) | [GitHub](https://github.com/kabeerK992)
