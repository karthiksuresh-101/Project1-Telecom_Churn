# Telecom_Customer_Churn_Analysis:
## Project Description
This project is an end-to-end churn analysis built using Python, SQL, and Tableau to explore customer behavior and identify churn drivers in a telecom dataset (Kaggle: Telco Customer Churn).

Unlike a typical churn project, this analysis was intentionally designed to simulate a real business environment. I asked AI to generate realistic stakeholder questions, similar to what a retention manager or product owner would ask. These questions guided the entire workflow—from EDA to SQL segmentation to dashboard design.

The result is a stakeholder-driven churn insights dashboard, highlighting churn risk, service adoption patterns, payment friction, high-value customer loss, and tenure-based churn behavior.


## Program parameters
```
input_file = str            # Path to raw Telco Customer Churn dataset (CSV)
output_file = str           # Path for cleaned dataset export
numeric_fields = []         # Numeric columns to convert (e.g., TotalCharges)
service_columns = []        # Service subscription fields used for pivot/EDA
tenure_bins = []            # Tenure grouping thresholds for lifecycle analysis
tenure_labels = []          # Labels for grouped tenure ranges
```

## How to Run
1. **Clone the repo**   
```
git clone https://github.com/<your-username>/<repo-name>.git 
cd <repo-name> 
```
2. **Install dependencies**
This project uses common Python analytics libraries:
```
pip install pandas numpy matplotlib seaborn
```

3. **Run the Script**

``Run this inside your notebook``: [Telecom_Churn_Notebook.py](Telecom_Churn_Notebook.py)








## How to Explore the Analysis

#### This project is fully contained inside one notebook:

``Code.ipynb`` : [Notebook](Code.ipynb) 


This notebook includes the complete workflow:

- Data loading
- Preprocessing (missing values, data types, feature creation)
- Exploratory Data Analysis (EDA)
- VisualizationsChurn segment analysis
- Exporting cleaned data to connect with the dashboard




## Contact / About the author

Karthik Suresh — Data Analyst | Portfolio: (link to your Notion or portfolio)
Email: (your email) — LinkedIn: (your LinkedIn)






