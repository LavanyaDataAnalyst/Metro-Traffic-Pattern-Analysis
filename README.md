# 🚦🚗 US Minneapolis Metro Traffic Pattern Analysis using Python & PowerBI

## ℹ️ Description:

* This project analyzes traffic volume patterns in the Minneapolis Metro area using Exploratory Data Analysis (EDA).
* The objective is to identify traffic trends, understand the impact of weather and holidays on traffic volume.
* It generate actionable insights for transportation planning and traffic management.
  
## 📖 Table of Contents:
>* Project Overview
>* Dataset Description
>* Data Structure
>* Tools and Technologies
>* Features Implemented
>* Key Insights
>* Recommendation
>* Conclusion
>* How to Use

## 📘Project Overview:

* Cleaning and preprocessing traffic data.
* Performing Exploratory Data Analysis (EDA).
* Analyzing traffic behavior under different weather conditions.
* Studying traffic variations during holidays and non-holidays.
* Creating visualizations and Power BI dashboards.
* Generating business insights and recommendations for traffic management.

## 🗂️ Dataset Description

* **Dataset Name:** Metro Interstate Traffic Volume Dataset
* **Source:** UCI Machine Learning Repository
* **Timeline:** 2012 – 2018
* **Dataset Updated:** 2019
* **Records:** Approximately 48,000 traffic observations
* **Target Variable:** Traffic Volume
* **Domain:** Transportation Analytics | Traffic Management | Smart City Analytics
  
## 🧱 Data Structure

* **Holiday** – Indicates whether the observation date falls on a public holiday.
* **Temperature** – Records the temperature in Kelvin.
* **Rain_1h** – Measures the amount of rainfall received within one hour.
* **Snow_1h** – Measures the amount of snowfall received within one hour.
* **Clouds_All** – Represents the percentage of cloud cover in the sky.
* **Weather_Main** – Specifies the primary weather condition (e.g., Clear, Clouds, Rain).
* **Weather_Description** – Provides a more detailed description of the weather condition.
* **Date_Time** – Contains the date and time of the traffic observation.
* **Traffic_Volume** – Represents the number of vehicles recorded during the observation period.

## 🛠 Tools & Technologies:
**Tools**

``
Google Colab |
Python |
Power BI |
GitHub |
``
  
**Python Libraries**

``
Pandas |
NumPy |
Matplotlib |
Seaborn |
Plotly Express
``

## ⚙️ Features Implemented:

* Imported and analyzed the Metro Traffic dataset.
* Performed data exploration using shape, info, describe, head, and tail functions.
* Identified and handled missing values.
* Replaced null values in the Holiday column with "No Holiday".
* Checked and removed duplicate records.
* Renamed columns for better readability.
* Converted Date_Time into datetime format.
* Performed statistical analysis using skewness and kurtosis.
* Created Traffic Density categories based on traffic volume.
* Conducted weather-based traffic analysis.
* Performed holiday vs non-holiday traffic analysis.
* Generated visualizations for traffic trends.
* Built interactive Power BI dashboards.
* Produced business insights and recommendations.
  

![Dashboard 1](Image/Dashboard%201.png)

![Dashboard 2](Image/Dashboard%202.png)


## 📈 Key Insights
* Moderate traffic density occurs most frequently in the dataset.
* Traffic volume remains relatively stable from 2012 to 2018.
* Cloudy and clear weather conditions account for most traffic observations.
* Weather has a limited impact on overall traffic flow under normal conditions.
* High traffic density is associated with higher temperatures and rainfall levels.
* Snowfall shows no strong relationship with traffic density.
* Traffic volume is significantly higher on non-holiday days.
* Most holidays experience lower traffic compared to regular days.
* Severe weather conditions such as smoke and squalls tend to reduce traffic volume.
* The analysis highlights the importance of weather and holiday factors in traffic management and planning.

## 💡 Recommendation
* Increase traffic monitoring during Moderate and High traffic density periods.
* Use weather forecasts to prepare congestion management strategies.
* Optimize signal timings during peak traffic conditions.
* Plan road maintenance during low-traffic periods and holidays.
* Develop predictive models for traffic forecasting.
* Integrate real-time traffic and weather data for proactive traffic management.
* Implement intelligent transportation systems to reduce congestion.
  
## 📈Conclusion:

* This project successfully cleaned, transformed, and analyzed the Minneapolis Metro Traffic dataset.
* The analysis revealed important traffic patterns, weather influences, and holiday effects on traffic volume.
* Through EDA, visualizations, and Power BI dashboards, valuable insights were generated to support transportation planning and traffic management.
* The project demonstrates the practical application of data analytics in solving real-world traffic challenges.
  
## ▶️ How to Use

- Clone the repository to your local machine.
- Open the project in Google Colab or Jupyter Notebook.
- Install the required Python libraries:
``
Pandas |
NumPy |
Matplotlib |
Seaborn |
Plotly
``
- Load the Metro Interstate Traffic Volume dataset.
- Run the data cleaning and preprocessing scripts.
- Execute the Exploratory Data Analysis (EDA) notebook.
- Review the generated visualizations and insights.
- Export the cleaned dataset if needed.
- Open the Power BI dashboard file (.pbix) using Power BI Desktop.
- Explore the interactive dashboard and traffic analysis reports.

## 👩‍💻 Author
 > Lavanya Madhan Raj

