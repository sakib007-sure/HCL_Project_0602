 ##-----Shakib Anasri-----##
 ##--------CSE--12--------##
 ---ABES Engineering College---
 
 
 # What Drives Runs? An Analysis of IPL Batting Innings

## 1. Project Overview

This project analyses IPL batting innings using Python and data analysis techniques. The objective is to understand the factors that influence runs scored by a batter.

## 2. Dataset Information

- **Dataset:** `cricket_data.csv`
- **Total innings:** 250
- **Domain:** Sports analytics
- **Data source:** Synthetic dataset generated using Claude AI

## 3. Objectives

1. Analyse the overall distribution of runs scored.
2. Study the relationship between balls faced, net practice hours, and runs scored.
3. Compare runs scored across player roles, pitch types, and innings types.
4. Identify low-scoring or at-risk innings.

## 4. Data Cleaning and Processing

- Checked for missing values.
- Removed duplicate rows.
- Handled missing `Pitch_Type` values.
- Filled missing `Net_Practice_Hours` values using the mean.
- Created three new columns:
	- `Strike_Rate`
	- `Performance_Label`
	- `Experience_Level`

## 5. Key Findings

- **Total innings analysed:** 250
- **Average runs:** 22.9
- **Highest score:** 64
- **At-risk innings (below 10 runs):** 67
- **At-risk percentage:** 26.8%
- **Average strike rate:** 114.34

## 6. Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- VS Code / Jupyter Notebook

## 7. Visualisations

The project includes charts for:

- City-wise average runs
- Average runs by pitch type
- Average runs by player role
- Top 10 highest scores
- City-wise total runs
- Balls faced vs. runs scored
- Net practice hours vs. runs scored

## 8. Conclusion

This project uses data analysis and visualisation to explore batting performance in IPL innings. It helps identify scoring patterns and low-scoring innings.

> **Note:** The dataset is synthetic. Findings demonstrate analytical patterns in this dataset and should not be treated as conclusions about actual IPL players.
