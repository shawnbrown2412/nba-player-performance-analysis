# nba-player-performance-analysis

## Project Overview

This project analyzes the factors that influence NBA player scoring performance using statistical modeling and data visualization techniques in R.

The analysis focuses on how:
- playing time,
- shooting efficiency,
- player position,
- and offensive involvement

influence points per game (PPG) across NBA players.

Using descriptive statistics, correlation analysis, visualization, and multiple linear regression modeling, the project evaluates the relative contribution of these variables to offensive production.

---

## Tools and Libraries

- R
- dplyr
- ggplot2
- readr
- broom

---

## Dataset

The project uses NBA player statistics data containing over 33,000 player observations, including:
- points per game,
- minutes played,
- shooting percentages,
- assists,
- and player position information.

Key variables analyzed include:
- `pts_per_game`
- `mp_per_game`
- `fg_percent`
- `x3p_percent`
- `ft_percent`
- `ast_per_game`

---

## Analysis Performed

The project includes:
- Data cleaning and preprocessing
- Descriptive statistical analysis
- Position-based scoring analysis
- Correlation analysis
- Data visualization using ggplot2
- Multiple linear regression modeling
- Expanded regression analysis with assists
- Model prediction evaluation
- Residual diagnostics and error analysis

---

## Key Findings

- Minutes played demonstrated the strongest positive relationship with scoring output.
- Shooting efficiency metrics positively contributed to offensive production.
- Guards tended to produce higher average scoring totals compared to several other positions.
- Assists per game were positively associated with scoring, suggesting overlap between scoring and playmaking responsibilities.
- Residual analysis indicated that additional factors such as offensive system, shot volume, and player role may also influence scoring performance.

---

## Project Structure

```text
nba-player-performance-analysis/
│
├── data/
│   └── Player Per Game.csv
│
├── nba-analysis.Rmd
├── nba-analysis.R
├── README.md
└── nba-player-performance-analysis.Rproj
```

---

## Skills Demonstrated

- Data Cleaning
- Data Visualization
- Statistical Modeling
- Regression Analysis
- Exploratory Data Analysis
- Model Evaluation
- Sports Analytics
- R Programming

---

## Future Improvements

Potential future extensions include:
- advanced predictive modeling,
- position-specific regression models,
- clustering player archetypes,
- and interactive dashboards using Tableau or Power BI.
