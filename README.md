# Seattle-Home-Sales-Dataset-Analysis
## Overview
This project analyzes a dataset home sales in the Seattle Metropolitan area in 2014 and 2015, which consists of about 22,000 transactions. Exploratory data analysis and iterative multiple linear regression methods are used. Analysis reveals that median price for a home's zip code, interior square footage, and property grade are all relatively strong predictors of a home's sale price.  
## Business Problem
An online housing marketplace new to the Seattle housing market is facing the challenge of securing properties from residential sellers in an unfamiliar environment, in an especially competitive year for real estate. The startup must secure homes profitably and relatively quickly, as average time on the market for houses are at record lows. Our project aimed to help the team locate and easily identify the highest-value properties. 
## Data
The data, consisting of past home sales transactions in 2014 and 2015, consisted of 22,000 unique rows. Transactions were timestamped and marked by zip code in which the house is located. The dataset also inclued a number of features associated with each property, including condition, grade, square footage, number of bathrooms, number of bedrooms, and square footage of the nearest 15 neighbors. 
## Methods
Before formulating any predictive model, our team conducted some exploratory data analysis to identify some potentially promising features on which to focus our analysis. Our regression model underwent several iterations both to weed out less helpful features and to strengthen features that looked to be more strongly predictive of sale price. 
## Results
Our analysis found that grade, interior square footage, and median home sales price for the zip code of the home in question are all relatively strong predictors of future sales price. 
Our analysis led to three recommendations for the company team: 
- Prioritze offers on home with a "grade" of 7 or better
- Give preference to closings on homes with ample living space
- Pay special attention to a property's zip code when basing offers 
## Repository Structure
main
├── data
├── images
├── .DS_store
├── .gitignore                          
├── README.md 
├── Final_Shared_Doyogan_Kedo.ipynb
├── index.html                                
kedo
├── data
├── images
├── .gitignore                          
├── functions.py 
├── Alexis-Seattle-Home-Sales-Dataset-Analysis.ipynb
doyogan
├── data 
├── images
├── Eldrich-Seattle-Home-Sales-Dataset-Analysis.ipynb                     
