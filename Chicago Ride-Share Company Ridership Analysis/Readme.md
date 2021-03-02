<DIV ALIGN=CENTER>
    <h1>Chicago Ride-Share Company Ridership Analysis</h1>
      
</DIV> 

This [presentation slide](https://github.com/amilyhuang10/MSCA_Projects/blob/main/Chicago%20Ride-Share%20Company%20Ridership%20Analysis/Presentation%20Slide.pdf) contains data overview, business intelligence report, and time series model building results and evaluation. 

### **Goal and Objective**<br>
The goal of this project is to optimize vehicle allocation with the rideshare trips and other related datasets, and give business insights and recommendations to Transportation Network Providers(TNP).

### **Datasets**
All dataset are from Nov 2018 to Dec 2019
- [Chicago Ridership](https://data.cityofchicago.org/Transportation/Transportation-Network-Providers-Trips/m6dm-c72p) 
- [Weather](https://www.ncdc.noaa.gov/cdo-web/datasets)
- Sport Events - [webscraping script](https://github.com/amilyhuang10/MSCA_Projects/blob/main/Chicago%20Ride-Share%20Company%20Ridership%20Analysis/Data%20Preprocessing%20and%20Modeling/Sport_Events_Webscraping.ipynb)
    - [2018-19 Chicago Bulls Schedule](https://www.espn.com/nba/team/schedule/_/name/chi/season/2019/seasontype/1)
    - [Chicago Bears NFL](https://www.espn.com/nfl/team/_/name/chi/chicago-bears)
    - [Chicago Cubs Baseball](https://www.espn.com/mlb/team/_/name/chc/chicago-cubs)
    - [Chicago White Sox Baseball](https://www.espn.com/mlb/team/_/name/chw/chicago-white-sox)

- [Crime](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2)
- [Census data](https://datahub.cmap.illinois.gov/dataset/community-data-snapshots-raw-data)
- [Boundaries - Community Areas](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Community-Areas-current-/cauq-8yn6)

### **Data Preparation**
Preprocessed dataset using Python, MySQL and Uchicago Research Computing Center

### **Data Modeling**
Utilized MySQL to compile data into a relational database with star schema and stored processed data for further data analysis.<br>
<img src="https://github.com/amilyhuang10/MSCA_Projects/blob/main/Chicago%20Ride-Share%20Company%20Ridership%20Analysis/EER%20Diagram.png" width="500" />

### **Model Fitting**
- [Random Forest Regressor](https://github.com/amilyhuang10/MSCA_Projects/blob/main/Chicago%20Ride-Share%20Company%20Ridership%20Analysis/Model%20Fitting/Random_Forest_Regressor_Top_Important_Features.ipynb) to find top important features that affect ridership 
- Time series models to forecast the ridership using R ([sARIMA](https://github.com/amilyhuang10/MSCA_Projects/blob/main/Chicago%20Ride-Share%20Company%20Ridership%20Analysis/Model%20Fitting/sARIMA_Model_R.pdf) and Regression with ARIMA errors)
- Tableau was used for visualization and BI Report to analyze each variables' impact on ridership

This is a team project completed in the University of Chicago MS Data Analytics
