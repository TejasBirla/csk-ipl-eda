# 🦁 CSK IPL EDA — 2008 to 2026

An exploratory data analysis of **Chennai Super Kings (CSK)**' IPL performance from 2008 to 2026 using **Python, Pandas, NumPy, Matplotlib, and Seaborn**.

This project explores CSK's performance across seasons, opponents, venues, and key match statistics while practicing the complete EDA workflow.

---

## 📌 Project Overview

The goal of this project is to analyse CSK's IPL journey and extract meaningful insights from match-level data.

The analysis covers:

* Season-wise win and loss percentage
* Opponent-wise wins and losses
* Win percentage against regular opponents
* M.O.M. award analysis
* League-stage finishing positions
* Championship and runner-up finishes
* Venue-wise win percentage
* Toss outcome vs match outcome

---

## 🛠️ Technologies Used

* **Python**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 📂 Project Structure

```text
CSK Analysis/

│
├── data/
│   └── IPL_Matches_Data_2008_2026.csv
│
├── notebooks/
│   └── csk_analysis_2008_2026.ipynb
│
├── README.md
└── venv/
```

---

## 📊 Dataset

The project uses a **match-level IPL dataset covering seasons from 2008 to 2026**.

The dataset contains information such as:

* Season
* Teams
* Venue
* Toss winner
* Toss decision
* Winner
* Player of the Match
* Match result

The data was cleaned and standardized before performing the analysis.

---

## 🔍 Analysis Performed

### 🏏 Season Performance

* Analysed CSK's win percentage across IPL seasons.
* Compared season-wise wins and losses.
* Analysed CSK's league-stage finishing positions.

### ⚔️ Opponent Analysis

* Calculated the number of matches and wins against each opponent.
* Compared CSK's wins and losses against different opponents.
* Analysed win percentage against teams CSK played at least 15 times.

### 🏆 Player Analysis

* Analysed the players with the most M.O.M. awards in CSK victories.

### 🥇 Playoff & Final Performance

* Analysed CSK's championship and runner-up finishes.
* Examined CSK's final results across IPL seasons.

### 🏟️ Venue Analysis

* Standardized inconsistent venue names.
* Analysed CSK's win percentage at venues where they played at least 10 matches.

### 🪙 Toss Analysis

* Compared CSK's match win percentage when they won and lost the toss.
* Analysed whether winning the toss was associated with a higher chance of winning the match.

---

## 📈 Key Insights

* CSK's win percentage has varied considerably across different IPL seasons.
* CSK have recorded a high number of wins against several long-term opponents.
* Their win percentage varies across opponents, highlighting differences in their head-to-head records.
* M.S. Dhoni and Ravindra Jadeja are among the players with the highest number of M.O.M. awards in CSK victories.
* CSK have reached the IPL final multiple times, with both championship and runner-up finishes.
* CSK's league-stage finishing position has varied across seasons.
* Venue-wise analysis shows differences in CSK's win percentage across grounds.
* CSK had a **59.40% match win rate when they won the toss**, compared with **51.88% when they lost the toss**, indicating a relatively small difference in match outcomes.

---

## 📚 Key Learnings

* Learned to clean and standardize real-world data using **Pandas**.
* Practiced **filtering, grouping, aggregation, and data transformation**.
* Learned to use **Boolean indexing, `value_counts()`, `groupby()`, and `reindex()`**.
* Learned to compare different categories and conditions using data analysis.
* Learned to choose appropriate charts based on the type of analysis.
* Gained practical experience with **Matplotlib and Seaborn**.
* Learned to interpret visualizations and extract meaningful insights.
* Understood the importance of **data quality, sample size, and limitations** in EDA.
* Learned how to follow a complete **EDA workflow — from understanding and cleaning the data to analysing, visualizing, and communicating insights**.

---

## ⚠️ Limitations

* The analysis depends on the quality and completeness of the available dataset.
* Some team and venue names required manual standardization.
* Teams have participated in different numbers of IPL seasons, so opponent-wise win percentages should be considered alongside the number of matches played.
* Venue analysis was limited to venues where CSK played at least 10 matches.
* Toss analysis shows association between toss outcome and match outcome; it does not establish that winning the toss directly causes a team to win.
* The analysis focuses on match-level data and does not account for factors such as injuries, playing XI changes, weather, toss decisions, or other match-specific circumstances.
* The project is descriptive and does not include predictive modelling.

---

## 🚀 Future Analysis & Improvements

### 🟢 Short-Term — Improve Current EDA

* Add **data validation** and reduce manual data cleaning.
* Analyse **home vs away performance**.
* Add more **player-wise performance analysis** across seasons.
* Improve visualizations with clearer labels, sorting, and annotations.

### 🟡 Medium-Term — Deeper Analysis

* Add **ball-by-ball data** to analyse batting and bowling performance.
* Analyse **powerplay, middle-over, and death-over performance**.
* Analyse the impact of **toss decisions on match results**.
* Compare CSK's performance across different **IPL teams and seasons**.

### 🔴 Long-Term — Advanced Projects

* Build an interactive **Plotly dashboard** for CSK's performance.
* Create a broader **IPL team comparison dashboard**.
* Apply **statistical analysis** to identify meaningful patterns.
* Explore **predictive modelling** for player or team performance.

This progression would take the project from **basic EDA → deeper analysis → interactive analytics → machine learning**.

---

## 🦁 Personal Note

Picked CSK for this project because they are my favourite team!

What better way to learn EDA than by analysing a team I have followed and supported for years?

From analysing seasons, wins, losses, opponents, venues, M.O.M. awards, and toss outcomes, this project was a fun way to turn my interest in cricket into a data analysis project.

**Whistle Podu! 🦁💛**

**2027 — Bring it home! 🏆💛**
