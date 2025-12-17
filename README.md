# **Superstore Shopping Trends Analysis: Elderly Customers**


**Data Description**: This project analyses shopping data containing customer age, gender, purchase history, and product preferences. The dataset has been cleaned and filtered to focus specifically on elderly customers (60+ years), with gender distribution as the key variable for hypothesis testing.

 ## **Hypothesis**
"More elderly men visit the superstore than elderly women."


### **Business Requirements & Context**
Business Problem:
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

### ** Project Plan:** 
**1. Planning Phase**
- Define: Hypothesis, objectives, success criteria
- Acquire: Kaggle shopping trends dataset
- Setup: Python environment with required libraries

**2. Data Processing Phase**
- Extract: Load raw CSV data
- Transform: Clean, filter, create 'Is_Elderly' column
- Load: Save cleaned data to structured folders
**3. Analysis Phase**
- Statistical: Test hypothesis with gender counts
- Visualization: Create bar, pie, area, and KDE plots
- Exploration: Analyze age distributions and patterns
**4. Delivery Phase**
- Documentation: Create README and code comments
- Presentation: Prepare visualizations and report
- Submission: Finalize and deliver assessment
### **Dataset:**
- Source: Kaggle Customer Shopping Trends Dataset
- Contains customer demographics and purchase information
###Method
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


###  AI Integration
#### AI tools were used to:
Assisted in directing clean data to a new pathway.
Support the organisation and clarity of my notebook and README.
All AI-assisted outputs were overlooked and impliemented after being reviwed.