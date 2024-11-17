# IPL-Pie-in-the-Sky-project
This repository presents a SQL-based IPL Match Bidding app, "Pie-in-the-Sky". It offers match winner prediction, team standings, and bidder leaderboards. The database analyzes bidding, match, and player data, and dynamically calculates leaderboards based on match outcomes.

Overview
This project focuses on a comprehensive database management case study for a hypothetical IPL match bidding application called "Pie-in-the-Sky". The application facilitates user bidding on IPL matches, prediction of winners, and tracking leaderboard rankings. The project demonstrates the use of SQL to design, manage, and query a relational database, extracting valuable insights from the data.

Features
Database Schema:
Designed multiple interrelated tables to represent users, teams, matches, stadiums, bidding details, and tournament statistics.
Dynamic Point System:
Implemented a flexible point allocation system based on match outcomes and bidding accuracy.
Insights Extraction:
SQL queries to analyze match statistics, bidder performance, and leaderboard standings.
Trigger Implementation:
Demonstrates the use of SQL triggers for automating data backup.
Database Structure
The project uses a relational schema, including the following key tables:

IPL_User: Stores user credentials and roles (Admin or Bidder).
IPL_Team: Details about IPL teams, including their city and names.
IPL_Match: Tracks match schedules, results, and venues.
IPL_Bidding_Details: Records bids placed by users for various matches.
IPL_Team_Standings: Provides insights into team performance across tournaments.
Additional tables are included for players, stadiums, tournaments, and other entities to fully represent the IPL bidding ecosystem.

SQL Query Examples
This project includes queries to solve complex use cases such as:

Displaying the percentage of wins for each bidder.
Calculating the total matches played, won, and lost by each team.
Extracting top-performing players based on wickets taken.
Identifying top and bottom bidders based on points.
Analyzing trends in team performance based on match venues.

Future Scope
Add advanced analytical queries for deeper insights.
Incorporate stored procedures for repetitive tasks.
Expand the database schema to include more IPL-related data points.

Acknowledgements
This project is inspired by real-world IPL scenarios and is an excellent example of applying database management skills to solve business problems.

Connect with Me
For feedback, suggestions, or collaboration, feel free to connect via LinkedIn or GitHub. Your insights are always welcome!
