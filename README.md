# March Madness 2026

This project is intended to take advantage of my office's bracket competition to help me learn more about ways to solve the classification type of problem. I used several supervised learning models to predict the outcome of the 2026 March Madness tournament.

## Overview

The main goal of this project was to use my understanding of statistics to makeup for my lack of basketball understanding while I compete in my office's March Madness Bracket competition. Several models were trained on historic March Madness data from 2008-2024, then tested on the 2025 tournament results. The 3 best models were then selected and used to construct a bracket for the 2026 tournament. 

## Prerequisites
- R 4.3.2
- R Studio

## Installation
1. Install the required dependencies
   "install.packages(c("tidyverse","ggplot2","caret","nnet","randomForest","gbm","pROC"))
2. Download "March Madness 2026.Rmd"
3. Edit the file paths for the "away_neutral" and "matchups" variables to match the download of the two data files.

## Data

Data was pulled from the Kaggle "March Machine Learning Mania 2026". Two data files were used in this project.

1. Barttorvik Away-Neutral.csv - This csv contained all of the Barttorvik team data for away and neutral games. The data contains information        from 2008 to 2026 and was used to create a lot of team strength metrics.
2. Tournament Matchups.csv - This csv contained all of the historic matchup information from 2008 to 2025. Including the teams that played and       the score. This data was used to create the outcome variable, which was the dependent variable of interest in the models.

## Results

PDF files of the resulting brackets can be found under the main branch.

## Contact

For any questions or inquiries please feel free to reach out to my email: lyonspayton25@gmail.com.
