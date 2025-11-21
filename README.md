# Data & Business Analytics Dashboard

This project analyzes 400+ Data & Business Analytics job postings in Germany and visualizes the insights using Tableau Public.

🔗 **Interactive Dashboard**  
https://public.tableau.com/app/profile/polina.nechaeva/viz/Analytics_17636388319460/Dashboard1?publish=yes

---

## 📁 Repository Structure

### **1. Raw Data**
- `dataset_linkedin-jobs-scraper_2025-11-19_12-03-47-361.json`  
  Raw dataset extracted using a LinkedIn job scraper. Contains uncleaned job posting data.

### **2. Cleaned Dataset**
- `analytics_jobs_exploded_2025-11-19.xlsx`  
  Processed dataset after:
  - cleaning text fields  
  - normalizing structure  
  - exploding skills, tools, and categories  
  - preparing the data for BI/analytics  

### **3. Notebook**
- `Analyst_job.ipynb`  
  Google Colab notebook with full data cleaning pipeline:
  - data loading  
  - preprocessing  
  - regex skill extraction  
  - exploding rows  
  - exporting analysis-ready dataset  

### **4. Documentation**
- `README.md` — this file.

---

## 🛠 Tech Stack

- **Python (Pandas, JSON, Regex)**
- **Google Colab**
- **Tableau Public**
- **LinkedIn Jobs Scraper**
- **Excel / CSV transformations**

---

## 📊 Dashboard Insights

The dashboard explores:

- Most in-demand tools (Python, SQL, Power BI, Tableau, dbt, Snowflake, etc.)
- Seniority breakdown (Junior / Mid / Senior)
- Employment types (full-time, part-time, contract)
- Work models (remote, hybrid, on-site)
- Industries hiring data professionals
- Tool clusters and demand distribution

---

## 🚀 How to Use

1. Open the notebook `Analyst_job.ipynb` to reproduce data cleaning.
2. Use `analytics_jobs_exploded_2025-11-19.xlsx` as a source file in Tableau.
3. Explore the interactive dashboard on Tableau Public.

---

## 📌 Next Steps (Ideas)

- Add salary extraction
- Compare cities (Berlin, Munich, Hamburg, Frankfurt)
- Track trends over time month-by-month
- Include more job boards

---

## 👤 Author

**Polina Nechaeva**  
Data Analyst / BI Specialist  
Tableau • Power BI • SQL • Python

Connect on LinkedIn for collaboration or questions.
