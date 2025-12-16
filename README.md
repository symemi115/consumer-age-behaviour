# Superstore Shopping Trends Analysis: Elderly Customers

 Hypothesis
"More elderly men visit the superstore than elderly women."
 Project Overview
This project analyzes customer shopping trends data to test whether elderly men (60+) visit the superstore more frequently than elderly women.

Dataset
- Source: Kaggle Customer Shopping Trends Dataset
- Contains customer demographics and purchase information
 Method
1. Data Cleaning: Removed duplicates, checked for missing values
2. Feature Engineering: Created 'Is_Elderly' column (Age ≥ 60)
4. Analysis: Compared gender distribution among elderly customers
5. Visualization: Used Matplotlib and Plotly for clear presentations

 Key Findings
- Total elderly customers: 3112
- Elderly men:  542
- Elderly women: 246
- Ratio (Men:Women): 2.20

Conclusion


Files
- `shopping_analysis.ipynb`: Main analysis code
- `elderly_gender_interactive.html`: Interactive visualization
- `requirements.txt`: Python dependencies

How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the Jupyter notebook or Python script
3. View visualizations in the notebook or generated HTML file

Technologies Used
- Pandas (data manipulation)
- Matplotlib (static visualizations)
- Plotly (interactive visualizations)
- NumPy (numerical operations)
