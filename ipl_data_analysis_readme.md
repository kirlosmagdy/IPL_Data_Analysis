# 🏏 IPL Data Analysis using PySpark on Databricks

## 📋 Project Overview
This project focuses on **cleaning, analyzing, and visualizing IPL (Indian Premier League) data** using **PySpark** and **SQL** on **Databricks**. The goal is to uncover key insights from the IPL dataset such as team performances, player statistics, match outcomes, and winning patterns over the seasons.

This end-to-end data analysis project demonstrates strong data engineering and analytical skills — from data ingestion and transformation to analysis and visualization — all within a scalable cloud-based environment.

---

## 🎯 Objectives
- Perform **data cleaning** to handle missing, duplicate, or inconsistent records.
- Conduct **exploratory data analysis (EDA)** to identify patterns and trends.
- Use **SQL and PySpark DataFrame APIs** to query and manipulate data efficiently.
- Generate **visual insights** from the processed data.
- Showcase how **Databricks** can be used as a unified platform for big data analytics.

---

## 🧩 Dataset Description
The dataset includes detailed information about IPL matches, players, teams, and results across multiple seasons. The main data files uploaded to Databricks and GitHub include:

- **Matches Data:** Contains information about each match (season, date, venue, teams, winner, toss, etc.)
- **Deliveries Data:** Contains ball-by-ball details including batsman, bowler, runs, extras, and wickets.

---

## ⚙️ Technologies Used
- **Databricks** – Cloud-based environment for big data processing and analytics.
- **PySpark** – Distributed computing framework for data cleaning, transformation, and analysis.
- **SQL (Spark SQL)** – For structured querying and aggregations.
- **Python** – Used for data manipulation, visualization, and insights extraction.
- **Matplotlib / Seaborn (if used)** – For visualizations within the notebook.

---

## 🧼 Data Cleaning & Transformation
The first step involved cleaning and preparing the raw IPL data for analysis:

- Removed duplicates and null values.
- Standardized column names and formats.
- Merged related datasets (matches and deliveries) for enriched analysis.
- Derived new metrics such as total runs, strike rates, and win margins.
- Created SQL views to simplify querying.

---

## 🔍 Exploratory Data Analysis (EDA)
Comprehensive analysis was done using **PySpark DataFrames** and **SQL queries** to answer key business questions, such as:

- Which teams have won the most matches?
- Which players are the top run-scorers and wicket-takers?
- What is the most successful venue?
- How does winning the toss impact match outcomes?
- What are the scoring trends across seasons?

---

## 📊 Visualizations
Several visual insights were created to summarize findings, including:
- Top-performing teams by wins.
- Most consistent players (batsmen and bowlers).
- Toss vs. Match result correlation.
- Average runs per over and per season.

These visuals help stakeholders easily interpret complex data patterns.

---

## 🧠 Key Insights
- **Mumbai Indians** and **Chennai Super Kings** emerged as the most consistent teams over the years.
- Winning the **toss** doesn’t always guarantee winning the match.
- Certain venues have a higher win probability for teams batting first.
- Players like **Virat Kohli** and **AB de Villiers** consistently ranked among top run-scorers.

---

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/kirlosmagdy/IPL_Data_Analysis.git
   ```
2. Upload the files to your **Databricks workspace**.
3. Import the notebook file (`IPL_Data_Analysis.ipynb` or `.dbc`) into Databricks.
4. Attach a cluster and run all cells sequentially.
5. Explore the visualizations and SQL queries inside the notebook.

---

## 🔮 Future Enhancements
- Integrate **machine learning models** to predict match outcomes.
- Automate data ingestion using **Azure Data Factory** or **Databricks Jobs**.
- Build a **dashboard in Power BI or Tableau** to visualize the insights.

---

## 👨‍💻 Author
**Kirlos Magdy**  
Data Engineer | Python & SQL Enthusiast | Azure & Databricks Developer  
📎 [GitHub](https://github.com/kirlosmagdy) | [LinkedIn](https://www.linkedin.com/in/kirlosmagdy/)

---

## ⭐ Acknowledgements
Special thanks to Databricks and the open IPL datasets community for enabling this analysis.

If you found this project useful, consider ⭐ starring the repo to support future work!

