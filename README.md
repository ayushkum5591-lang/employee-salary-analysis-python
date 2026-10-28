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

## Charts-- Salary Distribution 
<img width="1200" height="827" alt="image" src="https://github.com/user-attachments/assets/5268b0a5-97ad-453e-915d-9c8212b96cbd" />

## Experince vs Salary 
<img width="947" height="772" alt="image" src="https://github.com/user-attachments/assets/8cd2f1a7-fb03-4760-8365-c36b6e2bee24" />

## Salary vs Attandance
<img width="826" height="830" alt="image" src="https://github.com/user-attachments/assets/c76d3a9b-062c-4fe3-9964-84d73d6f9125" />



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
