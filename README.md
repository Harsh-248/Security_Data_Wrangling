# Security Data Wrangling

## Overview

This project focuses on data wrangling and exploratory data analysis (EDA) for cybersecurity attack data. The objective is to clean, preprocess, and analyze security-related datasets to extract meaningful insights and detect patterns in cyberattacks.

## Features

Loads and preprocesses a cybersecurity dataset.

Cleans missing values and removes duplicate entries.

Validates and filters network ports based on standard ranges.

Splits and formats time-related columns for better analysis.

Merges attack data with TCP port service information.

Visualizes missing data using missingno.

Applies statistical methods (T-tests, Chi-square tests) to analyze trends in attack data.

Generates heatmaps, scatter plots, violin plots, and strip plots to explore attack distributions.

## Installation

Prerequisites

Ensure you have Python installed along with the following libraries:

pip install pandas numpy matplotlib seaborn scipy missingno

## Usage

### Clone the repository:

git clone https://github.com/yourusername/security-data-wrangling.git
cd security-data-wrangling

### Run the Python script:

python security_data_wrangling.py


## Files

security_data_wrangling.py: Main Python script for data wrangling and analysis.

TCP-ports.csv: A dataset containing TCP port service mappings.

Cybersecurity_attacks.csv: A dataset containing cybersecurity attack records.

## Analysis Performed

### Data Cleaning:

Handles missing values in attack subcategories.

Removes invalid Source/Destination ports (out of range 0–65535).

Standardizes protocol names and attack categories.

### Exploratory Data Analysis (EDA):

Identifies most targeted IP addresses.

Finds most attacked ports.

Analyzes attack frequency by category.

Studies attack patterns across different times of the day.

### Statistical Analysis:

T-test: Compares Source vs. Destination Ports.

Chi-square test: Examines relationships between attack categories and ports.

### Visualizations:

Heatmaps: Correlation analysis and attack frequency per hour/IP.

Scatter plots: Attack duration and port distributions.

Violin/strip plots: Attack distribution by category.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

