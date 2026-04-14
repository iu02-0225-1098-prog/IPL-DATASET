# IPL-DATASET
Cricket Data Analysis Project

 

Dataset Overview

This project is based on three datasets:

- seasons.csv → Contains season-wise tournament information

- matches.csv → Includes match-level data (teams, results, venues, etc.)

- players.csv → Contains player-level performance statistics

 

Project Objective

- Analyze match outcomes and team performance

- Evaluate player statistics and contributions

- Identify trends across different seasons

- Generate insights using structured data

 

File Descriptions

 

1. seasons.csv

Key Columns:

- season – Year of the tournament

- winner – Winning team

- runner_up – Runner-up team

- player_of_series – Best player of the season

 

2. matches.csv

Key Columns:

- id – Unique match ID

- season – Season year

- team1, team2 – Competing teams

- winner – Match winner

- venue – Match location

- toss_winner, toss_decision – Toss details

- result – Match result (win/tie/no result)

 

3. players.csv

Key Columns:

- player_name – Name of the player

- team – Associated team

- runs – Runs scored

- wickets – Wickets taken

- matches_played – Total matches played

 

Data Processing Steps

1. Data Cleaning – Handle missing values, remove duplicates, standardize column names

2. Data Integration – Merge datasets using common keys

3. Data Transformation – Create derived metrics

 

Analysis Performed

- Team performance across seasons

- Season winners and trends

- Player statistics

- Toss impact on match results

- Venue-based performance

 

Key Insights

- Toss can influence match outcomes

- Some players consistently perform across seasons

- Venue conditions affect performance

 

Tools & Technologies

- Python / Pandas

- Excel / CSV

- Visualization tools (Matplotlib / Power BI / Tableau)

 

How to Use

Load datasets using Pandas and perform analysis

 

Future Improvements

- Add predictive modeling

- Build dashboards

- Integrate live data
