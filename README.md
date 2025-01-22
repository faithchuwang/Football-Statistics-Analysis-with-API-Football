# Football Statistics Analysis with API-Football

## Project Overview

This project analyzes football statistics using data extracted from the API-Football service. The primary goal is to explore team and player performances, identify trends, and generate insights through visualization in Power BI. The project involves data extraction, preprocessing, storage in a relational database, and performing statistical analysis to support decision-making for teams, players, and league organizers.

## Data Sources

- API-Football: The primary source of data, providing information on fixtures, teams, players, and venue statistics.
- PostgreSQL Database: Used to store and manage extracted data for efficient querying and analysis.

## Tools Used

- Python: For data extraction and API interaction.
- PostgreSQL: For relational database storage and querying.
- Power BI: For data visualization and dashboard creation.
- Pandas & NumPy: For data manipulation and preprocessing.
- DAX (Data Analysis Expressions): For calculated measures in Power BI.

## Data Cleaning & Preparation

- Extracted JSON responses from API-Football were transformed into structured tables.
- Data normalization was performed to establish relationships between tables.
- Inconsistent data entries, missing values, and duplicate records were handled.
- Data was imported into PostgreSQL, ensuring referential integrity.

## Exploratory Data Analysis

- Initial data exploration was conducted using SQL queries and Python.
- Statistical summaries were generated to understand distributions and trends.
- Key metrics such as goal distributions, player performances, and team efficiencies were identified.

## Data Analysis

- Calculated total goals, average goals per game, and efficiency metrics.
- Examined home vs. away performances and their impact on match outcomes.
- Assessed team performances based on goal-scoring trends and defensive efficiency.
- Evaluated venue capacities and estimated attendance figures.

## Results & Findings

- Total Goals Scored: 1246 goals across all matches.
- Total Matches: 380 games analyzed.
- Top Scorer: E. Haaland led the goal-scoring charts.
- Most Efficient Team: Arsenal had the best goal-to-effort ratio.
- Home Wins vs. Away Wins: Home teams won 58.72% of matches, while away teams won 41.28%.
- Top Goal-Scoring Teams: Newcastle scored the highest with 76 goals.
- Least Goals Scored: Everton had the lowest tally with 51 goals.
- Highest Venue Capacity: Manchester United’s stadium holds 76,212 seats.
- Lowest Venue Capacity: Luton Town’s stadium holds 11,500 seats.
- Estimated Attendance: 11.33 million fans attended the matches.

## Recommendations

**For Teams**:

- Improve Away Performance: Strategies should be implemented to increase away win percentages.
- Enhance Goal Efficiency: Teams like Everton should analyze Arsenal’s approach to improve offensive capabilities.

**For League Organizers**:

- Boost Smaller Venue Attendance: Encourage clubs with lower capacity stadiums to expand seating and attract more fans.
- Optimize Match Scheduling: Ensure fair home and away distributions to balance team performances.

**For Players**:

- Performance Enhancement: Underperforming players should receive targeted training to improve contributions.

## References

- API-Football Documentation: https://www.api-football.com/
- PostgreSQL Official Documentation: https://www.postgresql.org/
- Power BI Documentation: https://learn.microsoft.com/en-us/power-bi/

