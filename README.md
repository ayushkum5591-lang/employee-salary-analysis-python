# Employee Salary Analysis (Python)

Exploratory data analysis of a 150-record HR dataset: cleaning, feature engineering and visualisation of salary, experience, attendance and performance.

## Business question
How do salary, bonus, experience, attendance and performance vary across departments and gender?

## Tools
Python · Pandas · NumPy · Matplotlib · Jupyter Notebook

## Method
1. **Cleaning:** filled missing salary with the mean, missing attendance with the median, and removed records with no department.
2. **Feature engineering:** added `Total Income`, `Salary Category` (Low / Medium / High) and `Attendance Status`.
3. **Analysis:** grouped salary, bonus, experience, attendance and performance by department and gender.
4. **Visualisation:** 9 charts (bar, pie, histogram, scatter, line, box plot, subplots).

## Charts
![Salary distribution](images/salary_distribution.png)

## Files
```
employee_salary_analysis.ipynb
employee_data.csv
images/
```

## Limitations
- Sample dataset (150 rows, synthetic), so results are illustrative.
- Mean imputation is simple; a larger dataset would call for a more careful missing-value strategy.

## Author
Ayush Kumar · [LinkedIn](https://www.linkedin.com/in/ayush-kumar-214742443) · ayushkum5591@gmail.com
