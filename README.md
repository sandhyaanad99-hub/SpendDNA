# SpendDNA
A Python tool that analyzes 6 month of UPI transaction data to categorize spending ,detect behavioral archetypes,and flag anomalies- built using only Pandas , Numpy, and core Python( no ML , no regex , no visualization libraries).
## Output Screenshot


![SpendDNA Report 1](report_Screenshot%201.PNG)
![SpendDNA Report 2](report_screenshot%202.PNG)



## What this project does
- Parses messy transaction data (4 date formats, 3 amount formats)
- Extracts canonical vendor names from 39+ merchant description variants
- Categorizes spending into 12 categories
- Detects spending archetypes (Shopaholic, Investor, YOLO Spender, Bengaluru Dinner-Hour Orderer, etc.)
- Flags anomalous transactions using z-score analysis
- Forecasts next month's spend per category

## Constraints
✅ Allowed: pandas, NumPy, core Python  
❌ Not used: regex, matplotlib/seaborn/plotly, scikit-learn/scipy.stats, pandas-profiling, any ML library

## How to run
1. Clone this repo or download the files
2. Open `SpendDNA_Sandhya_A.ipynb` in Jupyter or Colab
3. Ensure `Data set for DADS June.csv` is in the same folder/session
4. Run all cells top to bottom
