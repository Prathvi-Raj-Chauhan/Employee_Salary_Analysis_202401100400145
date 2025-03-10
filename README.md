# Employee Salary Analysis

## Overview
This project analyzes employee salaries based on experience, age, and gender, using data visualization techniques.

## Features
- Loads and processes salary data.
- Provides statistical summaries.
- Generates visualizations like salary distribution, boxplots, heatmaps, and scatter plots.

## Requirements
- Python 3
- Pandas
- Matplotlib
- Seaborn

## Usage
1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd employee-salary-analysis
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the script:
   ```sh
   python employee_salary_analysis.py
   ```
4. Upload the CSV file when prompted.
5. Analyze the generated visualizations.

## Example Dataset Format
```
ID,Experience_Years,Age,Gender,Salary
1,5,28,Female,250000
2,1,21,Male,50000
...
```

## Notes
- Converts `Salary` to numeric format.
- Skips graphs if required columns are missing.

## Conclusion
This project provides salary trend insights, useful for HR analytics and workforce planning.

