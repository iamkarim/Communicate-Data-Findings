# (Ford GoBike Dataset Exploration)
## by (Sarumi Abdulkarim)


## Dataset

Ford GoBike is the Bay Area's bike share system. Bay Area Bike Share was introduced in 2013 as a pilot program for the region, with 700 bikes and 70 stations across San Francisco and San Jose. Once expansion is complete, Ford GoBike will grow to 7,000 bikes across San Francisco, the East Bay and San Jose.Ford GoBike, like other bike share systems, consists of a fleet of specially designed, sturdy and durable bikes that are locked into a network of docking stations throughout the city. The bikes can be unlocked from one station and returned to any other station in the system, making them ideal for one-way trips. People use bike share to commute to work or school, run errands, get to appointments or social engagements and more. It's a fun, convenient and affordable way to get around.
The bikes are available for use 24 hours/day, 7 days/week, 365 days/year and riders have access to all bikes in the network when they become a member or purchase a pass
The FordGo Bike dataset uses data collected through the month of February,2019. There were approximately 183,412 bike rides collected. This dataset can be gotten in CSV format <a href=https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv>here</a>

> The column headers description are as follows:
>*  Trip Duration in seconds
    * Start Time and Date
    * End Time and Date
>* Start Station ID
    * Start Station Name
    * Start Station Latitude
    * Start Station Longitude
>* End Station ID
    * End Station Name
    * End Station Latitude
    * End Station Longitude
>* Bike ID
>* User Type (Customer or Subscriber)
    * Member's Gender (Male, Female or Other)
    * Member's Birth Year 
>* If the Bike was shared during the trip (Yes or No)
>
> While Cleaning the Data, The Following Columns were added to the dataset:
>* Member's Age
>* Start Time Month                 
>* Start Time Month Number             
>* Start Time Weekday               
>* Start Time Hour                
>* End Time Hour                   
>* Duration in minutes                     
>* Distance in kilometers

## Summary of Findings
> At the start of the exploration, nothing seems out of the normal expectations for a bike sharing system in a major city. So far, the data reveals that adults in the average working age range are the primary user base for the system, and they use the bikes on their daily commutes.
> The relationship of the Distance Covered and the Duration with other features were the standouts. It showed that people covered a great distance with the bikes without wasting the time of Customers or the Subscribers. We were also able to see the relation with several age groups with millenials being the ones with the most distance covered and with most time spent on the service. 
> I also noticed the count of rider per day in respect to the User types. Most Subscribers use their bike rides between Monday to Friday while the Customers have a low spread through out the week and it brought the assumption of customers being tourists or people out of town trying to navigate the Bay Area.
> I observed the relationship of the Start time and the Days of the Week which helped in revealing when rides are taken per week and also between the Customers and Subscribers. Distance and duration also strentened each other in looking through the Genders of the User types which help see the difference in athletic ability between the male and female.


## Key Insights for Presentation

According to the investigation, the two types of riders have different usage patterns and habits. Customers ride a lot on weekends, especially in the afternoon, but subscribers use the system substantially throughout the weekdays, from Monday through Friday. Customers prefer to use more in the late afternoon around 17pm Monday through Friday, whereas subscribers tend to make more journeys between 8 and 9 am and 17 and 18 pm on workdays. Subscribers' efficient/short periods of consumption are consistent with their high concentration during Monday through Friday rush hours, showing that the use is mostly for commuting to work. Customers are using the bike sharing system significantly differently from subscribers, taking advantage of it far more on weekends and in the afternoons, as evidenced by the more flexible and lax pattern of their usage.