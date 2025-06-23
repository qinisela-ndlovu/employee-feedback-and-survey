# 📊 Employee Feedback Data Analysis Project

## 🧩 Overview  
This project analyzes employee feedback collected via a SharePoint list integrated with PowerApps. The goal is to gain insights into:

- ✅ **Employee satisfaction**  
- 🤖 **System friendliness**  
- 🔁 **Likelihood to continue using the product/service**  
- 🛠️ **Common issues and feature requests**

---

## 📁 Data Source  
- **Origin**: SharePoint list capturing employee feedback submissions.

---

## 🧹 Data Preparation  
- Exported raw data from SharePoint to CSV.  
- Cleaned data using **Power BI Power Query Editor**:
  - 🔄 Handled inconsistent data formats (e.g., “4 – Likely” ➡️ “4”)
  - 🚫 Addressed missing values with "No response" or blanks
  - 🧽 Standardized text fields & normalized rating scales

---

## 🔍 Insights  
- 📈 Identified key trends such as:
  - Most common issue categories
  - Overall satisfaction levels
  - Correlations between friendliness and likelihood to continue  
- ⚠️ Note: Analysis has **limitations** due to:
  - Small sample size (new app)
  - Anonymous responses

---

## 🛠️ How to Use This Repository  
- Open the **Power BI `.pbix`** file for interactive exploration  
- Reference the **CSV** file for raw data  

---

## 🔮 Future Work  
1. 🔗 Automate data import from SharePoint via Power BI connector  
2. 🧠 Enhance feature request analysis using **text mining/NLP**  
3. 📊 Expand dataset for deeper, more reliable insights  
4. 🧭 Add filtering & drill-down capabilities in the Power BI dashboard  
