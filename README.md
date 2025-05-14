# 📊 Power BI NPS Dashboard

This repository contains a Power BI dashboard that analyzes **Net Promoter Score (NPS)** performance for India's top motorcycle companies, covering data from **April 2024 to March 2025**.

---

## 🧾 Dashboard Overview

The dashboard is divided into **three main pages**:

### 1️⃣ Guidelines  
- Overview of the project scope and data structure  
- Explanation of NPS & NP% calculation logic  

### 2️⃣ VCS (Visual Company Scorecard)  
- Company-wise and product-wise NPS scorecards  
- Monthly performance trends across dealers, states, and customer segments  

### 3️⃣ Tables & Personalize  
- Detailed data tables with slicers and filters  
- Ability to personalize columns (such as adding/removing fields)  
- Logos are used to represent each company for better visual recognition  
- Visual indicators for Promoters, Passives, and Detractors  

---

## 🔍 Key Metrics

### 🎯 Net Promoter Score (NPS)

**NPS = ((Promoters - Detractors) / (Promoters + Passives + Detractors)) * 100:**


| Rating Range | Category  |
|--------------|-----------|
| 9–10         | Promoter  |
| 7–8          | Passive   |
| 1–6          | Detractor |

---

### 🔢 NP% (Negative Percentage)

**NP% = ((Passives + Detractors) / (Promoters + Passives + Detractors)) * 100:**


---

## 🛠 Tools Used

- Microsoft Power BI Desktop  
- Microsoft Excel  
- DAX (Data Analysis Expressions)  
- Python (for synthetic data generation)  
- GitHub (for version control and hosting)

---

## 📁 Files Included

| File                         | Description                         |
|------------------------------|-------------------------------------|
| `NPS_Motorcycle_Final_20160.csv` | Final dataset (20,160 rows)     |
| `Power-BI_NPS-Dashboard.pbix`    | Power BI dashboard file         |
| `README.md`                      | Project documentation (this file) |

---

## 🖼 Screenshot Previews

📌 Place screenshots in an `images/` folder in the root of the repository.

```text
Power-BI_NPS-Dashboard/
├── images/
│   ├── ![image](https://github.com/user-attachments/assets/20aa19f4-db47-41fc-b9c7-78e8d6e0cd4f).png

│   ├── vcs_page.png
│   ├── tables_page.png![repository-open-graph-template](https://github.com/user-attachments/assets/ddcec4f8-b10b-4303-b447-1ea9cdae807a)

├── Power-BI_NPS-Dashboard.pbix
├── NPS_Motorcycle_Final_20160.csv
└── README.md
