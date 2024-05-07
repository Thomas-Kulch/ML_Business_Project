# OilyGiant Mining Company ML in Business Project

The Task:

I'll be working for the OilyGiant mining company. My task is to find the best place for a new well.
    
    
Steps to choose the location:

 - Collect the oil well parameters in the selected region: oil quality and volume of reserves;
 - Build a model for predicting the volume of reserves in the new wells;
 - Pick the oil wells with the highest estimated values;
 - Pick the region with the highest total profit for the selected oil wells.
    
    
I have data on oil samples from three regions. Parameters of each oil well in the region are already known. i will build a model that will help to pick the region with the highest profit margin. I will analyze potential profit and risks using the Bootstrapping technique.
    
Conditions for this project:

 - Only linear regression is suitable for model training (the rest are not sufficiently predictable).
 - When exploring the region, a study of 500 points is carried with picking the best 200 points for the profit calculation.
 - The budget for development of 200 oil wells is 100 USD million.
 - One barrel of raw materials brings 4.5 USD of revenue The revenue from one unit of product is 4,500 dollars (volume of reserves is in thousand barrels).
 - After the risk evaluation, keep only the regions with the risk of losses lower than 2.5%. From the ones that fit the criteria, the region with the highest average profit should be selected.


In this project, I will be testing my skills on the business side of Machine Learning by:
    
- Distinguishing between offline metrics and online metrics;
- Using bootstrap to calculate confidence intervals and business metrics;
- Performing cross-validation so that conclusions about the model evaluation are more reliable.

The overall goal of this project is to determine if a machine learning model I develop will be profitable for this company.

I use the sklearn library with several modules as well as the pandas library.

### Installation Instructions

To install and run this project on your local machine:


    1. Download the zip files

    2. Open the project folder in your IDE

