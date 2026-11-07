# Analysis of ATM/CRM Infrastructure in India (2023–2024) using Python: Insights and Recommendations for Digital Banking Adoption

## 📌 Project Overview
This project analyses ATM/CRM infrastructure across different bank categories in India during 2023 and 2024. Using Python, the data is explored and analysed to identify infrastructure distribution, relationships, and year-wise trends. The findings provide insights to support banking infrastructure planning and digital banking development.

## 🎯 Objectives
- Analyse the distribution of on-site and off-site ATM/CRM infrastructure.
- Compare infrastructure across bank categories.
- Examine year-wise changes between 2023 and 2024.
- Identify relationships between on-site and off-site ATM/CRM counts.
- Provide data-driven insights and recommendations.

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## 📊 Analysis Performed
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Descriptive statistical analysis
- Univariate and bivariate analysis
- Correlation analysis
- Outlier detection
- Year-wise and bank-category comparison
- Data visualization

## 🔍 Key Insights
1. Public Sector Banks have the largest ATM/CRM infrastructure.
They recorded the highest average counts in both years, decreasing slightly from 6,522.85 in 2023 to 6,454.44 in 2024. This indicates that public sector banks maintain a comparatively extensive physical banking network.
2. Private Sector Banks showed growth in on-site infrastructure.
The average on-site ATM/CRM count increased from approximately 2,029 in 2023 to 2,198 in 2024, representing growth of around 8.36%.
3. Small Finance Banks recorded infrastructure growth.
Their average on-site ATM/CRM count increased from approximately 243 in 2023 to 274 in 2024, a rise of around 12.71%.
4. On-site and off-site ATM/CRM counts have a strong positive relationship.
The correlation is approximately +0.90, suggesting that banks with more on-site ATMs/CRMs also tend to have more off-site ATMs/CRMs. This indicates an association, not causation.
5. Infrastructure is unevenly distributed across bank categories.
Public and private sector banks account for much higher average ATM/CRM counts than foreign and payment banks. Payment banks have very limited ATM/CRM infrastructure in comparison.
6. The findings can support digital banking recommendations.
Banks may use their existing ATM/CRM networks to improve customer awareness and access to digital services such as UPI, mobile banking, and internet banking.


## 📁 Project Structure
```text
ATM-CRM-Infrastructure-Analysis/
│
├── data/
│   └── dataset.csv
│
├── notebook/
│   └── ATM_CRM_Analysis.ipynb
│
├── visuals/
│   └── charts/
│
└── README.md
```

## 💡 Conclusion
The analysis highlights differences in ATM/CRM infrastructure across bank categories and identifies year-wise changes. These insights can support further investigation into infrastructure planning and the role of physical banking networks in digital banking development.

## ⚠️ Limitations
The analysis covers only 2023 and 2024. The dataset measures ATM/CRM infrastructure and does not directly measure digital payment adoption or customer demand. Additional transaction, cost, and geographic data would strengthen future analysis.

