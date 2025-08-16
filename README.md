# WUZZUF-JobPulse-Dashboard
Power BI project analyzing WUZZUF job postings to extract insights on skills demand, career levels, work modes, and salary trends.
(demo.PNG)
---
## 1. Executive Summary
This project analyzes job-posting data from **WUZZUF** and transforms it into actionable insights using **Power BI (DAX, Power Query)**.  
Key outcomes:
- Data Wrangling & Cleaning (Power Query).
- Building 5 distinct and interactive visuals.
- User-Centric dashboard design.

---
## 2. Business Questions
- What are the most in-demand job roles/skills?  
- How do posting trends vary by location/work mode (Remote/On-site/Hybrid)?  
- Which career levels (Entry/Mid/Senior) dominate the market?  

👉 These drive insights for:
- **HR Strategy**: Focus on high-demand skills (e.g., Python, Digital Marketing).  
- **Talent Acquisition**: Target regions with low competition but high openings.  
- **Trend Monitoring**: Spot declining roles early.  

---
## 3. Data Preparation
- Removed blank rows & verified data types.  
- Extracted **day, month, year, quarter** from dates for trend analysis.  
- Normalized text (e.g., unified “Remote/remote/REMOTE”).  

---

## 4. Data Modeling & Measures
- Created dimensional table for skills.  
- Key Measures:
  - **Total Job Postings** – counts all postings.  
  - **Top 10 Skills** – most frequently mentioned skills.  
  - **Average Salary** – midpoint of min & max pay.  
  - **Average Experience** – mean required years of experience.  
  - **Remote Jobs %** – percentage of remote postings.  

---
## 5. Dashboard Design
### Key Visual Components:
1. **KPI Cards** → Total postings, Avg salary, Avg experience, Remote %  
2. **Trends (Column/Line)** → Job postings, salary, and experience over time  
3. **Pie Charts** → Skill breakdowns, job type, sector proportions  
4. **Map Visuals** → Geographic job density, salary variation, remote vs onsite  
5. **Interactive Slicers** → Career level, work mode, sector, salary ranges  

📌 **Why This Design Works**  
- **Hierarchical insights**: KPIs → Trends → Distributions → Maps.  
- **Actionable outcomes**: Recruiters, job seekers, and educators benefit.  
- **Engagement**: Visual variety & interactivity.  
- **Decision support**: Macro + micro perspectives.  

---
## 6. Tools & Skills
- **Power BI** (DAX, Power Query)  
- Data Cleaning & Wrangling  
- Data Visualization & Dashboarding  
- Business Intelligence (BI) Best Practices  

