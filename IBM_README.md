# IBM Watson Auto Insurance — Marketing & Risk Analysis

**Business Problem:** An auto insurance company is spending marketing budget across 4 channels and 4 renewal offer types — but does not know which combinations drive the highest customer lifetime value and most cost-effective renewals. This project identifies exactly that, and surfaces where budget is actively being wasted.

This Power BI dashboard analyzes **9,134 customer records across 5 U.S. states** — covering a total claims portfolio of **$3.96M** — using DAX measures, Power Query transformations, and drill-through filtering to surface actionable decisions for marketing and risk teams.

---

## Project Summary

| Metric | Value |
|---|---|
| Customers Analyzed | 9,134 |
| Features | 24 columns |
| CLV Range | $1,898 – $83,325 |
| Average CLV | $8,005 |
| Total Claims Portfolio | $3,964,967 |
| Avg Monthly Premium | $93 |
| Overall Renewal Response Rate | 14.3% |
| States Covered | Washington, Arizona, Nevada, California, Oregon |

---

## Key Business Insights & Recommendations

### 1. ⚠️ Offer 4 Has a 0% Response Rate — Yet 1,024 Customers Are Still Being Sent It
This is the most urgent finding in the dataset. Offer 4 was sent to 1,024 customers and generated **zero renewals** — a 0.0% response rate across every channel and every state. Meanwhile, Offer 2 achieves a **23.4% response rate**, the highest of all offer types.

The company is spending real budget marketing to over 1,000 customers with a guaranteed zero return.

**Recommendation:** Discontinue Offer 4 immediately. Reallocate that budget entirely to Offer 2 campaigns. The Agent + Offer 2 combination is the single highest-performing pairing in the data at **31.9% response rate** — nearly one in three customers converts. That combination should become the default renewal strategy.

---

### 2. Agent Channel Converts at 1.7x the Rate of Every Other Channel — Yet Budget Is Split Equally
The Agent channel achieves a **19.1% renewal response rate**, compared to Web (11.8%), Branch (11.5%), and Call Center (10.9%). That makes Agent **67% more effective** than the average of the other three channels combined.

More importantly, the Agent + Offer 2 pairing hits **31.9%** — while the same Offer 2 through Call Center delivers only **23.2%**, and through Branch just **16.0%**.

**Recommendation:** Shift renewal campaign budget heavily toward the Agent channel. Use Branch and Call Center for new customer acquisition only — these channels lose their advantage the moment a customer already exists in the system. Pair every Agent renewal campaign with Offer 2 as the default.

---

### 3. Premium Coverage Customers Generate 52% Higher CLV — But File Claims at the Same Rate as Basic
Premium coverage customers average **$10,896 CLV** versus **$7,191 for Basic** — a 52% difference. Despite filing higher average claims ($651 vs $379), their renewal response rate (14.6%) is virtually identical to Basic customers (14.3%).

This means Premium customers are not harder to retain — they're just more valuable when you do.

**Recommendation:** Prioritize Premium coverage upsells during renewal conversations, particularly through the Agent channel. The CLV uplift of $3,700 per customer more than justifies higher retention spend. Introduce a loyalty-based deductible reduction for Premium customers who go 12+ months claim-free — this reduces cost while reinforcing retention.

---

### 4. Luxury SUV and Luxury Car Owners Are 2.1x More Valuable Than Average — And Being Underserved
Luxury SUV and Luxury Car owners average **$17,123 and $17,053 CLV** respectively — more than double the company average of $8,005. They file 3.1x more claims than standard Four-Door Car owners, but their premium and lifetime value more than compensate.

The risk is not their claims volume — it is losing them to a competitor.

**Recommendation:** Create a dedicated retention track for Luxury vehicle owners. Proactively assign them to Agent channel with Offer 2, and pair them with Premium coverage. Set a claims frequency alert at the vehicle class level so the risk team can engage before a customer crosses into unprofitable territory. These customers are too valuable to manage reactively.

---

### 5. Customers With 2+ Complaints Have 15% Lower CLV and Are Far Less Likely to Renew
Customers with 2 or more open complaints show a **12.4% renewal response rate** and average CLV of **$7,375** — notably lower than complaint-free customers (14.6% response rate, $8,059 avg CLV). The gap widens as complaint count increases.

**Recommendation:** Flag customers with 2+ open complaints before any renewal campaign is triggered. Route them to a complaint resolution workflow first — then re-enter them into the renewal funnel once resolved. Marketing to unresolved complainers wastes campaign spend and risks accelerating churn. Complaint resolution is a pre-condition for effective renewal marketing, not an afterthought.

---

## Dashboard Structure

| Page | What It Shows |
|---|---|
| CLV Analysis | CLV by state, income, education, employment status |
| Marketing Performance | Channel × Offer response rates, policy type breakdown |
| Risk Analysis | Complaint vs claim heatmap, high-risk vehicle segments |
| Geographic View | State-wise CLV, premium, and response rate comparisons |

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard development and visualization |
| DAX | Calculated measures, KPIs, and segment logic |
| Power Query (M) | Data cleaning and transformation |

---

## Repository Structure

```
├── IBM_Watson_Marketing-Customer-Value-Analysis.csv   # Source dataset (9,134 records)
├── IBM_Marketing___Risk_Analysis_Dashboard.pbix       # Power BI dashboard
└── README.md
```

---

## How to Open

1. Download `IBM_Marketing___Risk_Analysis_Dashboard.pbix`
2. Open in Power BI Desktop (free download from Microsoft)
3. If data doesn't load: `Transform Data → Data Source Settings` → update path to your local CSV

---

## Author

**Kabeer Khan** — Data Analyst
📧 kabeerk992@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/kabeer-khan-analyst) | [GitHub](https://github.com/kabeerK992/ibm-marketing-risk-dashboard)
