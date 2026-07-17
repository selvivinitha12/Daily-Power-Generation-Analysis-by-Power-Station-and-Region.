# Daily-Power-Generation-Analysis-by-Power-Station-and-Region.
# ⚡ Daily Power Generation Analysis Dashboard

## 📖 Project Overview
The **Daily Power Generation Analysis Dashboard** is an interactive data analytics project developed using **Python** and **Power BI**. The project focuses on analyzing daily electricity generation data across different regions, sectors, and power station types. Python was used for data cleaning, preprocessing, and exploratory data analysis (EDA), while Power BI was used to create interactive dashboards for performance monitoring and decision-making.

---

## 🎯 Project Objectives
- Analyze daily power generation performance.
- Compare Actual Generation with Planned Generation.
- Measure Capacity Utilization and Generation Efficiency.
- Analyze Region-wise, Sector-wise, and Station Type-wise performance.
- Build an interactive Power BI dashboard for better business insights.

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Data Cleaning & EDA |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Exploratory Data Analysis |
| Power BI | Dashboard Development |
| Power Query | Data Transformation |
| DAX | KPI Calculations |
| Git & GitHub | Version Control |

---

## 📂 Dataset Information

The dataset contains information about:

- Date
- Region
- Sector
- Power Station
- Station Type
- Installed Capacity (MW)
- Monitored Capacity (MW)
- Planned Generation (MU)
- Actual Generation (MU)

---

## 🧹 Data Preprocessing (Python)

The dataset was cleaned using Python by:

- Removing duplicate records
- Handling missing values
- Converting data types
- Renaming columns
- Formatting numerical values
- Exporting the cleaned dataset as CSV

```python
df.to_csv("cleaned_dataset.csv", index=False)
```

---

## 📊 Dashboard KPIs

- Total Actual Generation
- Total Planned Generation
- Total Monitored Capacity
- Capacity Utilization
- Generation Efficiency
- Total Regions
- Total Sectors
- Total Power Stations

---

## 📈 Dashboard Visualizations

- KPI Cards
- Region-wise Line Chart
- Sector-wise Bar Chart
- Station Type Donut Chart
- Slicers
- Trend Analysis

---

## 🔍 Key Insights

- Actual generation is compared with planned generation to evaluate overall performance.
- Capacity utilization and generation efficiency measure operational effectiveness.
- Hydro, Thermal (Gas), and Nuclear stations contribute differently to total power generation.
- Region-wise analysis identifies high-performing and low-performing areas.
- Historical trends support future planning and operational monitoring.

---

## 🔄 Project Workflow

1. Collect the dataset
2. Clean data using Python
3. Perform Exploratory Data Analysis (EDA)
4. Export cleaned dataset
5. Import data into Power BI
6. Create DAX measures
7. Build interactive dashboard
8. Generate insights and conclusions

---

## 📸 Dashboard Preview

Add your Power BI dashboard screenshot here.

```
Dashboard.png
```

---

## 📁 Repository Structure

```
Daily-Power-Generation-Analysis/
│
├── Dataset/
│   └── cleaned_dataset.csv
│
├── Notebook/
│   └── Daily_Power_Generation_Analysis.ipynb
│
├── Dashboard/
│   └── Daily_Power_Generation_Dashboard.pbix
│
├── Images/
│   └── Dashboard.png
│
├── README.md
│
└── requirements.txt
```

---

## 🚀 Project Outcome

This project demonstrates how Python and Power BI can transform raw power generation data into meaningful business insights. The dashboard enables users to monitor generation performance, compare planned and actual generation, evaluate efficiency, and support data-driven decision-making for efficient power generation management.

---

## 👩‍💻 Author

**R. Vinitha**

**Data Analyst**

### Skills
- Python
- SQL
- Power BI
- Excel
- Pandas
- NumPy
- Data Visualization
- Data Cleaning
- Exploratory Data Analysis (EDA)

---
