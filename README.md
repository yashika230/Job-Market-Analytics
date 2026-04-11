# Job-Market-Analytics
📌 Brief One Line Summary

A data analytics project that explores job market trends by analyzing job postings, extracting key skills, and visualizing insights using Power BI.
##
📖 Overview

This project focuses on analyzing job market data to uncover trends in salaries, in-demand skills, hiring companies, industries, and job distribution across locations.

The dataset was cleaned and transformed using Python, and an interactive dashboard was built using Power BI to present actionable insights.
##
❗ Problem Statement

The job market contains large amounts of unstructured data, making it difficult to identify trends such as:

Which skills are most in demand
Which companies are hiring the most
Salary distribution across job roles
Industry and location-based opportunities

This project aims to convert raw job posting data into meaningful insights.

📂 Dataset
Source: Job postings dataset (raw CSV format)
Contains:
Job title
Company
Location
Salary range (low & high)
Job description
Industry
Employment type

⚠️ The dataset initially had:

Missing values
Unstructured text (skills inside description)
Inconsistent formatting
🛠️ Tools and Technologies
Python (Pandas, NumPy) → Data cleaning & transformation
Power BI → Data visualization & dashboard
VS Code / Jupyter Notebook → Development environment
CSV Files → Data storage
⚙️ Methods
🔹 Data Cleaning
Removed duplicates and null values
Standardized column names
Cleaned location and industry fields
Created avg_salary from salary range
🔹 Skills Extraction
Extracted skills from job descriptions using keyword matching
Converted unstructured text into structured skills column
Handled multiple skills per job
🔹 Data Transformation
Split skills into rows for analysis
Standardized categories (job titles, industries)
📈 Key Insights
🔥 Python, SQL, and Cloud technologies are the most in-demand skills
🏢 Top companies dominate hiring with significantly higher job postings
💰 Salary varies by job role, with technical roles offering higher compensation
📊 Mid-senior level roles have the highest demand
🌍 Job opportunities are concentrated in specific key locations
🏭 Certain industries dominate hiring trends
📊 Dashboard / Output

The Power BI dashboard consists of 2 pages:

📌 Overview Page
KPI Cards (Salary, Companies, Locations, Skills)
Top Hiring Companies
Top Industries
Job Level Distribution
📌 Detailed Analysis Page
Salary by Job Title (Average vs Median)
Top In-Demand Skills
Job Distribution by Location

👉 The dashboard provides an interactive and user-friendly way to explore job market trends.

▶️ How to Run this Project
🔹 Step 1: Clone Repository
git clone <your-repo-link>
🔹 Step 2: Install Dependencies
pip install pandas numpy
🔹 Step 3: Run Data Cleaning Script
python data_cleaning.py
🔹 Step 4: Open Dashboard
Open Power BI file (.pbix)
Load cleaned dataset
Explore visuals
📊 Results & Conclusion

This project successfully transforms raw job posting data into meaningful insights.

It helps:

Job seekers identify in-demand skills
Companies understand hiring trends
Analysts explore salary and industry patterns

The dashboard makes complex data easy to understand and supports data-driven decision making.

🚀 Future Work
Use NLP for advanced skill extraction
Add real-time data integration
Improve salary prediction using machine learning
Expand dataset for better accuracy
Deploy dashboard online
💡 Final Note

This project demonstrates strong skills in:

Data Cleaning
Data Transformation
Data Visualization
Analytical Thinking
