- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/NBA-Trends-Analysis.git



# NBA Trends Analysis
Analyzing changes in trends throughout the 2000-2024 NBA seasons using Python in Jupyter Notebook. This project utilizes web scraping, Python, and data analysis techniques to discover how different player stats have changed over the past 20 years in the NBA. 

*Primary tools: Jupyter Notebook, Python, Web Scraping, pandas, plotly, BeautifulSoup*

## Contents
#### Web Scraping
- [notebooks/NBA_Stats_Scraping] BeautifulSoup (bs4) and requests libraries for web scraping, pandas for data manipulation. Defines the URL for the API endpoint to fetch NBA player stats (points per game in this case). Sends a GET request and parses the response. Retrieves and processes the headers and data from the API response. Creates a temporary DataFrame with the relevant data and additional columns for year and season type. Defines columns and initializes an empty DataFrame. Iterates through different seasons and season types to scrape data. For each combination, fetches data, processes it, and appends it to the main DataFrame. Saves the aggregated data into an Excel file named nba_player_data.xlsx.

- [notebooks/NBA_Data_Analysis] Reads the Excel file containing the NBA player data. Drops unnecessary columns (RANK, EFF). Maps old team abbreviations to new ones and replaces season type names for clarity. Separates data into regular season and playoff data. Calculates additional statistics like shooting percentages, true shooting percentage (TS%), and assist-to-turnover ratio (AST/TOV). Aggregates data by year to compute team-level stats. Computes advanced metrics such as FG3A%, PTS/FGA, FG3M/FGM, FTA/FGA, TS%, AST/TOV, OREB%, DREB%, and STL/TOV.

#### Visualization
- [notebooks/NBA_Data_Analysis] Correlation matrix heatmap of various metrics using plotly.express. Histograms of player minutes per game in regular and playoff seasons. Trends of various metrics per 48 minutes and per 100 possessions. Aggregates data by year to observe changes in stats over time. Plots trends for advanced metrics per 48 minutes and per 100 possessions. Compares regular season and playoff data by calculating metrics per 100 possessions and plotting trends.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/NBA-Trends-Analysis.git
