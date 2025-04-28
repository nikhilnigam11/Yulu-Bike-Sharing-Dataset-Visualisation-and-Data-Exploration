# Yulu-Bike-Sharing-Dataset-Visualisation-and-Data-Exploration
Yulu Bike Sharing Dataset Visualisation and Data Exploration
Yulu Bike Sharing Data Analysis

👨‍💻 Author
Name: Nikhil Kumar Nigam
Role: Data Analyst Intern @ Elevate Labs
Email: nikhilnigam@engineer.com

📚 Project Overview
This project presents an in-depth analysis of the Yulu Bike Sharing Dataset as part of my Data Analyst Internship at Elevate Labs.
It explores user riding patterns, weather impact, working day influence, seasonality trends, and more to derive valuable business insights for Yulu.

📂 Dataset
Source: Keggle.

Size: 10,886 records

Features:

datetime: Timestamp

season: (1: Spring, 2: Summer, 3: Fall, 4: Winter)

holiday: (0 = No, 1 = Yes)

workingday: (0 = No, 1 = Yes)

weather: (1 to 4 levels, from clear to heavy rain)

temp, atemp, humidity, windspeed: Environmental conditions

casual, registered, count: User counts

**Key Analysis Performed**
Data Cleaning:

Checked for missing values and duplicates (none found).

Converted datetime to correct format.

**Exploratory Data Analysis (EDA):**

Analyzed distributions of registered, casual, and count.

Correlation heatmap for feature relationships.

Histograms and bar plots for weather, season, workingday analysis.

**Insights Generated:**

Clear and warm days see the highest ride volume.

Working days have significantly more rides than non-working days.

Temperature and ride count have a moderate positive correlation.

High humidity and rainfall negatively affect ridership.

Registered users contribute far more to total rides compared to casual users.

**Business Recommendations for Yulu**
Focus marketing promotions on clear weather and working days.

Develop special weekend and leisure ride offers to boost non-working day usage.

Launch seasonal campaigns during spring and winter to offset lower ridership.

Dynamic bike reallocation based on weather forecasts and working day trends.

Enhance user safety communication for rainy and humid days.

📊 Technologies Used
Python

Pandas

NumPy

Seaborn

Matplotlib

Google Colab

