# Airbnb-Market-Analysis
https://public.tableau.com/views/Book1_17109561781800/Dashboard1?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link

# Airbnb Market Analysis

# Project Overview
This project focuses on analyzing Airbnb data for New York City in 2019 to understand market trends, customer preferences, and pricing dynamics. The goal is to gain actionable insights into seasonal demand patterns, room type preferences, and availability, and provide recommendations to Airbnb hosts for optimizing their listings and pricing strategies.

# Team Members:

Yepuri Harsha Vardhan
Amajala Sai Ram
Sree Nikhil Velicheti
Vemula Kesavaaditya Gupta
Myneni Gyanada Chowdary
Akshitha Gopu
Isha Narwaria
Sarah Fathima Barkath

# Skills and Tools:
Programming Languages: Python (NumPy, Pandas, Matplotlib, Seaborn, Sklearn)
Data Visualization: Tableau, Gmplot
Machine Learning Techniques: Label Encoding, OneHotEncoding
Dataset: Airbnb New York 2019 from Kaggle (6.59 MB)

# Objectives:
Analyze seasonal demand patterns:

Provide actionable recommendations for Airbnb based on analysis.
Identify the most booked room types based on customer reviews.
Analyze room availability in specific locations throughout the year.
Calculate the most utilized room type during nights.
Enable users to book the desired room using interactive visualizations.

# Project Workflow

Data Collection:
The dataset used for this project was obtained from Kaggle, which contains Airbnb listings for New York City in 2019. After collecting the data, we performed the following steps:

Data Preprocessing:
Dropped unnecessary columns.
Cleaned the dataset by removing duplicates and filling missing values.
Applied transformations using LabelEncoder and OneHotEncoder for categorical variables like neighbourhood_group, neighbourhood, and room_type.

Data Cleaning:
Checked for and removed duplicates.
Filled missing values and dropped unnecessary rows and columns.
Cleaned the data and saved it for further analysis.

Exploratory Data Analysis (EDA):
Used scatterplots, bar plots, pie charts, violin plots, and box plots to understand pricing, reviews, and booking patterns.
Visualized host activity, listing performance, and price distributions across neighborhoods using heatmaps and stacked bar charts.

Data Visualization:
Using Tableau, the following visualizations were created:

Location Pricing: Map visualizations using color density to identify pricing trends.

Room Type Preferences: Bar charts showing room types with more than 250 reviews.

Seasonal Demand: Heatmaps and bubble charts to track room availability and demand.

Top Reviewers: Highlight tables identifying frequent reviewers.

Room Availability: Stacked bar charts to analyze room availability throughout the year.

Minimum Nights: Pie charts showing the average minimum nights per room type.

Booking Trends: Bubble charts showing the most utilized room types at night.

# Tableau Dashboards:

Dashboard 1: A comprehensive analysis of location pricing, room types with top reviews, and seasonal room availability.
Dashboard 2: Visualizations on seasonal demand, price optimization, and most frequently booked room types based on reviews.

# Results & Insights:

Most Preferred Room Types: Entire home/apartment room types are the most preferred by guests, followed by private rooms.

Shared Rooms: Shared rooms are the least preferred, especially at night.

Seasonal Demand: Certain room types show higher availability and booking rates during specific times of the year.

Room Pricing: Price analysis revealed significant pricing outliers, particularly for minimum night stays and certain neighborhoods.

# Actionable Recommendations:

Increase Shared Room Availability: Shared rooms have lower availability, which presents an opportunity for Airbnb to expand its market share.

Dynamic Pricing Strategies: Implement dynamic pricing to incentivize bookings for less utilized room types during off-peak periods.

Optimize for Guest Preferences: Focus on listing more entire home/apartment types, as these are the most reviewed and preferred by guests.

# Conclusion:
This project provides valuable insights into the Airbnb market, highlighting room type preferences, seasonal demand, and pricing trends. By implementing the suggested recommendations, Airbnb hosts can optimize their listings and pricing strategies to increase bookings and improve guest satisfaction.
