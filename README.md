# Rollercoaster Database Exploratory Data Analysis

## Overview
This project performs exploratory data analysis on a rollercoaster database using pandas, numpy, matplotlib, and seaborn in Python. The analysis explores various characteristics of rollercoasters around the world, including speed, height, type, year introduced, and location.

## Table of Contents
- [Requirements](#requirements)
- [Dataset Description](#dataset-description)
- [Project Structure](#project-structure)
- [Analysis Steps](#analysis-steps)
- [Key Findings](#key-findings)
- [Usage](#usage)
- [License](#license)

## Requirements
To run this analysis, you need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn

You can install these packages using pip:
```
pip install pandas numpy matplotlib seaborn
```

## Dataset Description
The dataset `coaster_db.csv` contains information about rollercoasters from around the world, including:
- Coaster name
- Location
- Status
- Manufacturer
- Year introduced
- Geographic coordinates (latitude/longitude)
- Type classification
- Opening date
- Speed (mph)
- Height (ft)
- Number of inversions
- G-force measurements

## Project Structure
The analysis follows a structured approach to exploratory data analysis:

1. **Data Loading and Initial Inspection**
   - Import necessary libraries
   - Load the rollercoaster database
   - Examine basic dataset properties (shape, head, columns, data types)

2. **Data Preparation**
   - Select relevant columns
   - Convert date columns to datetime format
   - Rename columns for clarity
   - Check for missing values
   - Remove duplicates based on coaster name, location, and opening date

3. **Univariate Analysis**
   - Analyze feature distributions
   - Create histograms, KDE plots, and value counts for key features
   - Explore the distribution of rollercoaster types

4. **Feature Relationships Analysis**
   - Create scatter plots to examine relationships between speed and height
   - Generate correlation heatmaps
   - Create pairplots for multivariate analysis
   - Analyze feature relationships categorized by coaster type

5. **Location-based Analysis**
   - Identify locations with the fastest rollercoasters (with a minimum of 10 coasters)

## Key Findings
- There is a strong positive correlation between rollercoaster height and speed
- The years with the most rollercoaster introductions can be identified
- Different types of rollercoasters have distinct characteristic patterns
- Speed and height have gradually increased over time
- Locations vary significantly in their average rollercoaster speeds

## Usage
To run this analysis:

1. Ensure you have the required libraries installed
2. Download the `coaster_db.csv` dataset
3. Open the Jupyter notebook `introduction-to-exploratory-data-analysis.ipynb`
4. Run all cells in sequence

---
