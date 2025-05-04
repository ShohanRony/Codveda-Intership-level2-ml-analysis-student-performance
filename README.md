# Student Performance Analysis

This repository contains a comprehensive analysis of student performance data as part of the Codveda Internship Level 2 Machine Learning tasks. The project focuses on applying various machine learning techniques to analyze and predict student academic performance.

## Project Overview

The project analyzes student data to identify factors affecting academic performance and builds predictive models using different machine learning approaches:

1. **Regression Analysis**: Predicting final grades (G3) based on previous performance and other factors
2. **Time Series Analysis**: Analyzing performance patterns over time
3. **Clustering Analysis**: Grouping students based on similar characteristics using K-Means

## Dataset

The analysis uses the `student_data.csv` dataset which contains information about students including:

- Demographic data (age, gender, address)
- Family background (education level of parents, family size)
- School-related variables (study time, absences)
- Social factors (relationships, free time)
- Performance indicators (G1, G2, G3 grades)

## Project Structure

- `Task 1 Regression Analysis.ipynb`: Linear regression model to predict final grades
- `Task 2 Time Series Analysis.ipynb`: Analysis of performance patterns over time
- `Task 3 Clustering Analysis (K-Means).ipynb`: Grouping students based on similar characteristics
- `student_data.csv`: Dataset containing student information

## Key Findings

### Regression Analysis
- Strong correlation between first period grades (G1) and final grades (G3)
- Linear regression model achieved an R-squared value of 0.6995
- Mean Squared Error of 6.1627

### Time Series Analysis
Examines how student performance changes over evaluation periods and identifies patterns in academic achievement.

### Clustering Analysis
Identifies distinct student groups based on various characteristics, helping to understand different student profiles and their academic outcomes.

## Technologies Used

- Python
- Pandas for data manipulation
- NumPy for numerical operations
- Scikit-learn for machine learning models
- Matplotlib for data visualization

## Getting Started

1. Clone this repository
2. Ensure you have the required libraries installed:
   ```
   pip install pandas numpy scikit-learn matplotlib
   ```
3. Run the Jupyter notebooks to see the analysis and results

## Author

Shohinur Pervez Shohan

## License

This project is licensed under the MIT License - see the LICENSE file for details.