# 📊 Agent Productivity Dashboard – Google Looker  

<p align="center">
  <a href="https://github.com/joshuaalmari/data-analytics-portfolio">
    <img src="https://img.shields.io/badge/GitHub%20↗️-DATA%20ANALYTICS%20PORTFOLIO-2f2f2f?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://github.com/joshuaalmari/data-analytics-portfolio">
    <img src="https://img.shields.io/badge/CLICK%20TO%20RETURN-0078D4?style=for-the-badge"/>
  </a>
</p>

---

## 🏢 Project Overview
<p align="justify">
This Google Looker dashboard tracks daily team performance by monitoring <b>Average Handling Time (AHT), Hold Time, Adherence, QA Scores, Offline Activities, Max Hours, Refused Calls, ACW,</b> and <b>Total Daily Hours</b>.  
It provides <b>real-time insights</b> for team leaders to assess productivity, identify workflow gaps, and make data-driven decisions to optimize efficiency.
</p>

---

## 🔧 Workflow & Data Pipeline
- **🖥️ Data Extraction:** Automated daily export of performance data using <b>Python + Playwright</b>, removing the need for manual downloads.  
- **🧹 Data Preparation:** Cleaned, validated, and standardized data using <b>Excel</b> and <b>Power Query</b> to ensure accuracy.  
- **📊 Data Integration:** Processed datasets were uploaded to <b>Google Sheets</b> as a dynamic data source for Looker.  
- **📈 Dashboard Development:** Built in <b>Google Looker</b> to visualize KPIs for agent-level and team-wide performance tracking.  

> ℹ️ <b>Data Update Frequency:</b> Automatically refreshed daily through Python scripts and integrated Google Sheets data feeds.  

---

## 📌 Key Metrics & Insights
- **👤 Agent Productivity** – Overall performance per agent  
- **⏱️ Average Handling Time (AHT)** – Efficiency in task or call handling  
- **📞 Average Hold Time** – Time spent on hold during interactions  
- **📅 Adherence** – Schedule compliance rate  
- **⭐ QA Scores** – Quality assurance ratings  
- **🛠️ Offline Activities** – Logged non-core activities  
- **⏳ Max Hours** – Longest logged hours in a shift  
- **🚫 Refused Calls** – Declined or unhandled calls  
- **📝 After Call Work (ACW)** – Post-interaction documentation duration  
- **🕒 Total Daily Hours** – Total logged time per agent  

---

## 🛠️ Tools & Technologies
- **Python (Playwright)** – Automated browser-based data export  
- **Excel + Power Query** – Data cleaning and transformation  
- **Google Sheets** – Live data connection layer  
- **Google Looker Studio** – Dashboard design and visualization  

---

## 🚀 Impact
- Streamlined daily reporting through <b>automated data extraction</b> and transformation workflows.  
- Reduced manual report generation time by over <b>80%</b>.  
- Provided <b>team leaders</b> with real-time, actionable insights for performance monitoring.  
- Improved <b>data visibility</b> across multiple operational KPIs.  

---

## 📁 Repository Contents
- `README.md` – Project overview and documentation  
- `data-prep/` – Excel templates and cleaning workflows (anonymized)  
- `dashboard/` – Looker dashboard screenshots and sample views  
- `automation/` – Python scripts for Playwright automation  

---

## 🔗 Dashboard Access
[View Google Looker Dashboard (Interactive)](https://lookerstudio.google.com/)  
*(If public access is not available, screenshots can be viewed below.)*

---

## 🖼️ Visual Preview
<p align="center">
  <img src="dashboard/looker_dashboard_overview.png" width="750">
</p>

---

## 📥 Resources
- [Excel Data Template](data-prep/Agent_Productivity_Data.xlsx)  
- [Python Automation Script (Playwright)](automation/AgentData_AutoExport.py)  
- [Looker Dashboard Screenshot](dashboard/looker_dashboard_overview.png)  

---

## 📎 Data Notes
- **Source:** Internal agent productivity reports (anonymized for demo)  
- **Data Type:** Daily updated performance data  
- **Integration:** Google Sheets connected to Looker Studio  
- **Frequency:** Automated daily refresh  

---

<p align="center">
  ⚡ <b>Repository:</b> agent-productivity-looker-dashboard  
  <br><br>
  <a href="https://github.com/joshuaalmari/data-analytics-portfolio">
    <img src="https://img.shields.io/badge/BACK%20TO-DATA%20ANALYTICS%20PORTFOLIO-2f2f2f?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>
