# NBA Trends Data Analysis

## Overview
This project focuses on analyzing NBA player statistics from the 2000-2024 seasons. It involves web scraping, data cleaning, and statistical analysis to explore trends in player performance over time.

## Data Collection
The dataset is created by scraping Basketball Reference for player statistics, including per-game averages for various metrics. The raw data is processed and cleaned to ensure consistency and accuracy.

## Data Processing
Using Python, the dataset is structured to include:
- **Season Information**: `season_start_year`, `Season_type` (Regular Season/Playoffs).
- **Player & Team Identifiers**: `PLAYER_ID`, `PLAYER`, `TEAM_ID`, `TEAM`.
- **Performance Metrics (Per Game Averages)**: `PTS`, `REB`, `AST`, `STL`, `BLK`, `TOV`, `FG_PCT`, `FG3_PCT`, `FT_PCT`, and other shooting and rebounding stats.

## Tools & Technologies
- **Python (Pandas, BeautifulSoup, Matplotlib)** – Used for web scraping, data cleaning, and initial analysis.
- **Jupyter Notebook** – Main environment for processing and structuring data.
- **Excel/CSV** – Format for storing the cleaned dataset.

## Future Work
- Further trend analysis and deeper statistical insights.
- Exploring additional visualizations and predictive modeling.
- **Tableau Dashboard (Work in Progress)** – Creating an interactive dashboard for data exploration.
