# Customer Churn Analysis — Subscription Business

## Project Overview
Exploratory data analysis on 7,032 telecom customers to identify 
churn drivers and provide actionable retention recommendations.

**Tools:** Python, pandas, matplotlib  
**Dataset:** IBM Telco Customer Churn (Kaggle)

## Key Findings
| Finding | Insight |
|---------|---------|
| Overall churn rate | 26.6% — 3× above healthy benchmark |
| Highest risk group | Month-to-month users churn at 42.7% |
| Critical period | 50%+ of churn happens in first 10 months |
| High-value risk | Churned users pay 21% more ($74 vs $61/mo) |

## Business Recommendations
1. **Incentivize long-term contracts** — closing the gap between 
   month-to-month (42.7%) and annual (11.3%) churn could save 
   hundreds of customers per year
2. **Build a 10-month onboarding program** — targeted check-ins 
   and value demonstrations during the critical early period
3. **Create a premium retention tier** — high-spend users need 
   more value to justify their cost

## Files
- `analysis.ipynb` — full analysis notebook
- `data/telco-churn.csv` — dataset
- `charts/` — exported visualizations

## How to Run
```bash
pip install pandas matplotlib
jupyter notebook analysis.ipynb
```