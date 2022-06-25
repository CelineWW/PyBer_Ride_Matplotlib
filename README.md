# PyBer_Analysis
## Oerview
  - Analyze ride-sharing data and create a summary by city type. 
  - Analyze total weekly fares of ride-sharing for each city type, and show it in a multiple-line graph.

## Results

summarizes how the data differs by city type and 
There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)
The total number of rides for each city type is retrieved. (5 pt)
The total number of drivers for each city type is retrieved. (5 pt)
​The sum of the fares for each city type is retrieved. (5 pt)
​The average fare per ride for each city type is calculated. (5 pt)
The average fare per driver for each city type is calculated. (5 pt)
A PyBer summary DataFrame is created. (5 pt)
The PyBer summary DataFrame is formatted as shown in the example. (5 pt)


A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time. (10 pt)
A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare." (10 pt)
A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-28. (5 pt)
A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week. (10 pt)
An annotated chart showing the total fares by city type is created and saved to the "analysis" folder. (10 pt)

## Summary
how those differences can be used by decision-makers at PyBer.
There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)




Overview of the analysis: Explain the purpose of the new analysis.
Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.



