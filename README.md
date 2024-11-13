# COVID-19 India Data Analysis

## Overview
This project analyzes COVID-19 data in India using Python and Pandas. The analysis includes state-wise confirmed cases and visualizations of the pandemic's spread across different regions of India.

## Dataset
The analysis uses the 'covid_19_india.csv' dataset which contains the following information:
- Date and time of record
- State/Union Territory
- Confirmed cases (Indian and Foreign nationals)
- Number of cured cases
- Number of deaths
- Total confirmed cases

## Key Features
- State-wise analysis of confirmed COVID-19 cases
- Visual representation using heat maps
- Time series analysis of case progression
- Top affected states analysis

## Requirements
- Python 3.x
- Pandas
- Google Colab (for GPU acceleration)
- Other dependencies listed in requirements.txt

## Key Findings
Based on the analysis, the top 5 most affected states are:
1. Maharashtra (105,538,919 cases)
2. Tamil Nadu (50,167,412 cases)
3. Andhra Pradesh (48,200,952 cases)
4. Karnataka (42,342,521 cases)
5. Uttar Pradesh (28,088,092 cases)

## Setup and Usage
1. Mount Google Drive in Colab:
```python
from google.colab import drive
drive.mount('/content/drive')
```
2.Load and analyze the data:
```python
import pandas as pd
df = pd.read_csv('covid_19_india.csv')
```
Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
