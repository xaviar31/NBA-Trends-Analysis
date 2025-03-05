## **NBA Trends Analysis**
This project analyzes NBA player statistics and trends over the 2000-2024 seasons using Python, SQL, and Tableau. It involves web scraping, data cleaning, and plotting trends to uncover insights about player performance, team dynamics, and the evolution of key stats over time.

---

## **🔍 Techniques Used:**
1. **Data Gathering (Web Scraping)**:  
   Python's BeautifulSoup and requests libraries were used to scrape data from the BasketballReference website. This process gathered player statistics from each season and stores them in structured CSV files for further analysis.

2. **Data Cleaning and Preprocessing**:  
   The scraped data is cleaned using **Pandas**. This step includes removing duplicates, handling missing values, and transforming the data into a usable format for analysis. We focus on columns like Player Name, Team, PPG, RPG, APG, and other performance metrics.

3. **Data Analysis**:  
   Python, with Pandas and NumPy, is used to analyze trends in NBA player stats over the years. Key analyses include examining changes in PPG, 3-point attempts, assists per game, and more. Statistical methods and visualizations are employed to reveal patterns and insights.

4. **Visualization (Work in Progress)**:  
   Tableau will be used to create an interactive dashboard that allows users to explore NBA player data and visualize trends over time.

---

## **📑 Dataset:**
The dataset contains player statistics from the 2000-2024 NBA seasons, with columns like:

- Player Name
- Team
- Points Per Game (PPG)
- Rebounds Per Game (RPG)
- Assists Per Game (APG)
- Steals, Blocks, Minutes Played, and other performance metrics

The data is scraped from Basketball Reference and cleaned for analysis.

---

## **🎯 Project Goals:**
- Track the evolution of key player statistics (e.g., PPG, 3PA, assists).
- Identify trends in player performance across the 2000-2024 seasons.
- Create an interactive Tableau dashboard that allows users to explore stats for individual players and compare trends across years.
- Visualize how different performance metrics (e.g., 3-point attempts, points scored) have changed over the years.

---

## **🔑 Key Insights:**
- **Top Players by PPG**: Points scored in the league have steadily increase over time as the game continues to advance with stronger athletes and elite scorers.
- **3-Point Attempt Trends**: To know surprise the game of basketball has changes over these past 20 years especially within the 3 point game as there is a major increase of 3 point shot attempts within the league over time.
- **Assists Per Game Trends**: Over time, specifically after the 2012-2013 NBA season, there was a noticeable increase of assists within the league and it continues to grow.

---

## **📑 Conclusion:**
This project uncovers valuable insights into the evolution of NBA player stats over the past two decades. By leveraging Python for web scraping, data cleaning, and analysis, users can explore how key performance metrics have changed over time. The project highlights significant trends in player performance and allows for an engaging, interactive experience through the Tableau dashboard.

Future improvements could involve adding more granular stats (e.g., player efficiency rating, advanced analytics) or expanding the dataset to include more teams or individual game-level data.
