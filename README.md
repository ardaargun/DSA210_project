# League of Legends Win Rate Analysis

## Table of Contents
- [Introduction](#introduction)
- [Project Motivation](#project-motivation)
- [Data Source](#data-source)
- [Research Questions](#research-questions)
- [Data Analysis](#data-analysis)
- [Potential Additional Analyses](#potential-additional-analyses)
- [Conclusion](#conclusion)
- [Setup](#setup)

## Introduction
League of Legends is a highly competitive online multiplayer game with millions of active players worldwide. To climb the ranked ladder and improve as a player, it’s essential to understand the factors influencing success in matches. This project leverages data from LeagueofGraphs to explore the relationships between gameplay variables and win rate (WR).  
Using data structures and algorithms (DSA) as a foundation, I will analyze my gameplay patterns, identify trends, and uncover actionable insights. This analysis not only aims to enhance my own performance but also serves as a data-driven exploration that other players can replicate for their improvement.

## Project Motivation
As a passionate League of Legends player, achieving a higher win rate (WR) is a critical goal for improving my performance in ranked games. This project aims to analyze gameplay data from my profile on LeagueofGraphs to identify trends, strengths, and areas of improvement. By leveraging DSA techniques, I intend to uncover tricks and issues that can lead to better decision-making during games.

## Data Source
The data for this project is collected from [LeagueofGraphs](https://www.leagueofgraphs.com), a popular platform for analyzing League of Legends player statistics. That stores up to a matches that are a year older which can not be restored from the client of the game itself. This includes parsing personal profile data, such as:
- Match histories
- Role preferences
- Champion performance
- Win/loss records

## Research Questions
1. How does win rate (WR) vary based on:
   - **Roles** (e.g., Top, Jungle, Mid, ADC, Support)?
   - **Champions** played?
   - **Side of the map** (Blue vs. Red)?
   - **Match duration** (short vs. long games)?
3. How does WR differ between solo queue and flex queue?
4. Are there any time-based patterns, such as performance varying by patch updates or the game taking place after a win/lose (streak or single games as well) ?

## Data Analysis
The analysis will proceed through several stages:
1. **Data Collection**:
   - Parsing LeagueofGraphs profile data using web scraping techniques.
   - Organizing data into a structured format for analysis.

2. **Data Cleaning**:
   - Removing duplicate or incomplete match records.
   - Standardizing data formats (e.g., timestamps, champion names).

3. **Exploratory Data Analysis (EDA)**:
   - Visualizing trends in WR across various dimensions (roles, champions, etc.).
   - Calculating descriptive statistics for key variables.

4. **Modeling and Predictions**:
   - Using statistical methods or machine learning to predict WR based on selected features.
   - Evaluating how factors such as role synergy and counter-picks influence outcomes.

5. **Insights and Recommendations**:
   - Presenting actionable findings to optimize gameplay strategies.

## Potential Additional Analyses
- **Team Dynamics**: How does WR vary with single queues or premade teams?
- **Map Objectives**: Is WR influenced by control over objectives (e.g., Baron, Dragon)?
- **Skill Growth**: Measuring WR improvement over time as a function of games played or specific training.
- **Tilt Analysis**: How does losing streaks impact WR and subsequent performances?
- **Meta Shifts**: Correlating WR trends with changes in the League meta (e.g., patch updates).

## Conclusion
This project will combine the excitement of gaming with the rigor of data analysis, providing meaningful insights into how I (and potentially other players) can improve their League of Legends performance. Through systematic exploration of the data, I aim to create a framework that can be extended to other players looking to analyze their gameplay.

## Conclusion After the Project

With this project, I was able to retrieve data from the website LeagueofGraphs for my own League of Legends account, covering matches from the past year. The aspects I chose for analysis were thoroughly examined using exploratory data analysis (EDA) and data visualization (DV) techniques. After the data analysis, a regression model was created to predict the expected win rate (WR) of future games using a logistic regression model.

Any League of Legends account can be analyzed by downloading the HTML of the given account's information from the LeagueofGraphs site and providing it to the code sequence outlined in `DSA210_project.ipynb`. The detailed explanations of the steps involved in the project, including the EDA, DV results, and the regression model, can be accessed through the following drive link, where I walk through the entire process:



