Emergency Care Analysis Dashboard

📊 Project Overview

The Emergency Care Analysis Dashboard is an interactive Power BI report designed to analyze hospital emergency room (ER) operations. It provides key insights into patient admissions, waiting times, satisfaction levels, and departmental referrals.

The goal of this project is to help healthcare administrators identify trends, improve patient flow efficiency, and optimize staffing and resource allocation in emergency departments.

🎯 Objectives

Analyze total patient inflow trends by hour, day, and month

Monitor average waiting time and its correlation with patient satisfaction

Evaluate department referrals and patient admission distribution

Track demographics such as gender, race, and age categories

Provide actionable insights for hospital performance improvement

📈 Key Insights from the Dashboard

Total Patients: 4,878

Average Waiting Time: 35.5 minutes

Patient Feedback Index: 4.96

Departments Referred: 2,000+

Admission Status: 50.33% Admitted, 49.67% Not Admitted

Highest Patient Volume: Weekdays between 9 AM – 3 PM

Top Referral Departments: General Practice, Orthopedics, Cardiology

Dominant Patient Demographics: Ages 40–69 and White/African American races

🧩 Data Model

Tables Used:

Datas of Dates

Date, Day, Month, Month & Year, Weekdays, Year

Hospital ER_Data

Patient Admission Date, Admission Hour, Department Referral

Patient Age, Gender, Race, Satisfaction Score, Wait Time

Referral Department, Admission Flag, Patient Feedback, and more

Relationships:

Linked by Patient Admission Date → Date

Ensures dynamic time intelligence for yearly/monthly trends

🖥️ Dashboard Features

📅 Dynamic Date Filters: Year and Month slicers for trend analysis

⏱️ Waiting Time vs Scheduled Time comparison donut chart

👥 Demographics Distribution: Age, Gender, and Race visual insights

🏥 Department Referral Analysis to identify patient flow

📊 Hourly Heat Map: Displays patient count by day and hour

🧠 Tools & Technologies
Tool	Purpose
Power BI Desktop	Data modeling, DAX measures, and visualization
Excel / CSV	Source data files
DAX	Used for calculated columns, measures, and KPIs
Power Query Editor	Data cleaning and transformation
📂 Repository Structure
📁 Emergency-Care-Analysis/
│
├── 📊 Emergency_Care_Analysis.pbix      # Power BI Dashboard file
├── 📄 README.md                         # Project documentation
├── 📁 Dataset/                          # Raw or cleaned data files
│     └── Hospital_ER_Data.csv
└── 📁 Images/                           # Dashboard screenshots
      ├── Dashboard_View_1.png
      ├── Dashboard_View_2.png
      └── Data_Model_View.png

🚀 How to Use

Download the .pbix file from this repository

Open it in Power BI Desktop

Load the dataset or connect to your data source

Explore the interactive visuals and apply filters

📋 Future Enhancements

Add predictive analysis for patient inflow trends

Integrate real-time hospital data sources

Include doctor shift scheduling optimization

🏁 Conclusion

This dashboard provides healthcare managers and administrators with a clear, data-driven view of emergency department operations. By leveraging Power BI’s visualization capabilities, it empowers stakeholders to make informed decisions to reduce wait times, enhance patient satisfaction, and streamline ER workflows.

🧑‍💻 Author

Agnes A]
💼 Data Analyst | Power BI Developer | Business Analyst
📍 Chennai, India
