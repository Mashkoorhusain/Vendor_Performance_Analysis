# 🚀 Vendor Performance Analysis | End-to-End Data Analytics Project

Welcome! This project is a **real-world, end-to-end data analytics case study** focused on analyzing vendor performance using Python, SQL, and Power BI. It simulates how a business can use data to drive smarter decisions, optimize vendor selection, and improve profitability.

---

## 🎯 Project Objective

To help a retail company:
- Identify high-performing vendors
- Reduce product return rates
- Optimize product pricing
- Improve vendor partnerships using data-driven insights

---

## 🧰 Tools & Technologies

| Stack | Purpose |
|-------|---------|
| 🐍 **Python** | Data cleaning, transformation, EDA, statistical analysis |
| 🗃️ **SQLite** | Relational database for structured querying |
| 📊 **Power BI** | KPI dashboard for business stakeholders |
| 📒 **Jupyter Notebook** | Interactive analysis and documentation |
| 🧾 **PDF Report** | Summary of insights and recommendations |

---

## 📁 Project Structure

```
vendor-performance-analysis/
│
├── data/                    # Dataset(s)
│   └── vendor_sales_summary.csv
│
├── notebooks/               # Exploratory and analytical notebooks
│   ├── Exploratory Data Analysis.ipynb
│   └── Vendor Performance Analysis.ipynb
│
├── scripts/                 # Utility and DB ingestion scripts
│   ├── ingestion_db.py
│   └── get_vendor_summary.py
│
├── dashboard/               # Power BI .pbix file
│   └── vendor_performance.pbix
│
├── report/                  # Final report
│   └── Vendor Performance Report.pdf
│
├── requirements.txt         # Python dependencies
└── README.md                # Project overview
```

---

## 🔍 Key Insights

- 📈 **60%** of revenue came from top-performing vendors — but many had inconsistent margins
- 📉 Certain product categories had **high return rates**, suggesting quality or price issues
- 🧠 **Vendor X** showed the most consistent margin, making it a strong long-term partner
- 💰 Suggested **re-pricing strategies** improved average profit margins across multiple vendors

---

## 🧪 What I Did (Step by Step)

1. **Built a SQLite database** and connected it to Jupyter via SQLAlchemy
2. Wrote **complex SQL queries** to join and aggregate sales, returns, and inventory data
3. Performed **statistical tests** (t-tests, correlation) to evaluate vendor patterns
4. Created **meaningful visualizations** using Seaborn and Matplotlib
5. Designed a **Power BI dashboard** for decision-makers
6. Compiled a **formal business report** with recommendations

---

## 📊 Power BI Dashboard Highlights

- 📦 Vendor-level sales, returns, and margin trends
- 📅 Time-series analysis of profitability
- 🚦 Conditional formatting to flag underperformers
- 🧩 Filters to explore vendors by region, category, or return rate

> You can open the `.pbix` file in Power BI Desktop to explore it interactively.

---

## 🚀 How to Run the Project

> Recommended for users with basic Python + SQL knowledge

1. Clone or download the repo
2. Navigate to the `scripts/` folder and run:
   ```bash
   python ingestion_db.py
   ```
   This sets up the `inventory.db` database

3. Open the notebooks in the `notebooks/` folder and run cell-by-cell
4. Open the `.pbix` dashboard using Power BI Desktop
5. Read the final PDF report for key findings

---

## 🧾 Requirements

Install Python dependencies using:

```bash
pip install -r requirements.txt
```

---

## 📬 Let’s Connect

I'm passionate about data-driven storytelling and solving real business problems with analytics.

- 💼 [LinkedIn](https://www.linkedin.com/in/mashkoorhusain-husaini-728414305/)
- 📧 Email: www.mashkoorhusain07@gmail.com

---

## 🏁 Final Thoughts

This project was a deep dive into turning raw data into **business value**. From database setup to dashboard delivery, it reflects a real industry workflow and demonstrates both technical and business thinking.

Thanks for reading — feedback and collaboration are always welcome!
