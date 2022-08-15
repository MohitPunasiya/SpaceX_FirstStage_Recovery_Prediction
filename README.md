# SpaceX_Falcon9_FirstStage_Recovery_Prediction
## Context
I did this capstone project under IBM Data science series offered by coursera, SpaceX provides rocket launching facility at much lower prices than their market competition, This is because of reusability of first stage of Falcon 9 Rocket. The successful landing of the first stage depends on factor such as payload mass, launch site, orbit its launched to , time of the year etc.This project aims to explore data driven  approches to predict the success of first stage landing (or reusabiility)
This predictive model can be useful in decision making for those who are on other end of buisness
## Methodology 
* Collecting rocket launch data using SpaceX API and webscrapping from wiki pedia pages
* Performing data wrangling : Missing data impurations and one hotbit encoding
* Exploratory data analysis  by visualisation using plotly dash
* Interactive visual analsis using Folium and Plotly Dash 
* Training logistics regression, SVM, decision tree and Knn models and achieved best accuracy of 94 % by support vector machine (The model accuracy can be found in prediction_model notebook)


## File Structure
* 1_DataCollection : this file has data collection methodology using API
* webscrapping : this contains use of scrapper to extract data from html pages
* DataWrangling : This file contains codes regarding data wrangling, and some feature engineering
* EDA_FeatureEngg : This File contains exploratory data analysis
* EDA_SQL : This file has SQL queries and got some important information extraction
* pholium_launch_site_location : excuse me ! for wrong spelling of Folium, this file has eda using maps
* PlotlyDash_for_Project : codes for using plotly dash, interactive executive dashboard
* Prediction_model : it has all the tested models and their validation
## Author 
* Mohit
