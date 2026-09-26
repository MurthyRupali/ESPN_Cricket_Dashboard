# ESPN_Cricket_Dashboard
An interactive Power BI dashboard analyzing historical cricket data between India and Pakistan scraped from ESPN Cricinfo. The dashboard transforms raw match and player statistics into visual insights, offering a comparative analysis of head-to-head records, individual player performances.
Project Title
ESPN India vs. Pakistan Cricket Analytics & Performance Dashboard


# 🏏 ESPN India vs. Pakistan Cricket Analytics Dashboard

An interactive Power BI dashboard analyzing player performances and match statistics between India and Pakistan using scraped data from ESPN Cricinfo.

---

## 📌 Project Overview
This project provides a comparative analysis of player performance across **Batting**, **Bowling**, and **Fielding** modules. By cleaning raw match records and modeling relational data in Power BI, the dashboard allows users to dynamically explore career spans, scoring efficiencies, and match impact metrics for individual players.

---

## 📊 Dashboard Pages & Feature Breakdown

### 1. 🏏 Batting Analysis
* **Volume & Longevity:** Tracks player active span, total matches played, innings, and not outs.
* **Scoring Efficiency:** Calculates total runs, strike rate, batting average, and balls faced.
* **Milestones:** Displays highest score, 50s, 100s, and ducks (zeroes).

### 2. ⚾ Bowling Analysis
* **Workload & Control:** Measures overs bowled, maidens, total runs conceded, and economy rate.
* **Wicket Breakdown:** Tracks total wickets, bowling average, bowling strike rate, 4-wicket hauls, and 5-wicket hauls.

### 3. 🧤 Fielding Analysis
* **Fielding Contribution:** Analyzes total catches taken, catches as a fielder vs. catches as a wicketkeeper, and stumpings across match spans.

---

## 🛠️ Data Pipeline & Technical Details
* **Data Extraction:** Scraped from ESPN Cricinfo.
* **Data Transformation:** Cleaned, formatted, and structured using Power Query / Python.
* **Data Modeling:** Modeled using a Star Schema architecture in Power BI.
* **DAX Formulas:** Developed custom measures for dynamic averages, strike rates, and economy rates.

---

## 🛠️ Tools & Technologies Used
* **Power BI Desktop** (Data Modeling, DAX, Visualizations)
* **Power Query** (ETL Processing)
* **Python / Pandas** (Data Cleaning & Preparation)
* **Git & GitHub** (Version Control)

---

## ⚙️ How to View the Dashboard
1. Clone or download this repository.
2. Open the file `ESPN Ind-Pak cricket stats.pbix` using **Power BI Desktop**.
3. Use the top right **Player** filter dropdown on each tab to slice data by individual players.

### Dashboard Analysis & Key Insights

#### 1. Batting Analysis View (MS Dhoni Selected)

* **Career Span & Match Volume:** 2005–2019 across 36 matches (31 innings, 8 not outs).
* **Scoring Metrics:** 1,231 runs scored off 1,361 balls faced at a solid average of **53.52** and a strike rate of **90.00**.
* **Highlights:** Highest score of **148**, 2 centuries, 9 half-centuries, and 0 ducks (zeroes).

#### 2. Bowling Analysis View (Anil Kumble Selected)

* **Career Span & Match Volume:** 1990–2005 across 34 matches (33 innings).
* **Bowling Performance:** 54 wickets in 304 overs (18 maidens), conceding 1,310 runs.
* **Efficiency & Impact Metrics:** Bowling economy rate of **4.29**, bowling average of **24.25**, strike rate of **33.80**, and three 4-wicket hauls.

#### 3. Fielding Analysis View

* **Fielding Overview:** Tracks fielding metrics over specified spans (e.g., 1998–2006 across 24 matches).
* **Key KPIs:** Breaks down total catches taken (5), catches as a fielder (5), catches as a wicketkeeper (0), and stumpings (0).



