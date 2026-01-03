<img width="1725" height="1375" alt="Screenshot 2026-01-03 215548" src="https://github.com/user-attachments/assets/c8e6fc6f-a461-4883-883f-305b596dfd0b" />

🍔 McDonald’s India Menu – Nutrition KPI Analysis
📌 Project Overview

This project analyzes the nutritional composition of McDonald’s India menu items with a focus on health-related KPIs such as fat, added sugar, and overall nutritional risk.
The goal is to demonstrate data cleaning, KPI creation, and transparent handling of data quality issues using a real-world dataset.

📂 Repository Structure
India-Menu-Nutrition-Analysis/
│
├── data/
│   ├── India_Menu_raw.csv
│   └── India_Menu_cleaned.csv
│
├── analysis/
│   ├── nutrition_kpis.xlsx
│   └── methodology.md
│
├── README.md
└── .gitignore

📊 Key KPIs Created

Average Fat per Item

Total Added Sugar per Item

Sugar Risk (%)

Nutritional Risk Score

Health Category (Healthy / Moderate / High Risk)

% High-Risk Menu Items

⚠️ Data Quality Note

The original dataset contains a Total Fat column populated with zero values across all menu items.
These values were treated as missing nutritional data, not as true zero-fat products.

To ensure transparency and analytical accuracy:

The raw dataset is preserved without modification

Derived columns were added in a cleaned dataset

Sugar-based nutritional risk KPIs were used where fat data was unavailable

All assumptions are documented in the methodology file

🧮 KPI Methodology (Summary)
Sugar Risk (%)
Sugar Risk (%) = (Added Sugar per Item ÷ 25g) × 100

Nutritional Risk Score

When fat data is unavailable:

Nutritional Risk Score = Sugar Risk (%)


Classification:

0–30 → Healthy

31–60 → Moderate

60 → High Risk

📈 Tools Used

Microsoft Excel (data cleaning & KPI calculations)

Git & GitHub (version control)

CSV data format

📌 Limitations

Fat-based KPIs could not be fully computed due to missing fat data

Analysis relies on available nutritional attributes (primarily sugar)

Results should be interpreted as indicative, not clinical

🎯 Key Takeaway

This project highlights the importance of ethical data handling and demonstrates how meaningful insights can still be derived from imperfect real-world datasets.

🤝 Contributions

Suggestions and improvements are welcome. Feel free to fork the repository or open an issue.
