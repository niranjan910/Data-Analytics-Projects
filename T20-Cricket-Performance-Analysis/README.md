# 🏏 T20 Cricket Match Insights & Performance Analytics

This project explores detailed T20 cricket match data to uncover patterns that influence match outcomes. Using Python and pandas, we clean, transform, and analyze real match records to help franchises and analysts make better, data-driven decisions.

---

## 📌 **Business Problem**

> **Goal:** Identify the key factors that influence match outcomes in T20 cricket, with a focus on **batting performance**, **bowling impact**, and **match context** — empowering teams to refine strategy, player selection, and in-game tactics.

---

## 📂 **Dataset Overview**

- **Records:** 270,000+ match delivery details  
- **Key Features:**  
  - **Teams:** Batting, Bowling  
  - **Players:** Batter, Bowler, Wickets  
  - **Innings & Overs:** Ball-by-ball actions  
  - **Runs:** Batter runs, extras, totals  
  - **Context:** Venue, City, Season, Toss

---

## ⚙️ **Cleaning Steps**

1️⃣ Dropped irrelevant columns (IDs, redundant flags, helper columns)  
2️⃣ Standardized team names (e.g., *Delhi Daredevils → Delhi Capitals*)  
3️⃣ Converted binary columns (0/1) to clear ‘Yes/No’ labels  
4️⃣ Filled missing values for dismissals with `Not Out`  
5️⃣ Optimized data types: used `category` for text features to save memory  
6️⃣ Verified no nulls remain in key analysis fields

---

## 🔍 **Key Exploratory Analysis**

- **Team Analysis:** Match wins vs. venues, toss decisions, season trends  
- **Batting Insights:** Top batters by runs, strike rate  
- **Bowling Insights:** Top bowlers by wickets, economy rate  
- **Wicket Patterns:** Who dismisses whom  
- **Venue Impact:** Home advantage, high-scoring grounds  
- **Advanced Metrics:** Batter strike rates, bowler economy, top partnerships

---

## 📊 **Tools Used**

- **Python**: pandas, numpy  
- **Visualization:** seaborn, matplotlib  
- **IDE:** Jupyter Notebook / VSCode

---

## 💡 **Insights Delivered**

✅ Identify best performing batters & bowlers  
✅ Analyze how toss outcomes influence wins  
✅ Explore venue impacts on match results  
✅ Reveal bowler vs batter duels & common dismissal patterns

---
