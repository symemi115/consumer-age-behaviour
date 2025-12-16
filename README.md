# **Superstore Shopping Trends Analysis: Elderly Customers**

 ## **Hypothesis**
"More elderly men visit the superstore than elderly women."

## Project Overview
This data analysis project investigates shopping patterns among elderly customers (65+) at a major superstore. The study focuses on testing whether elderly men visit the superstore more frequently than elderly women, using data science techniques to derive actionable business insights.

**Business Requirements & Context
Business Problem:**
Understanding customer demographics is crucial for:
1. Targeted Marketing: Efficient allocation of marketing resources
2. Inventory Management: Stocking age and gender-appropriate products
3. Store Layout Optimization: Creating comfortable shopping environments
4. Customer Experience: Tailoring services to dominant customer segments
5. Revenue Optimization: Focusing on high-potential customer groups

#### **Business Objectives:**
1.Identify the dominant gender among elderly shoppers
2.Understand potential revenue implications
3.Provide data-driven recommendations for marketing strategies
4.Support evidence-based decision making for senior-focused initiatives

**Dataset:**
- Source: Kaggle Customer Shopping Trends Dataset
- Contains customer demographics and purchase information
 Method
1. Data Cleaning: Removed duplicates, checked for missing values
2. Feature Engineering: Created 'Is_Elderly' column (Age ≥ 60)
4. Analysis: Compared gender distribution among elderly customers
5. Visualization: Used Matplotlib and Plotly for clear presentations
**
Key Variables Used**
1. Age: Customer age (used to identify elderly >60)
2. Gender: Male/Female classification
3. Purchase Amount (USD): Transaction value
4. Category Product category purchased
5. Location: Store location not specified



 **Key Findings**
- Total elderly customers: 3112
- Elderly men:  542
- Elderly women: 246
- Ratio (Men:Women): 2.20

**Conclusion**
Primary Finding: Elderly Men represent the majority of elderly shoppers


**Files**
- `shopping_analysis.ipynb`: Main analysis code
- `requirements.txt`: Python dependencies

**How to Run**
1. Install dependencies: `pip install -r requirements.txt`
2. Run the Jupyter notebook or Python script
3. View visualizations in the notebook

**Technologies Used**
- Pandas (data manipulation)
- Matplotlib (static visualizations)
- Plotly (interactive visualizations)
- NumPy (numerical operations)
