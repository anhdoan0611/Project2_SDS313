# Project2

##Overview
This repository contains an analysis of Premier League Player Statistics from All Seasons, exploring players’ trends, performance across various metrics.

##Data Source
- The data was downloaded from [kaggle](https://www.kaggle.com/datasets/rishikeshkanabar/premier-league-player-statistics-updated-daily/data)
- **Description**: The cleaned dataset contains the following variables:
  - **Name**: Name of the player
  - **Jersey Number**: Player's jersey number
  - **Club**: Club to which the player belongs
  - **Position**: Player's field position (e.g., Forward, Midfielder, Defender, Goalkeeper)
  - **Nationality**: Player's nationality
  - **Age**: Player's age
  - **Appearances**: Number of matches played by the player
  - **Wins**: Total matches won while the player was on the field
  - **Losses**: Total matches lost while the player was on the field
  - **Goals**: Total goals scored by the player
  - **Assists**: Total assists provided by the player
  - **Goals Contribution**: Sum of goals and assists, indicating the player's total contribution to scoring
  - **Class**: Player category based on appearances (Rookie: Less than 50 Appearances, Regular: More than 50 but Less than 100 Apps, Veteran: At Least 100 Apps)

##Analyses Conducted
- **Univariate Analyses**:
  - **Goals Contribution**
  - **Player's Age**
  - **Player's Position**
  - **Player's Class**
- **Multivariate Analyses**:
  - **Player's Age vs Player's Position**
  - **Total Goals Scored vs Total Assists Made by Class**
  - **Matches Won vs Matches Loss by Big 6 Clubs (Arsenal, Chelsea, Liverpool, Manchester United, Manchester City, Tottenham Hotspur)**
  - **Player's Age by Club**
 
##Instructions for Reproduction:
- Download the dataset and make sure it is available in the working directory
- Open R or RStudio and Install "stringr", "ggplot2", and "dplyr" packages
- Run the R script
  
