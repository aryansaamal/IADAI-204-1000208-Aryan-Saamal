## 📊 IPL Cricket Analysis – Match-Winning Factors (Tableau Dashboard)
---

### 📌 Project Overview

This project presents an interactive Tableau dashboard analysing Indian Premier League (IPL) cricket data to uncover key match-winning factors. The dashboard is designed to support teams, coaches, analysts, and fans in understanding how player performances, team rivalries, and toss decisions influence match outcomes. The goal is to transform raw cricket data into meaningful visual insights that support data-driven storytelling.

---

### 🗂️ Data Summary

**Datasets Used:**

* `matches.csv` – Match-level details (season, teams, venue, toss, winner)
* `deliveries.csv` – Ball-by-ball data (runs, wickets, batsmen, bowlers)

**Data Preparation & Processing:**

* Joined `matches.csv` and `deliveries.csv` using `matches.id = deliveries.match_id` (Inner Join).
* Standardised key fields and ignored irrelevant columns.
* Created calculated fields in Tableau:

  * **Strike Rate** = Runs per 100 balls
  * **Economy Rate** = Runs conceded per over
  * **Wickets** = Count of wickets (excluding run-outs)

---

### 🔍 Key Insights

* Top batsmen play a crucial role in setting strong foundations, especially during powerplay overs.
* Wicket-taking bowlers with lower economy rates significantly impact match outcomes.
* Certain team rivalries show consistent dominance across seasons.
* Toss decisions influence match results at specific venues, highlighting the role of match conditions.

---

### 🧭 Dashboard Features

* **Top Batsmen Analysis:** Bar chart showing leading run-scorers with strike rates.
* **Top Bowlers Analysis:** Bar chart highlighting wicket-takers with economy rates.
* **Team Rivalries:** Comparative view of head-to-head match outcomes.
* **Toss vs Win:** Visual comparison of toss decisions and match results.
* **Interactive Filters:** Users can filter by season, team, and venue to explore specific scenarios.

---

### 🖼️ Relevant Screenshots

<img width="1718" height="1146" alt="image" src="https://github.com/user-attachments/assets/8d8f15c0-10a1-4532-9474-fa063adb31e4" /><img width="1861" height="1243" alt="Screenshot 2026-02-14 231930" src="https://github.com/user-attachments/assets/575d252d-3dec-4fdf-aabf-d5015e501805" /><img width="994" height="814" alt="image" src="https://github.com/user-attachments/assets/f044e7db-e735-4845-8ca7-5c6157601a75" />






---

### Dashboard Link
https://public.tableau.com/views/IPLCricketAnalysis_17710909342860/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


---
