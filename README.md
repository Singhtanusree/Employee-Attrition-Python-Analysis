# Employee Attrition Analysis (Pandas + Matplotlib)

## Business Question
Which department and recruitment source have the highest voluntary attrition, and is it driven by low engagement/satisfaction or by pay — so HR can prioritize where to focus retention efforts first?

## Tools Used
- **Python** — pandas (data cleaning, feature engineering, aggregation)
- **Matplotlib** — data visualization
- Jupyter Notebook

## Dataset
Synthetic HR dataset (`employee_attrition_data.csv`) containing employee demographics, department, recruitment source, engagement/satisfaction scores, salary, tenure, and exit details.

## Key Findings
- **Operations has the highest attrition (37%)** — nearly double Marketing's rate (20%), and well above the company average (~26%).
- **Employee Referral and Indeed hires churn the most** (32.9% and 30.3% respectively), despite referrals being the channel typically considered most "trusted."
- **Job satisfaction, not salary, is the stronger attrition signal** — leavers report satisfaction of 2.53/5 vs. 3.23/5 for stayers, while the salary gap between the two groups is small (~₹4,400/month).
- **Top exit reasons are growth-related, not pay-related** — "No Growth" (27%) and "Better Opportunity" (21%) together account for nearly half of all exits, compared to just 11% citing "Higher Salary Elsewhere."

## Business Recommendations
1. **Prioritize Operations for a retention review** — its 37% attrition is the single largest contributor to overall churn; bringing it down to the company average would meaningfully cut total attrition.
2. **Audit the Employee Referral pipeline** — despite its reputation, it has the highest attrition of any recruitment source. Interviewing a sample of recently-referred leavers could surface expectation mismatches set during hiring.
3. **Invest in visible growth paths, not just pay** — since growth-related reasons dominate exits, career-pathing and internal mobility programs are likely to have more retention impact than compensation adjustments alone.

## Repository Structure
```
├── notebooks/
│   └── employee_attrition_analysis.ipynb
├── data/
│   └── employee_attrition_data.csv
├── images/
   ├── attrition_by_department.png
   ├── attrition_by_recruitment_source.png
   ├── count_of_emp_by_exit_reason.png
   └── dashboard.png



