# BikeHistory

![nycbike](https://github.com/spalakollu/BikeHistory/blob/main/images/nycbike.png)


In this dataset, we will explore the new york city bike rider's trips. The information about the rider's trip is located here. For the capstone project, we will be taking information from May 2022 to November 2022. At the time of beginning this project, data for december 2022 is not available. The dataset contains information on 676k trip riders from the last 6 months.

Citi Bike is a bike-sharing service in New York City that allows users to rent and ride bikes from a network of self-service docking stations located throughout the city. To use Citi Bike, users must first sign up for a membership, which can be purchased online or at a Citi Bike kiosk. Once they have a membership, users can check out a bike from any Citi Bike docking station using their membership card or the Citi Bike app on their smartphone. After they have finished their ride, users can return the bike to any Citi Bike docking station. Citi Bike offers a variety of membership options, including daily, weekly, and annual memberships, as well as options for tourists and students. Citi Bike also offers electric bikes, which can be rented in the same way as standard bikes.

CRISP-DM - This is the project management method used in the process to determine the findings.The below diagram explains the overall crisp-dm process.

![crispdm](https://github.com/spalakollu/BikeHistory/blob/main/images/crisp.png)

The below outline of the executed projected explains the details involved in the CRISP-DM process.
## 1) Business Understanding 
   - ### 1.1) Business Question
             Given a dataset containing information bike riders trip attributes, predict the class of biker riders. 
   - ### 1.2) Understanding of Business 
              Citibank nyc publishes the bike riders trip data every month. The data contains information which will help to answer the following questions. 
## 2) Data Understanding 
   - ### 2.1) Data collection - imports
   - ### 2.2) Data collection - Load data
   - ### 2.3) Data collection - describe data
   - ### 2.4) Data collection - data types
   - ### 2.5) Data collection - data dimensions
   - ### 2.6) Data collection - NaN values
## 3) Data Preparation
   - ### 3.1) Numerical and Categorical Attributes
   - ### 3.2) Clean Dataset by dropping rows and columns 
   - ### 3.3) Rename Columns
   - ### 3.4) Data Analysis
      - ### 3.4.1) Univariate Analysis (Descriptive Statistics)
         - ### 3.4.1.1) Response Variable
         - ### 3.4.1.2) Numerical Variables
         - ### 3.4.1.3) Categorical Variables
      - ### 3.4.2) Bivariate Analysis (Inferential Statistics)
      - ### 3.4.3) Multivariate Analysis
## 4) Data Modelling 
  - ### 4.1) Rescaling
  - ### 4.2)Transformation
      - ### 4.2.1) Encoding
      - ### 4.2.2) Response Variable Transformation
  - ### 4.3) Feature Selection
      - ### 4.3.1) Feature Slection using KNN and SFS
      - ### 4.3.2) Feature Importance using Permutation Importance
  - ### 4.4)Models 
      - ### 4.4.1) Linear Regression 
      - ### 4.4.2) Linear Regression - With Cross Validation
         - ### 4.4.2.1) Hyperparameter tuning
  - ### 4.4.3) Linear Regression - Lasso 
  - ### 4.4.4) Ridge Regression 
  - ### 4.4.5) Ridge Regression with GridSearchCV
  - ### 4.4.6) Ridge Regression - Transformed Target Regression
## 5) Evaluation 
  - ### 5.1) Metric Evaluation
      - ### 5.1.1) Identification of Evaluation Metric
      - ### 5.1.2) Rationale behind use of Evaluation Metric. 
  - ### 5.2) Interpretation of Coefficients
## 6) Deployment
## 7) Recommendations to the dealer. Details 
## 8) Next Steps
