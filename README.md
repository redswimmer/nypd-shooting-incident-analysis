# NYPD Shooting Data Analysis in R

## Overview

This project analyzes historic NYPD shooting incident data from 2006 to 2023 across New York City's five boroughs: Manhattan, Brooklyn, Queens, the Bronx, and Staten Island. The goal is to identify borough-level trends in shooting activity and explore demographic patterns related to perpetrators and victims.

The analysis includes data cleaning, transformation, visualization, and predictive modeling to understand how shooting trends have changed over time.

## Goals

- Clean and standardize NYPD shooting incident data.
- Explore shooting trends by borough, race, age group, and sex.
- Visualize borough-level monthly shooting trends.
- Train a simple linear regression model to predict shootings by year and borough.
- Reflect on potential sources of bias in the data.

## Data Source

- **NYPD Shooting Incident Data (Historic)**  
  Source: [NYC Open Data](https://data.cityofnewyork.us/api/views/833y-fsy8/rows.csv?accessType=DOWNLOAD)  

## How to Run the Analysis

1. Clone the repository (or download the project folder):

    ```bash
    git clone https://github.com/redswimmer/nypd-shooting-incident-analysis.git
    ```

2. Open RStudio and load the project folder.

3. Install required packages (if not already installed):

    ```r
    install.packages(c(
      "dplyr",
      "ggplot2",
      "lubridate",
      "corrplot"
    ))
    ```

4. Run the R Markdown file