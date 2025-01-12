# Cricket Analytics: Batting Performance Analysis & Prediction

This repository contains an R-based project that analyzes cricket batting performance data using various statistical techniques, including data cleaning, exploratory data analysis (EDA), regression modeling, and country-based analysis. The project also predicts batting averages using a regression model and visualizes performance trends over time.

## Project Overview

The **Cricket Analytics** project leverages data from international cricket batsmen to:
- Clean and preprocess the dataset.
- Perform exploratory data analysis (EDA) on key batting performance metrics (e.g., batting average, strike rate).
- Build predictive models for batting performance, utilizing techniques like **Multiple Linear Regression**.
- Analyze and visualize batting trends across different countries.
- Predict batting averages using statistical models.
  
This analysis can help understand batting performance trends, identify top players, and offer insights into cricket analytics.

## Features

- **Data Cleaning**: Handles missing values, renames columns, and processes player statistics (e.g., batting average, strike rate).
- **Exploratory Data Analysis (EDA)**: Calculates and visualizes key statistics, including distribution of centuries, fifties, ducks, and other performance metrics.
- **Correlation Analysis**: Explores correlations between various performance metrics like runs, strike rate, batting average, and others.
- **Predictive Modeling**: Builds predictive models to estimate batting average based on historical performance data.
- **Country-Based Analysis**: Analyzes and visualizes cricket player distributions across the globe.
- **Performance Over Time**: Analyzes trends in batting average and strike rate over the years.
- **Visualization**: Provides interactive tables and visualizations for better insights using `ggplot2` and `DT`.

## Installation

To run this project on your local machine, follow these steps:

### 1. Clone this repository:
```bash
git clone https://github.com/vaishakb251/MyProjects.git](https://github.com/vaishakb251/Cricket-Analytics-Batting-Performance-Analysis-Prediction
``` 

### 2. Install the required R packages:
```r
install.packages(c("readxl", "dplyr", "knitr", "DT", "corrplot", "ggplot2", "sf", "maps", "leaps", "olsrr"))
```

### 3. Open the R script (cricket_analytics.R) and run the code in your RStudio environment or any other R platform.

#### File Structure
- cricket_analytics.R: The main R script that performs data cleaning, exploration, modeling, and visualization.
- Batsman.xlsx: Dataset containing international batsmen's performance data (ensure the file path is correctly set when running the code).
- README.md: This README file, containing project details and setup instructions.

## Data Source

The dataset used in this project is ICC Cricket Data from Kaggle ([Cricket Data](https://www.kaggle.com/datasets/mahendran1/icc-cricket). This data contains performance metrics of international batsmen, including:
```notepad  
    Matches played
    Innings
    Runs scored
    Batting average
    Strike rate
    Hundreds, fifties, ducks, and more.
```

## Usage

- **Data Cleaning**:
  - Converts numeric columns to appropriate types.
  - Handles missing values represented by "-" and removes rows with missing data.
- **Exploratory Data Analysis (EDA)**:
  - Summary statistics of key metrics.
  - Frequency distribution of centuries, fifties, and ducks.
  - Correlation matrix to identify relationships between performance metrics.
- **Predictive Modeling**:
  - Multiple Linear Regression models are built to predict batting averages based on historical performance metrics.
- **Country-Based Analysis**:
  - Analyzes and visualizes cricket player distribution by country on a world map.
- **Performance Over Time**:
  - Creates a performance overview across different years and visualizes trends in batting average and strike rate.

## Contributions

Contributions are welcome! Feel free to fork the repository, submit issues, or open a pull request. If you have any suggestions, enhancements, or questions, don't hesitate to contact me.
