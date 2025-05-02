#  Customer Churn Analysis – Telecom Industry
This project identifies the factors contributing to customer churn in a telecom dataset using Python, SQL, Tableau, and Power BI. It includes data cleaning, visualization, predictive modeling, and interactive dashboards.
## Objective
To reduce churn by identifying patterns and building a predictive model that helps telecom businesses retain high-value customers.
## Dataset
- **Source**: Synthetic telecom customer dataset
- **Records**: 7,043 customers
- **Key Features**: Gender, SeniorCitizen, Contract, MonthlyCharges, Tenure, InternetService, StreamingTV, and Churn
- **Added Feature**: `ProfitSegment` (Low / Medium / High) based on `MonthlyCharges`

---

##  Tools & Technologies
- **Python**: Data cleaning, EDA, ML modeling (`pandas`, `matplotlib`, `seaborn`, `sklearn`)
- **MySQL**: SQL aggregation and querying
- **Tableau**: Interactive dashboards
- **Power BI**: Business reporting visuals

---

##  Key Visuals
### Python Plots:
- Churn Distribution
- MonthlyCharges vs Tenure
- Churn by Profit Segment

### Tableau Dashboards:
- Churn by Contract & Profit Segment
- Churn Heatmap: Internet vs Streaming Services
- Interactive filters: Gender, InternetService, Contract

### Power BI:
- Pie Chart: Churn Distribution
- Bar Chart: Churn by Contract
- Slicers: Gender, Contract, InternetService

---

## Machine Learning
- **Model**: Random Forest Classifier
- **Data Prep**: One-hot encoding, null handling, type casting
- **Explainability**: SHAP for feature importance (Tenure, Contract, MonthlyCharges were top drivers)

---

##  Business Insights
- Highest churn: Month-to-month customers
-  New users (low tenure) = higher churn risk
-  High-profit segment also shows churn → need loyalty offers
-  Streaming and internet service usage impact churn behavior

---

##  Deliverables
- `Customer_Churn_Analysis.ipynb`
- `CustomerChurn_Final_Cleaned.csv`
- EDA plots (PNG)
- `Churn_Report.pdf` and `Churn_Detailed_Report.pdf`
- `Customer_Churn_Presentation.pdf`
- Tableau Workbook (`.twbx`) 
- Power BI Dashboard (`.pbix`) 

---

##  How to Run
1. Clone this repository
2. Open and run `Customer_Churn_Analysis.ipynb` in Jupyter
3. Use the cleaned CSV in Tableau/Power BI
4. Review PDFs and dashboards for insights and presentation

---

##  Date Completed
**May 2025**

---

## Author
Satyam Shaw
_Data Science Portfolio Project_
