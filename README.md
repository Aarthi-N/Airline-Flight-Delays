# AIRLINE FLIGHT DELAYS

_COMPANY_: CODTECH IT SOLUTIONS

_NAME_: AARTHI N

_INTERN ID_: CT04DY248

_DOMAIN_: DATA ANALYTICS

_DURATION_: 4 WEEKS

_MENTOR_: NEELAM SANTOSH

**PROJECT DESCRIPTION**:

        The Airline Flight Delay Analysis project is a data-driven initiative aimed at understanding the factors influencing flight delays, cancellations and airline reliability in the aviation industry. Flight delays are a critical issue, causing inconvenience to passengers, financial loss to airlines and operational inefficiencies at airports. By analyzing a large dataset of files, this project provides actionable insights into delay trends, cancellation patterns and carrier performance.
         
**TOOLS AND TECHNOLOGIES USED**:
       This project primarily utilizes **PySpark**, a powerful open source distributed computing framework, for handling and analyzing large-scale flight data.The dataset used in this project is too large to be efficiently processed using traditional tools like Excel or even base Python with Pandas. Hence, PySpark was chosen for its ability to perfrom parallel processing and handle big data operations.
     ***PySpark SQL**: Used to read and transform CSV files into Spark DataFrames, allowing SQL-like operations on structured data.
     ***Pandas**: Used selectively for small-scale data manipulations and checking outputs.
     ***Matplotlib / Seaborn**: Used for visualization of delay trends, cancellations, and reliability metrics.
     ***Zipfile & OS librarie**s: Used to extract the raw dataset from compressed files.

**DATA PREPARATION**:   
       The dataset included four major files:
          1. **Airlines.csv** - containing airline codes and names.
          2. **Airports.csv** - containing airport details such as city, state, country, latitude and longtitude.
          3. **Flights.csv** - the main dataset containing detailed records of flights, including scheduled time, actual time, delaus and cancellations.
          4. **Cancellation_codes.csv** - mapping of codes to reasons for cancellation such as weather, carrier or security.

**DATA ANALYSIS**:
       The analysis was performed in multiple stages:
          1. **Yearly delay trends** - Flights were grouped by month and year to analyze how the project of delayed flights varied across the year. This highlighted peak seasons of delay and              possible seasonal impacts such as weather.
          2. **Cancellations Analysis** - The dataset was filtered for cancelled flights, and cancellations were categorized by reason. The percentage contribution of each cancellation reason
             was calculated, giving insights into weather delays were caused more by operational inefficiencies, weather conditions or air traffic.
          3. **Airline Reliabilty** - Airlines were ranked based on their percentage of on-time departures. This revealed which airlines were the most punctual and which had frequent delays. 
             This information is particularly for consumers choosing flights and for airlines to benchmark performance.
          4. **Visualization of insights** - The results were visualized using bar plots, pie charts and line graphs. For example, pie charts were used to represent the portion of cancellation reasons, while line plots displayed delay trends across months.

**KEY INSIGHTS**:
      * Flight delays showed seasonal variation, with higher delays in certain months.
      * A significant percentage of cancellations were attributable to weather and airline / carrier issues, indicating where infrastructure improvements or better planning could reduce disruptions.
      * Certain airlines consistently demonstrated on-time performance, making them more reliable compared to others.
      * Larger airports and busier routes tended to have more delays due to congestion in the air traffic system.

**CONCLUSION**:
        This project demonstrates the power of PySpark in handling and analyzing large datasets that would be challenging with traditional data processsing tools. By integrating flight, airline, airport and cancellation data, the project provided a holistic view of the flight delay problem. The insights generated can help airlines improve operational strategies, airports optimize traffic management and passengers make informed travel choices.
     
