# Python_Imperial_Legacy_Hospitality_Analysis

Imperial Legacy owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

## Some of the Exploratory Data Analysis(EDA) performed on the dataset :
  ### Data Collection :
      - Data gathered from 5 csv files - dim_date, dim_rooms, dim_hotels, fact_bookings and fact_aggregated,bookings.
  ### Data Cleaning :
      - deleted the rows having invalid data for no of guests (no of guests were negative in some rows)
      - detected and removed outliers in revenue generated column by using 3 standard deviation method.
  ### Data Transformation :
      - Created new columns
      - Calculated occupancy % by dividing successful bookings from capacity.
  ### Data Visulalization :
      - Plotted bar graph of booking status.to understand the no of successful,checkedout, no show etc bookings.
      - Plotted bar graph of booking platform to understand no of bookings through various platforms.
      - Plotted bar graph of city to understand the distribution of business in various cities.
 ## Some of the insights extracted from the analysis is as follow :
  - Average occupancy% for each room category
  - Average Occupancy % per city
  - When is the occupancy better weekday or weekend
  - Month wise analysis of occupancy % in different cities.
    
