# 🏏 IPL Data Analysis Using Python

## 📌 Project Overview

This project analyzes historical **Indian Premier League (IPL)** cricket data to uncover insights about team performance, player achievements, and match outcomes. Using Python and data analysis libraries, the project explores trends in match results, batting performance, bowling statistics, and seasonal scoring patterns.

The objective is to demonstrate data analysis skills such as data cleaning, aggregation and creating meaningful visualizations.

---

## 🎯 Objectives

* Identify the most successful IPL teams based on match wins.
* Analyze the impact of toss decisions on match results.
* Find the top run scorers in IPL history.
* Identify bowlers with the highest wicket counts.

---

## 🛠 Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook / VS Code**

---

## 📂 Dataset

The project uses two IPL datasets:

### 1️⃣ matches.csv

Contains match-level information.

Columns include:

* `id` – Match ID
* `season` – IPL season year
* `team1`, `team2` – Teams playing
* `toss_winner` – Team that won the toss
* `toss_decision` – Bat or field decision
* `winner` – Match winner
* `venue` – Match venue

### 2️⃣ deliveries.csv

Contains ball-by-ball match data.

Columns include:

* `match_id` – Match identifier
* `over` – Over number
* `ball` – Ball number
* `batter` – Batsman name
* `bowler` – Bowler name
* `batsman_runs` – Runs scored by batsman
* `total_runs` – Total runs in that delivery
* `dismissal_kind` – Type of dismissal

---

## 📊 Analysis Performed

### 1️⃣ Most Successful Teams

Calculated total match wins for each team to identify the most successful franchises in IPL history.

### 2️⃣ Toss Impact Analysis

Analyzed how often the team winning the toss also wins the match.

### 3️⃣ Top Run Scorers

Identified the top batsmen based on total runs scored across all seasons.

### 4️⃣ Leading Wicket Takers

Analyzed bowling performance by counting total wickets taken by bowlers

---

## 📈 Key Insights

* Certain teams consistently dominate IPL seasons with higher win counts.
* Toss advantage does not always guarantee a match victory.
* A few batsmen dominate run-scoring across multiple seasons.
* Top bowlers contribute significantly to match outcomes through wicket-taking ability.
  
---

## 📁 Project Structure

```id="2khe6m"
IPL-Data-Analysis/
│
├── ipl_analysis.ipynb
├── matches.csv
├── deliveries.csv
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository.
2. Install required Python libraries:

```id="j64vym"
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook:

```id="1o07py"
ipl_analysis.ipynb
```

4. Run all cells to reproduce the analysis and visualizations.

---

## 💡 Skills Demonstrated

* Data cleaning and preprocessing
* Data aggregation using Pandas
* Dataset merging and transformation
* Exploratory Data Analysis (EDA)
* Data visualization and storytelling
* Sports analytics

---

## 👨‍💻 Author

**Durga Prasad Keshri**
Aspiring Data Analyst | Python | SQL | Excel | Data Visualization
