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

3.Provide data driven recommendations for marketing strategies

4.Support evidence-based decision making for senior-focused initiatives

### Project Planning:
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
### Method:
1. Data Cleaning: Removed duplicates, checked for missing values
2. Feature Engineering: Created 'Is_Elderly' column (Age ≥ 60)
4. Analysis: Compared gender distribution among elderly customers
5. Visualization: Used Matplotlib and Plotly for clear presentations

**Key Variables Used**
1. Age: Customer age (used to identify elderly >60)
2. Gender: Male/Female classification
3. Purchase Amount (USD): Transaction value
4. Category Product category purchased
5. Location: Store location not specified


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
- Plotly (interactive visualizations) #please not Github does not support this, please download and run through VS Code.
- NumPy (numerical operations)

 **AI Collaboration**: This project was developed with assistance from AI tools for:
  - Code structure and optimization suggestions
  - Data visualization techniques and implementations
  - Documentation and reporting templates
  - Problem-solving and debugging support


 **Key Findings**
- Total elderly customers: 3112
- Elderly men:  542
- Elderly women: 246
- Ratio (Men:Women): 2.20

**Conclusion**
The analysis provides definitive evidence that elderly male customers (542) significantly outnumber elderly female customers (246) at the superstore. This 68.8% vs 31.2% distribution validates the initial hypothesis and establishes a clear demographic dominance that should inform strategic business decisions moving forward.

**Credits & Content used:** 

The content of this project, represent the understanding provided by Various products given by Code Institute.
Some works in the readme file have been inspired from Previous Students at Code Institute.
Some issues that I had faced has been sorted through guidence from my wonderful tutor Vasi and brilliant class members from the Data Analyst community at Code Institute.


**Acknowledegments** 

I extend my sincere gratitude to Code Institute for providing comprehensive data analytics education that formed the foundation of this project. The skills and methodologies learned throughout the course were instrumental in developing this data visualization analysis.

Special thanks to my tutor, Vasi, for their patient guidance and invaluable support in addressing numerous technical questions and challenges encountered during development.

I also wish to acknowledge my peers for their collaborative spirit, motivation, and shared insights that significantly contributed to the successful completion of this work.