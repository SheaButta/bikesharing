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

    ![](https://github.com/SheaButta/bikesharing/blob/main/images/Viz1.PNG)


_**Visualization (Viz) 2 - Checkout Times by Gender**_

    This Viz displays a line graph of the number of bikes checked out by the duration for each gender by the hour 
    * Filtered by the hour and gender.

    ![](https://github.com/SheaButta/bikesharing/blob/main/images/Viz2.PNG)


 _**Visualization (Viz) 3: Trips by Weekday per Hour**_
 
    This Viz displays a heatmap of the number of bikes trips for each hour of each day of the week.

    ![](https://github.com/SheaButta/bikesharing/blob/main/images/Viz3.PNG)
    

_**Visualization (Viz) 4: Trips by Gender (Weekday per Hour)**_
 
    This Viz displays a heatmap of the number of bikes trips by _**gender**_ for each hour of each day of the week.

    ![](https://github.com/SheaButta/bikesharing/blob/main/images/Viz4.PNG)
    

_**Visualization (Viz) 5: User Trips by Gender by Weekday**_
 
    This Viz displays a heatmap of the number of bikes trips for each type of user and gender for each day of the week.  
    * Filtered by user (Customer or Subscriber) and gender.

    ![](https://github.com/SheaButta/bikesharing/blob/main/images/Viz5.PNG)


_**Visualization (Viz) 6: Types of Users**_
 
    This Viz displays the type of users Citibike has.  They have Customers and Subscribers.  Their cusstomers are occastional or regular riders; while their subscribers pay a year fee for this service.  This pie chart and legend says everthing.

    ![](https://github.com/SheaButta/bikesharing/blob/main/images/Viz6.PNG


_**Visualization (Viz) 7: Top Starting Locations**_
 
    This Viz displays the starting location for each biker rider and counts the number of ride from each location which is describe by latitude and longitude.
    
    ![](https://github.com/SheaButta/bikesharing/blob/main/images/Viz7.PNG)


## Summary
The dataset has been analyzed and visualized thoroughly.  Based on my review of all avenues for a return on investment, each visualization shows huge potential for Des Moines to have solid bike sharing business.  This data was only collected for the month of August which visualizes a return on investment.  My analysis did not cover the early spring and summer months.

There are two (2) additonal visualizations that I would recommend performing to display additional returns on investment.  These two (2) additional visualizations include;

1. Using the latitude and longitude columns from the dataset, I would recommend a visualization to include the actual city names and/or boroughs that represent various hotspots     for a bikers start location.
    
2. Using the [Birth Year] from the dataset, I would recommend producing a visualization to calculate an approximate age of each biker.







