# 🏥 Supplier Performance and Risk Dashboard

A data analytics project that evaluates healthcare supplier performance to identify risks, optimize sourcing decisions, and drive strategic procurement planning.

---

## 🔍 Project Overview

In the healthcare supply chain, consistent and high-quality supplier performance is critical to ensuring patient care is not disrupted. This project uses data analytics to:

- Calculate supplier KPIs such as on-time delivery, lead time variability, and defect rates
- Score and rank suppliers by performance
- Cluster vendors into tiers based on historical reliability
- Provide actionable visual insights through a Power BI/Tableau dashboard

---

## 📊 Key Features

- 📦 **Vendor Scoring Model** based on custom KPI weightings
- ⏱️ **Lead Time Analysis** with variability tracking
- 🧼 **Clean, Processed Data** from raw supply chain exports
- 📈 **Interactive Dashboard** for procurement leadership
- 📁 **Modular Codebase** for reuse across datasets

---

## 🧰 Tech Stack

- **Python** – pandas, numpy, matplotlib, seaborn, scikit-learn
- **Power BI** or **Tableau** – for interactive dashboards
- **Jupyter Notebooks** – for EDA and modeling
- **Git & GitHub** – version control and project tracking

---

## 📁 Project Structure

```
supplier-performance-dashboard/
├── data/                  # Raw and processed datasets
├── notebooks/             # Jupyter notebooks for analysis
├── app/                   # Final dashboard (Power BI or Tableau)
├── reports/               # Visuals and final report
├── src/                   # Scripts for cleaning, KPIs, scoring
├── README.md              # Project overview
├── requirements.txt       # Python dependencies
└── .gitignore             # Files to exclude from Git
```

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/supplier-performance-dashboard.git
   cd supplier-performance-dashboard
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open and run the notebooks in `/notebooks`:
   - `01_data_cleaning_and_eda.ipynb`
   - `02_supplier_kpis.ipynb`
   - `03_dashboard_modeling.ipynb`

4. Open the final dashboard from the `/app` folder in Power BI or Tableau.

---

## 📌 KPIs Tracked

| KPI Name               | Description                              |
|------------------------|------------------------------------------|
| On-Time Delivery %     | % of orders delivered on or before due   |
| Lead Time Variability  | Standard deviation of delivery time      |
| Order Accuracy Rate    | % of orders received without defect      |
| Cost Variance          | % deviation from contract pricing        |
| Fill Rate              | % of order quantity fulfilled            |

---

## 📂 Sample Dataset

A sample dataset is provided in `/data/raw/` containing anonymized supplier performance data:
- `supplier_id`
- `po_date`
- `delivery_date`
- `ordered_qty`
- `received_qty`
- `unit_cost`
- `contract_cost`

---

## 🧠 Insights Example

- 3 suppliers show increasing lead time variability over 6 months
- 2 vendors have >15% cost variance from contract pricing
- Clustering reveals Tier 1, Tier 2, and Tier 3 suppliers by performance

---

## 📌 Future Improvements

- Incorporate supplier risk scores from external data (e.g., ESG, compliance)
- Automate monthly KPI refresh with real-time data
- Add drill-through capabilities in the dashboard for line-item analysis

---

## 👤 Author

**Jay**  
📫 [YourEmail@example.com]  
🔗 [LinkedIn Profile]  
💻 [GitHub Profile]

---

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for details.
