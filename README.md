# PyBer_Analysis
## Oerview
The purpose of new analysis of PyBer ride-sharing is discovering accessiblity and affordability of ride-sharing for each city type (urban, suburban, and rural cities). So PyBer company will have better overview of their past work and take more effective further steps to seek better business opptuinities and expand their operations in all types of cities.

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
Based on the results, some recommendations can be proposed to the CEO of PyBer:
  - Total rides in urban was 13 times of total rides in Rural city, and 2.6 times of total rides in suburban city. That means ubran city has hight utilization ratio of PyBer ride-sharing. This might be thanks to the population of urban cities, which caused a higher demand of ride-sharing. But it also can be improved by advertisement injecting to suburban and rural cities. 
    1. PyBer or the city governments can take more effort on spreading their Green environmental protection concept to encourage people to share their rides. 
    2. From the view of average fare per ride, we can tell, the more rider engaged, the lower fare per ride would it cost.
    3. A bonus for ride-sharing is saving rider's time. Riders may relax or get prepared for the work instead of focusing on driving if they choose to share ridings. 
    
  - Average fare per driver in urban city was approximately half times of in sururban city, and one third times of in rural city. Driver's avenue in urban city earn way less than in suburban city and rural city. The unsatisfying status might be a potential issue for the PyBer. On the other hand, we can see total drivers in urban city was 31, 5 times of rural city and suburban city respectively. Average fare per driver seems to be inversely proportional to total drivers. This indicated that drivers' service supply exceededs demand in urban city. PyBer should keep driver count to a minimun threshold for the ride-sharing needs.
  
  - A glance of total fare by city type graph shows that total fares of ride-sharing in Urban city is high above than suburban city and rural city. Specifically, it is roughly 2-3 times of suburban city and around 10 times of rural city. For PyBer, rural and suburban cities are undeveloped area to expand their business. They should put more investment to appeal to a wider user base. Attracting more drivers to register for PyBer app or training drivers by the PyBer company itself should be the very first step. Urban city contributed most of ride-sharing markert, which should be maintained with better quality of service. Such as, improving the PyBer app interactive interface, Optimizing ride-sharing plans for both the driver and the rider, Providing more information of each registered driver so as the rider can choose their preferences.



