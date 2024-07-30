# Worker's Compensation Claims Analysis
## New York | 2018 - 2021

### Project Overview
Conducted an analysis in SQL and Python to find insights on claims data submitted to the New York State Worker's Compensation Board containing over 375,000 records. Built performance dashboard in Tableau to visualize trends related to claim frequency, severity of injury, and industry. Insights are geared towards management, underwriting, and actuarial teams.

<img width="1207" alt="NY_WC_Claims_Dashboard" src="https://github.com/user-attachments/assets/1bc50b53-fcbe-40ae-89f2-0107974f6ed6">

### Link to Tableau Dashboard: https://public.tableau.com/app/profile/paige.horn/viz/ClaimsDashboardWorkersCompNY2018-2021/ClaimsDashboard

### North Star Metrics and Dimensions
- Claims: The total number of claims submitted
- Severity: Medical Only (MED ONLY), Temporary (TEMP), Partial or Full Disability (PERMANENT), Death
- Industry: The industry classification of the operations of the insured

### Summary of Insights
#### Claims Over Time: 
There was an expected drop in claims during 2020 during lockdown. Despite this, there is still a small spike in total claims during Q3 of each year. There is a lag in claim reporting, so the total number of claims for a given year may not be known until months or years in the future.
#### Severity: 
In general, the distribution of claim severity remains stable over time.
#### Industry:
Industry is the largest differential factor in severity of claim injury.

### Recommendations:
- Work closely with the actuarial team to see how frequency of claims across industry and severity compares to the losses for these categories. 
- Dig deeper into Q3 results to see if this trend spike holds true over a longer period of time. If so, investigate if any industries stand out in regards to claim frequency during these months.

### Data Source
https://data.ny.gov/Government-Finance/Assembled-Workers-Compensation-Claims-Beginning-20/jshw-gkgu/about_data

### Limitations on this Project
This claims data is very detailed when it comes to recording area of injury and cause of injury. There are too many categories to make a meaningful comaparison between all of them at once. In order to make the data more understandable, I grouped together smaller body parts into larger sections of the body, and grouped similar causes together. The Tableau dashboard has the ability to drill down into the data so the granularity is not lost, however a different analyst may group the data together in a different way. This would lead to different conclusions from high level comparisons. The analysts of this data should work closely with management and actuarial teams to standardize these groupings if these data dimensions are regularly analyzed.

### Tools
- Excel
- SQL
- Python
- Tableau
