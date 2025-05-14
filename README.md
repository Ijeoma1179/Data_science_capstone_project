#  Chinook Database Project: Sales Analysis and Predictive Modeling

This project is two parts. Part one is the analysis of Chinook database while part two is the  Prediction of  Customer Lifetime Value (CLV) in the Chinook Database. The goal of this project is to build a machine learning model that predicts Customer Lifetime Value (CLV) based on historical sales, customer demographics, and transaction patterns. the visualization was done in the notebook as well as power BI. 
`final project on chinook latest.ipynb` - Contains full data analysis including visualizations and insights from the Chinook database.
- `Chinook model.ipynb` - Includes the development of a machine learning model for predicting sales or customer behavior.

##  Project Structure

- `final project on chinook latest.ipynb`: Exploratory Data Analysis (EDA) and sales trends extraction
- `Chinook model.ipynb`: Feature engineering, model building, and evaluation using regression models
- `chinook.db`: The SQLite database containing music store records
- `PowerBI/`: Folder containing Power BI visualizations and screenshots

##  About the Chinook Database

The [Chinook Database] is a sample database representing a digital media store, including:

- Customers
- Invoices and Invoice Items
- Artists, Albums, Tracks
- Employees
- Genres and Media Types

  
## Project Objectives
**Part one:**##:
Sales Analysis with SQl and Power BI
T•	To Identify artists with the highest sales and analyze their sales trends over time. 
•	To  Segment customers based on purchase behavior and identify key characteristics of high-value customers. 
•	To determine the most popular music genres and analyze the change in genre popularity over different periods. 
•	To analyze monthly and yearly sales trends, including seasonal effects and significant sales events. 
•	To calculate the lifetime value of customers based on their purchase history and provide recommendations for improving customer retention. 
•	To perform association rule mining to find common combinations of tracks or albums purchased together.
## Power BI Visuals :

You can download and open the full interactive dashboard here:

https://github.com/Ijeoma1179/Data_science_capstone_project/blob/main/Chinook%20PowerBI%20dashboard%20latest.pbix


**Part Two**:  Predictive Modeling
1. To examine the structure and relationships in the Chinook database using SQL queries and Identify the key tables and attributes needed to calculate Customer Lifetime Value (CLV). 
2. To Use SQL to extract and join relevant data 
3. To create features from the extracted data 
4. Data Preprocessing 
5. Model Building
6. To evaluate the model using metrics such as RMSE or R^2.
7. To save the model for future purposes
###  Goal

Build regression models to predict the CLV 

### Steps

1. **Data Preparation**
   - Extract relevant features: customer country, invoice line count, genres purchased, etc.
   - One-hot encode categorical features
   - Feature selection using correlation

2. **Modeling**
   - Linear regreggion
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - Evaluation metrics: MSE (Mean Squared Error), R² Score

4. **Train-Test Split**
   - 90% training, 10% testing split due to dataset size

5. **Evaluation**
   - Compare model predictions to actual invoice amounts
   - Assess model performance using:
     - `mean_squared_error()`
     - `r2_score()`

## Getting Started

To run these notebooks, you will need:

-   **Jupyter Notebook or JupyterLab**: These are interactive development environments for working with notebooks. You can install them using pip:
    ```bash
    pip install notebook jupyterlab
    ```
-   **Python Libraries**: The analysis likely uses various Python libraries for data manipulation, analysis, and visualization. Common libraries include:
    -   pandas
    -   numpy
    -   matplotlib
    -   seaborn
    -   SQLAlchemy (if connecting directly to the database)
    -   SQLite
    -   Power BI Desktop

## git clone 
https://github.com/Ijeoma1179/Data_science_capstone_project.git
## Insights
Top genres contributing to revenue include Rock, Latin, and Metal

Predictive models were able to explain up to ~80% of invoice amount variation using engineered features
## Next Step 
Deploy the saved model 
## Author 




    -   
