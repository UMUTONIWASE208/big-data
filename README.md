here is the link to the google drive https://drive.google.com/file/d/1ci7CI3ovFHaup0NRSwmT9b-_ghr951h0/view?usp=sharing

Uber Fares Data Analysis Project 

NAMES: UMUTONIWASE Nicole 
ID:27280
UNIVERSITY:AUCA

 Project Title

Analyzing Uber Fare Patterns Using Python and Power BI

This project visualizes and analyzes Uber ride data to discover trends, peak periods, and insights using data analytics tools.*


Dashboard Overview
![Dashboard Screenshot](./screenshots/dax.png)
A snapshot of the full dashboard showing all major KPIs and graphs.

<img width="1865" height="778" alt="dax" src="https://github.com/user-attachments/assets/153fd4a0-406a-4e4a-9aa3-2c8ece44163e" />

Hourly Ride Patterns
[Hourly Pattern](./screenshots/hour.png)
Shows fare distribution by hour using clustered column chart and peak/off-peak slicer.
<img width="1856" height="1008" alt="hour" src="https://github.com/user-attachments/assets/ed6b9b60-0546-4df6-8348-3c54a1730824" />



 Monthly Ride Patterns
![Monthly Pattern](./screenshots/month.png)
Visual comparison of fares across months using bar or area chart.
<img width="1890" height="1007" alt="month" src="https://github.com/user-attachments/assets/8f5c6627-a93e-4916-a0fb-01c699f74856" />



 Busiest Ride Periods
[Matrix pattern](./screenshots/matrix.png)
Matrix showing hour vs. day_of_week with color highlighting busiest periods.
<img width="1176" height="338" alt="matrix" src="https://github.com/user-attachments/assets/bf281087-d06b-4a11-8430-2184925d54f9" />

 Seasonal Trends
![Seasonal Trends](./screenshots/year.png)
Shows long-term variation across years or time using line chart.
<img width="1907" height="1011" alt="year" src="https://github.com/user-attachments/assets/311aad0a-0041-4ea0-ae7e-62f6aa7872e8" />



 1. Introduction

This project explores Uber ride data using Python and Power BI to identify patterns, peak periods, and seasonal trends.  
The goal is to extract data-driven insights that improve ride demand forecasting and operational decisions.



 2. Methodology

Data Collection:
- Dataset: [Uber Fares Dataset](https://www.kaggle.com/datasets/)
- Source: Kaggle

 Tools Used:
- Python (`pandas`, `seaborn`, `matplotlib`)
- Power BI Desktop
- GitHub for version control and documentation

Steps Followed:
1. Load raw data into a Pandas DataFrame
2. Clean and handle missing values
3. Feature engineering: extract `hour`, `day`, `month`, `day_of_week`, `peak_time`
4. Export cleaned dataset as `uber_fares_enhanced.csv` for Power BI analysis
<img width="867" height="362" alt="input" src="https://github.com/user-attachments/assets/9d14bbdf-227b-48aa-823b-46e35284eab8" />
<img width="982" height="613" alt="loading" src="https://github.com/user-attachments/assets/e227be72-f6ce-442e-805d-9be91e617c36" />
<img width="967" height="347" alt="cleaned" src="https://github.com/user-attachments/assets/013d35b7-ac14-403d-ab54-d5ba2f38f178" />
<img width="1092" height="336" alt="image" src="https://github.com/user-attachments/assets/cbbd87aa-2cbe-43ec-b4ff-fe61acb5b005" />
<img width="516" height="82" alt="enhanced" src="https://github.com/user-attachments/assets/01558999-9ff3-461e-9a89-d827492f01f4" />

3. Exploratory Data Analysis (EDA)

- Descriptive statistics (mean, median, std deviation)
- Distribution of fares using histograms and boxplots
- Correlation between fare and trip distance
- Outlier detection using IQR method


4. Power BI Visualizations

 Hourly Ride Patterns
- Chart: Clustered column chart
- X-Axis: `hour`, Values: `fare_amount`
- Legend: `peak_time`
- Slicer: `day_of_week`
<img width="1897" height="1008" alt="date time" src="https://github.com/user-attachments/assets/de93b4a4-cefe-472c-a6b6-ee7d569e71c3" />
<img width="1903" height="1016" alt="day" src="https://github.com/user-attachments/assets/62d0cab1-4c8e-47d9-80c0-4c5029b9a149" />


Monthly Patterns
- Chart: Bar/Area chart
- X-Axis: `month`, Values: `fare_amount`
- Legend: `peak_time` or `day_of_week`

 Busiest Periods
- Matrix heatmap: `day_of_week` vs `hour` with conditional formatting
- Stacked column chart: `hour` (axis), `day_of_week` (legend)

 5. Key Findings

- Peak hours (7–9 AM, 5–8 PM) generate the highest fares
- Fridays and weekends show the highest ride volumes
- Fares increase during holiday seasons (e.g. December)
- Peak rides account for a majority of revenue

 6. Recommendations

- Increase driver availability during peak hours
- Offer off-peak promotions to balance demand
- Focus ads and campaigns on Fridays and weekends
- Use predictive scheduling in holiday seasons

 7. Project Structure
UberFares-Analysis/
├── data/
│ └── uber_fares_enhanced.csv
├── notebooks/
│ └── eda_and_cleaning.ipynb
├── visuals/
│ └── dashboard_screenshots/
├── UberFaresDashboard.pbix
├── Uber_Fares_Final_Report_Nicole.pptx
└── README.md
 
  Tools & Skills Practiced

- Python (pandas, seaborn, matplotlib)
- Data cleaning and feature engineering
- Power BI dashboard design
- Data storytelling and business insights
- Version control with GitHub






