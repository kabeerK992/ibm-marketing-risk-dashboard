# 📊 IBM Watson Marketing & Risk Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![IBM Watson](https://img.shields.io/badge/IBM%20Watson-BE95FF?style=for-the-badge&logo=ibm&logoColor=white)
![Dataset](https://img.shields.io/badge/Records-9%2C134-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> An interactive **Power BI dashboard** analyzing customer lifetime value, insurance risk profiles, and marketing performance using the IBM Watson Auto Insurance dataset.

---

## 📌 Project Overview

This project explores the IBM Watson Marketing – Customer Value Analysis dataset to uncover actionable insights about:

- Which customer segments generate the **highest lifetime value**
- How **coverage type, policy, and vehicle class** impact claim behavior
- The effectiveness of different **sales channels and renewal offers**
- **Risk profiling** based on complaint history, claim amounts, and income

The dashboard was built in **Microsoft Power BI** and is designed to support marketing and risk teams in making data-driven decisions.

---

## 📂 Repository Structure

```
├── IBM_Watson_Marketing-Customer-Value-Analysis.csv   # Source dataset (9,134 records)
├── IBM_Marketing___Risk_Analysis_Dashboard.pbix       # Power BI dashboard file
└── README.md
```

---

## 📋 Dataset Overview

**Source:** IBM Watson Analytics Sample Data – Auto Insurance  
**Records:** 9,134 customers | **Features:** 24 columns

| Category | Fields |
|---|---|
| **Customer Info** | Customer ID, State, Gender, Marital Status, Education, Employment Status |
| **Policy Details** | Policy Type, Policy, Coverage, Number of Policies, Effective To Date |
| **Financial** | Customer Lifetime Value, Income, Monthly Premium Auto, Total Claim Amount |
| **Behavioral** | Response, Renew Offer Type, Sales Channel, Months Since Last Claim |
| **Risk Indicators** | Number of Open Complaints, Months Since Policy Inception |
| **Vehicle** | Vehicle Class, Vehicle Size, Location Code |

### 🗺️ States Covered
`Washington` · `Arizona` · `Nevada` · `California` · `Oregon`

### 🚗 Vehicle Classes
`Two-Door Car` · `Four-Door Car` · `SUV` · `Luxury SUV` · `Sports Car` · `Luxury Car`

### 📦 Coverage Types
`Basic` · `Extended` · `Premium`

### 📝 Policy Types
`Corporate Auto` · `Personal Auto` · `Special Auto`

---

## 📊 Dashboard Highlights

The Power BI report includes the following analysis areas:

### 1. 💰 Customer Lifetime Value (CLV) Analysis
- CLV distribution across states and demographics
- CLV range: **$1,898 – $83,325**
- Segmentation by income bracket, education, and employment status

### 2. 📣 Marketing Performance
- Response rates by sales channel (Agent, Branch, Call Center, Web)
- Renewal offer effectiveness (Offer 1–4) by policy type
- Gender and marital status impact on campaign response

### 3. ⚠️ Risk Analysis
- Open complaints vs. claim amounts heatmap
- High-risk customer segments by vehicle class and coverage
- Months since last claim distribution by policy type

### 4. 🗺️ Geographic Insights
- State-wise CLV, premium, and claim comparisons
- Location code (Urban/Suburban/Rural) performance

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Power BI Desktop** | Dashboard development & visualization |
| **IBM Watson Dataset** | Source data |
| **DAX** | Calculated measures & KPIs |
| **Power Query (M)** | Data transformation & cleaning |

---

## 🚀 Getting Started

### Prerequisites
- [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Free)

### Steps to Run the Dashboard

1. **Clone this repository**
   ```bash
   git clone https://github.com/kabeerK992/ibm-marketing-risk-dashboard.git
   cd ibm-marketing-risk-dashboard
   ```

2. **Open the dashboard**
   - Launch **Power BI Desktop**
   - Click `File → Open` and select `IBM_Marketing___Risk_Analysis_Dashboard.pbix`

3. **Refresh data** *(if needed)*
   - Go to `Home → Refresh` to reload from the CSV file
   - If prompted, update the data source path to your local CSV location:
     `Transform Data → Data Source Settings`

---

## 💡 Key Insights (Sample)

- Customers with **Premium coverage** show significantly higher CLV despite higher claim amounts
- **Web and Agent channels** drive the most policy renewals
- **Luxury SUV and Sports Car** owners file higher total claims but also carry higher premiums
- Customers with **0 open complaints** are 2–3x more likely to respond positively to renewal offers

---

## 📈 Future Enhancements

- [ ] Add predictive CLV scoring using Python/ML integration
- [ ] Publish to Power BI Service for online access
- [ ] Add drill-through pages per customer segment
- [ ] Integrate real-time data refresh via API

---

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome!  
Feel free to open an **Issue** or submit a **Pull Request**.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

> **Dataset:** IBM Watson Analytics sample data, publicly available for educational and analytical use.

---

## 👤 Author

**Kabeer Khan**  
📧 Kabeerk992@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/kabeer-khan-63b7b4207?utm_source=share_via&utm_content=profile&utm_medium=member_ios)

---

⭐ *If you found this project helpful, please give it a star!*
