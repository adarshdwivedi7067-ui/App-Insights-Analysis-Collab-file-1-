#  App Insights Unlocked: Google Play Store Analytics

**Developed by:** Adarsh Dwivedi  
**Role:** Data and Business Analyst  

This repository features a complete **End-to-End Data Analytics Project** focused on the Google Play Store ecosystem.  
By analyzing **9,367+ apps**, the project identifies the key factors that drive app success, user engagement, and monetization strategies in the modern mobile market.

---

##  Technology Stack & Tools
- **Python:** Primary language used for Exploratory Data Analysis (EDA).  
- **Pandas & NumPy:** Data cleaning, handling missing values, and numerical transformations.  
- **Matplotlib & Seaborn:** Statistical visualizations and distribution plots.  
- **Microsoft Power BI / Looker Studio:** Interactive business dashboards.  
- **Power Query:** Advanced data modeling and unit conversion (MB/KB standardization).  

---

##  Project Workflow
### 1. Data Cleaning & Preprocessing
- **Unit Standardization:** Converted app Size into a uniform numerical format (MB).  
- **Data Type Correction:** Cleaned and converted Installs and Price columns by removing special characters (+, ,, $).  
- **Handling Nulls:** Strategically managed missing Rating values to ensure statistical accuracy.  
- **Deduping:** Removed duplicate entries to prevent bias in category analysis.  

### 2. Exploratory Data Analysis (EDA)
Using Python and Power BI, the following analyses were performed:  
- **Category Trends:** Identified genres with highest saturation vs. highest demand.  
- **Rating Analysis:** Benchmarked user satisfaction across different content ratings.  
- **Monetization Impact:** Analyzed how Free vs Paid status affects installs and reviews.  

---

##  Strategic Insights & Findings
- **The Power of Free:** 92.6% of apps are free-to-download, showing ad-revenue and in-app purchases dominate.  
- **Installation Giants:** Family category has the most apps, but Games and Communication dominate reach with **167+ Billion installs**.  
- **Quality Benchmark:** Average rating is **4.19**. Apps below 4.0 show a sharp drop in trust and organic downloads.  
- **Market Leaders:** Subway Surfers, 8 Ball Pool, and Sniper 3D identified as top performers.  

---

##  Business Recommendations
- **Genre Targeting:** New developers should explore categories like Education and Events (high ratings, low competition).  
- **Engagement Strategy:** Frequent updates correlate with higher ratings; maintain a regular update cycle.  
- **Pricing Niche:** Paid apps have fewer installs but often higher ratings. Premium strategy works best for niche utility/productivity tools.  

---

##  Repository Structure
- `App_Insights_EDA.ipynb` → Python notebook containing cleaning and visualization code.  
- `project_power_bi.pbix` → Interactive Power BI dashboard file.  
- `App_Insights_Analysis.docx` → Detailed project documentation and problem statement.  

---

## 📎 Data Source
Google Play Store Dataset (Kaggle) analyzed using **Python & Power BI**.
