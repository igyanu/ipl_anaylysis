# 🏏 IPL Analysis Dashboard (2008–2024)

## 📌 Project Overview

This Power BI dashboard provides a comprehensive analysis of the Indian Premier League (IPL) from 2008 to 2024. The dashboard enables users to explore team performance, season-wise statistics, player achievements, title winners, batting records, bowling records, and match outcomes through interactive visualizations.

The IPL, launched in 2008, has grown into one of the world's most popular T20 cricket leagues, making it an excellent dataset for sports analytics and business intelligence projects. 
---

## 🎯 Objectives

- Analyze IPL trends from 2008–2024.
- Identify the most successful teams and players.
- Compare batting and bowling performances.
- Track season-wise winners and awards.
- Provide interactive insights using Power BI.
---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- *CSV Dataset**
- **Data Modeling & Visualization**
---

## 📊 Dashboard Features

### 1. Main Dashboard

Provides an overview of IPL history from 2008–2024.

#### Key Metrics
- Total Matches Played
- Highest Team Score
- Lowest Team Score
- Number of Super Overs
- Win Percentage while Batting First vs Bowling First

#### Team Analysis
- IPL Title Winners by year
- Season-wise IPL Champions
- Overall Tournament Statistics
---

### 2. Season Analysis

Analyze any individual IPL season.

#### Insights Included
- IPL Champion Team
- Orange Cap Winner
- Purple Cap Winner
- Matches Played
- Total Sixes Hit
- Run Distribution
- Team-wise Win Count

Users can filter any season and instantly view the corresponding statistics.

---

### 3. Player Analysis

Interactive player comparison dashboard.

#### Batting Statistics
- Total Runs
- Strike Rate
- Centuries
- Player of the Match Awards

#### Bowling Statistics
- Total Wickets
- Economy Rate
- 4-Wicket Hauls
- Player of the Match Awards

Users can select any batsman or bowler from the dropdown menu and analyze their performance.
---

## 📈 Key Insights

### Team Performance
- Chennai Super Kings and Mumbai Indians are among the most successful franchises in IPL history with multiple championships.
- Kolkata Knight Riders emerged as the 2024 IPL champions. :contentReference[oaicite:2]{index=2}

### Match Trends
- Teams chasing targets have historically maintained a slight advantage over teams batting first.
- Super Overs remain relatively rare across IPL seasons.

### Player Performance
- The dashboard highlights top-performing batsmen and bowlers across multiple seasons.
- Users can compare strike rates, wickets, economy rates, centuries, and awards.

---

## 📂 Dataset Information

**Source:** IPL Match & Player Statistics Dataset

### Data Coverage
- Seasons: 2008 – 2024
- Match Results
- Team Statistics
- Batting Records
- Bowling Records
- Tournament Awards
---

## 🔍 Business Intelligence Concepts Used

### Data Modeling
- Star Schema Design
- Relationships between matches, players, teams, and seasons

### DAX Measures
Examples:

```DAX
Total Matches = COUNT(Matches[match_id])

Total Sixes = SUM(Batting[sixes])

Total Wickets = SUM(Bowling[wickets])

Win Percentage =
DIVIDE(
    [Matches Won],
    [Total Matches]
)
```

---

## 🚀 Skills Demonstrated

- Data Cleaning & Transformation
- Data Modeling
- DAX Calculations
- Sports Analytics
- KPI Development
- Interactive Dashboard Design
- Business Intelligence Reporting
- Data Visualization

---

## 📁 Repository Structure

```
IPL-Analysis-Dashboard/
│
├── README.md
├── IPL_Analysis.pbix
├── dataset/
│   ├── IPL_Data.csv
│   └── deliveries.zip
└── dashboard screenshots/
    ├── kohli in 2024.png
    ├── purple_cap.png
    ├── win by toss decision.png
    └── winner in  2023.png
```

---

## 📬 Contact

If you found this project interesting or have suggestions for improvement, feel free to connect with me.

**Created by:** Gyanendra Yadav

---

⭐ If you like this project, don't forget to star the repository.
