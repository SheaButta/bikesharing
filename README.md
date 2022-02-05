# bikesharing


## Overview 
The purpose of this project is to convince a group of investors that a bike-sharing program in Des Moines is be a solid business proposal.  My client recently took a trip to New York City and was able to experience a company named Citibike which is thriving in a bike-sharing business.  My client is interested in starting a similar business in Des Moines; however, they have no idea how to win over a group of investors.  

I was hired to do professional research and analysis; moreover, produce visualizations that will tell the best story as to why a bike-sharing business would thrive in Des Moines.  I decided to collect some data from Citibike in New York to generate visualizations to convince my client and the investors that a bike-sharing is a solid investment.

As always, my analysis followed the data analysis principles of (1) Determine the number of rows and columns; (2) Data types used; and (3) Is the data readable?

__Deliverables:__
- Change Trip Duration to a Datetime Format (Client)
- Create Visualizations for the Trip Analysis (Client)
- Create a Story and Report for the Final Presentation (Client/Investors)


## Resources
The resouces used for research and analysis included;
- Jupyter Notebook
- Pandas
- Tableau
- CSV data for research/analysis (201908-citibike-tripdata.csv)


## Results
The CSV data was reviewed and is readable.  There is one column named "Tripduration" which has a data type of int.  This data is required for my analysi so I decided to change the column data type from __int__ to __datetime__.  Changing the data type to datetime will report the "Tripduration" as __"Hours:Minutes:Seconds, (00:00:00)"__.


#### Deliverable 1: Change Trip Duration to a Datetime Format (Client)

This client deliverable required me to use Jupyter Notebook and load the CSV file into a Pandas DataFrame.  Once loaded into the DataFrame, the __Tripduration__ data type is changed.
    
    1.1: Datatypes of all columns
    
    ![](https://github.com/SheaButta/plotly_deployment/blob/main/static/images/Dashboard.PNG)


    1.2: Change datatype of Tripduration to datetime
    
    ![](https://github.com/SheaButta/plotly_deployment/blob/main/static/images/Dashboard.PNG)
    

    1.3: Tripduration datatype after change
    
    ![](https://github.com/SheaButta/plotly_deployment/blob/main/static/images/Dashboard.PNG)


    1.4: Tripduration datatype after change
    
    ![](https://github.com/SheaButta/plotly_deployment/blob/main/static/images/Dashboard.PNG)

    1.5: Create new CSV file after changing datatype
    
    ![](https://github.com/SheaButta/plotly_deployment/blob/main/static/images/Dashboard.PNG)
    

#### Deliverable 2: Create Visualizations for the Trip Analysis (Client)

This client deliverable required me to produce seven (7) visualizations which will tells a small story about different data points related to the Citibike data.


_**Visualization (Viz) 1 - Check Times for Users**_

    This Viz displays a line graph of the number of bikes checked out by the duration for all users.  
    * Filtered by the hour.

    ![](https://github.com/SheaButta/plotly_deployment/blob/main/static/images/BarChart.PNG)


_**Visualization (Viz) 2 - Checkout Times by Gender**_

    This Viz displays a line graph of the number of bikes checked out by the duration for each gender by the hour 
    * Filtered by the hour and gender.

    ![](https://github.com/SheaButta/plotly_deployment/blob/main/static/images/GuageChart.PNG)


 _**Visualization (Viz) 3: Trips by Weekday per Hour**_
 
    This Viz displays a heatmap of the number of bikes trips for each hour of each day of the week.

    ![](https://github.com/SheaButta/plotly_deployment/blob/main/static/images/BubbleChart.PNG)
    

_**Visualization (Viz) 4: Trips by Weekday per Hour**_
 
    This Viz displays a heatmap of the number of bikes trips by _**gender**_ for each hour of each day of the week.

    ![](https://github.com/SheaButta/plotly_deployment/blob/main/static/images/BubbleChart.PNG)
    

_**Visualization (Viz) 5: User Trips by Gender by Weekday**_
 
    This Viz displays a heatmap of the number of bikes trips for each type of user and gender for each day of the week.  
    * Filtered by user (Customer or Subscriber) and gender.

    ![](https://github.com/SheaButta/plotly_deployment/blob/main/static/images/BubbleChart.PNG)


_**Visualization (Viz) 6: **_
 
    This Viz displays a heatmap of the number of bikes trips for each type of user and gender for each day of the week.  
    * Filtered by user (Customer or Subscriber) and gender.

    ![](https://github.com/SheaButta/plotly_deployment/blob/main/static/images/BubbleChart.PNG)


_**Visualization (Viz) 7: **_
 
    This Viz displays a heatmap of the number of bikes trips for each type of user and gender for each day of the week.  
    * Filtered by user (Customer or Subscriber) and gender.

    ![](https://github.com/SheaButta/plotly_deployment/blob/main/static/images/BubbleChart.PNG)


## Summary
My client is extremely pleased with the final sprint and the release of their updated dashboard.   Probable Beef (PB) has decided to hire me as their "Data Engineer" to assist with their growth and decision making for their business.  As you can see, the final dashboard does include a great constrasting background color and is extremley easy on the eyes.  As you change the subject ID of volunteers, you will notice each visualization changes to represent the correlation based on the volunteer.

__Final Dashboard:__

![](https://github.com/SheaButta/plotly_deployment/blob/main/static/images/DDL_Charts.PNG)







