# PyBer_Analysis
## Oerview
The purpose of new analysis of PyBer ride-sharing is discovering accessiblity and affordability of ride-sharing for each city type (urban, suburban, and rural cities) .

  - To get the summary of ride-sharing, the total number of rides, drivers and fares were aggregated from original large dataset. Based on these values, fares were converted to average fare per ride(cost to the rider), and average fare per driver(revenue to the driver) for different city types. A DataFrame was created for the summmary. 
  - New DataFrame was created to show the total fare amount for each date and city type. The dates were filtered to a specific range:  2019-01-01 through 2019-04-28. Then we totalized the daily fares to weekly fares by city type. The result of the total fare analysis for each week was visulized with a multiple-line chart.

## Resources and Toools
  - Resources: [city_data.csv](https://github.com/CelineWW/PyBer_Analysis/blob/main/Resources/city_data.csv), [ride_data.csv](https://github.com/CelineWW/PyBer_Analysis/blob/main/Resources/ride_data.csv)
  - Tools: Jupyter notebook, Pandas, Matplotlib

## Results
  - Results of PyBer ride-sharing analyses based on city type are shown as below:
    - The total number of rides for rural, suburban, and urban city are 125, 625, and 1,625 rides respectively.
    - The total number of drivers for rural, suburban, and urban city are 78, 625, and 2,405 drivers respectively.
    - The sum of the fares for rural, suburban, and urban city are $4,327.93, $19.356.33, $39,854.38 respectively.
    - The average fare per ride for rural, suburban, and urban city are $34.62, $30.97, $24.53 respectively.
    - The average fare per driver for rural, suburban, and urban city are $55.49, $39.50, $16.57 respectively.
    
    Formatted <PyBer_ride-sharing_summary DataFrame> is attached.
  <p align="center">
     <img src="https://user-images.githubusercontent.com/105877888/175786677-178e831b-17ae-490c-b9e9-162ef04fa581.PNG">
  </p>

  - Weekly fares of PyBer ride-sharing during 2019-01-01 through 2019-04-28 are sorted by city type.  
    
    The result is illustrated by multiple-line chart as below: 
   ![PyBer_fare_summary](https://user-images.githubusercontent.com/105877888/175786703-9dfeaa62-e972-47bd-819d-8442fdcbbc86.png)
   
   
## Summary
Based on the results, 
Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
 Overall, ride-sharing is more common in urban city, whereas barely taken in rural city. In the meantime, for either fare per ride or fare per driver, average fares in urban city, are much lower than suburban and rural city.     
 
  Total fares of ride-sharing in Urban city is high above than suburban city and rural city. It is roughly 2-3 times of suburban city and around 10 times of rural city.



