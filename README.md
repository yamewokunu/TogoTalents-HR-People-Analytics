# TogoTalents — Employee Retention Analysis

## Objective

Explore employee departures and identify patterns to guide further retention analysis.

## Data and Methods

This project uses a synthetic HR dataset with 59 records after removing one duplicate.

Data preparation in Python with Pandas included standardizing categories, converting numeric fields, and replacing selected missing or invalid values with medians.

Exploratory analysis compared departure status by department, satisfaction, salary, and overtime. The results are presented in dashboard visualizations.

## Key Findings

- **Employee departures:** 19 of 59 employees (32.2%) had left.
- **Departments:** Finance and Human Resources had the highest departure proportions, at 45.45% each.
- **Satisfaction:** Employees who left averaged 2.16/5, compared with 3.45/5 among those who stayed.
- **Salary:** Median monthly salary was $4,300 among employees who left, compared with $4,750 among those who stayed.
- **Overtime:** The departure proportion was 46.43% among employees working overtime, compared with 19.35% among those without overtime.

## Recommendations

In a real organization, these patterns would support reviewing workload and overtime, gathering employee feedback, and assessing compensation for similar roles.

Finance and Human Resources should be examined more closely. Test and monitor proposed actions before evaluating their effectiveness.

## Limitations

The dataset is small and synthetic. Results describe associations and do not establish why employees left.

Median imputation may affect comparisons, and one employee identifier remains duplicated across different records.

Without a defined observation period, the 32.2% figure represents the proportion recorded as having left, not an annual turnover rate.

## Tools Used

Python, Pandas, Matplotlib, Google Sheets, and Looker Studio.

## Project Files

- [Python Notebook](TogoTalents_Prepare.ipynb)
- [Employee Retention Dashboard](TogoTalents_Dashboard.png)
- [Interactive Dashboard](TogoTalents_Employee_Retention_Dashboard_Interactive.html)

## AI-Assisted Development

AI assistance supported Python coding, debugging, and dashboard development. My contributions included defining analytical objectives, reviewing the results, making analytical decisions, and interpreting findings.
