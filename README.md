# Background
V. Isualize has given a brand-new assignment. Using Python skills and knowledge of Pandas, I will create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, I will create a multiple-line graph that shows the total weekly fares for each city type. Finally, a written report summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

# Summary 
The PyBer Summary Dataframe compares PyBer's ridesharing services in three distinct cities: Rural, Suburban, and Urban. The data highlights the demand for Pybers ride-sharing among urban cities as opposed to suburban and rural. In the period January 2019-May2019 , 1625 rides are shown in urban cities while 625 rides are in Suburban cities, and 125 rides are in rural cities. These percentages are highlighted in the figures below and show Urban cities significantly benefit PyBer's platform through overall rides.

# What You'll See
This new assignment consists of two technical analysis deliverables and a written report to present your results. 


Deliverable 1: A ride-sharing summary DataFrame by city type
Deliverable 2: A multiple-line chart of total fares for each city type
Deliverable 3: A written report for the PyBer analysis (README.md)

###### Resources and Before Start Notes:
Data Source: PyBer_Challenge_starter_code.ipynb named later as PyBer_Challenge.ipynb
Data File: file.csv
Software: Matplotli 3.2.2, Python 3.9, Visual Studio Code 1.50.0, Anaconda 4.8.5, Jupyter Notebook 6.1.4, Pandas
For more information, read the Documentation on Python data types.

## DELIVERABLE 1: A Ride-Sharing Summary DataFrame by City Type

*A detail analysis of:
The total number of rides for each city type is retrieved.
![Fig6](https://user-images.githubusercontent.com/111712209/194261145-f6d6e483-4016-4b26-95b5-de365bcfe1a5.png)


The total number of drivers for each city type is retrieved.
![Fig8](https://user-images.githubusercontent.com/111712209/194261301-8225a1f6-3eaf-4b00-85df-e5706b041d89.png)


The sum of the fares for each city type is retrieved.
![Fig5](https://user-images.githubusercontent.com/111712209/194261391-8c0be6a3-5a77-4276-91fa-6273cadb77b5.png)

The average fare per ride for each city type is calculated.

The average fare per driver for each city type is calculated.

A PyBer summary DataFrame is created.
The PyBer summary DataFrame is formatted as shown in the example.
![PyBer_Summary](https://user-images.githubusercontent.com/111712209/194167359-bb2d65eb-9853-4cf0-968c-4af6a7706786.png)

## DELIVERABLE 2: A multiple-line chart of total fares for each city type

A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.
A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."

![Groupby](https://user-images.githubusercontent.com/111712209/194177094-7169c5bb-b7dd-42a4-a8ae-12be5f929c80.png)



A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-29.
A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.
![PyBer_Summary](https://user-images.githubusercontent.com/111712209/194171128-c76d07c7-6bea-49e5-93ae-b9620ef789b8.png)

An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.
![Analysis_folder](https://user-images.githubusercontent.com/111712209/194171225-d23b848a-8480-48c9-989a-69ea68d36bf5.png)

## DELIVERABLE 3: A written report for the PyBer Analysis

The written analysis has the following:

#Overview of the analysis:
The purpose of the new analysis is:
 To analyze and discover trends and create a complete overview of the Ride-Sharing data by city type which includes charts from Matplotlib libraries such as Line, Bar, Scatter, Bubble, Pie, and box-and-whisker plots. Then we determine the mean, median and mode using Pandas, NumPy and SciPy statistics. Our Final Analysis will show distinct line graphs of total weekly fares for each city type. 

** 2. Results

There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. 
The Suburban fares started around $1,000, and the analysis was not profitable, fare dropped in March and in mid-April.
The Rural fares started at around $200, the analysis shows fares increase and dropped till the end of April.
The Urban fares start with an average of $1,800 with a consistent increase around 2,400.

*The PyBer DataFrame
![PyBer_Summary](https://user-images.githubusercontent.com/111712209/193993780-9463e634-950d-4566-8b46-27c8a310a02c.png)

*Line Charts of total fares
![Fare_Play](https://user-images.githubusercontent.com/111712209/193995696-1e5d4ac2-c8d0-40f0-879b-406825a4b534.png)

*PyBer Ride-Sharing Data(2019)
![Ride_Sharing(2019)](https://user-images.githubusercontent.com/111712209/193996980-e63d6c18-1c9b-4e6d-93f2-9b3166646dac.png)


There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. Based on our findings we can prepare business recommendations for addressing any disparities among the city types 

1)Our analysis indicates that there are many good opportunities to expand the business in rural and suburban city, including hiring drivers to operate and expose business in rural and suburban cities. This can be deduced by examining our charts and figures. Lets take a look:

From the data shown below, we can see there is a larger use of PyBer ridesharing in urban cities and more drivers as well, concluding the majority of PyBer's revenue comes from urban areas.
$ of Total Drivers by City Type 
![Fig8](https://user-images.githubusercontent.com/111712209/193998851-a2924d4c-1a2c-45f8-bfd6-b6270939a3dc.png)

2)Since the Urban cities fare is the most consistent with drivers and rated higher, this will give many business opportunities to expand rides. On the other hand, the cost for using Pyber is greater in rural cities then urban cities therefore discouraging riders due to the high fares 
% of Total Fares by City Type
![Fig5](https://user-images.githubusercontent.com/111712209/194003458-f2999c46-c1f2-4e2b-8df2-3dc67cc9db15.png)

3) The Rural cities is the lowest of the two city types(Urban and Suburban).  Since there is room for growth, an expansion of fares would assist the company in gaining financially and benefitting their data. Drivers in rural cities will earn more as a result even though this may discourage potential drivers from working with PyBer in other cities due to the low fares per driver
 ![PyBer_fare_summary](https://user-images.githubusercontent.com/111712209/194004114-aa270946-584e-44e8-9176-85779976344d.png)
 
 In Conclusion, PyBer's ridesharing services vary significantly in Rural, Suburban and Urban cities based on the data above displaying the number of rides, drivers and fares per city and the high amount of usage of PyBer's services in urban cities.
