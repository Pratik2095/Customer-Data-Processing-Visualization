# 📊 Customer Data Processing & Visualization

**Customer Data Pre-processing & Data Visualization** using Python (Pandas, Seaborn, Matplotlib).

## Files
- `Customer Data Processing_Final_Assignment.ipynb` — main notebook (code + outputs)
- `Customer Data Processing_Final_Assignment.pdf` — exported report
- `acw_user_data.csv` — input data (if allowed to share)
- `Processed.json`, `retired.json`, `employed.json`, `remove_ccard.json`, `Commute.json`
- `plots/` — saved figures (PNG)

## Tasks covered
**Data Processing**
1) Read CSV  
2) Convert flat → nested JSON  
3) Clean `Dependants` (empty → `0`) → `Processed.json`  
4) Split retired vs employed → `retired.json`, `employed.json`  
5) Flag cards with >10 years start→expiry → `remove_ccard.json`  
6) Salary-per-mile of commute → sort & save → `Commute.json`

**Data Visualization**
- Mean salary, median age  
- Histograms (age bin width=5, dependants clean-up, age by marital status)  
- Relplots (commute vs salary, age vs salary, age vs salary by dependants)  
- All figures saved in `/plots`

