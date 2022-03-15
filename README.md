# DATA_ANALYSIS_PROJECTS-

In these three projects from the udacity Advanced Data Analysis Nanodegree Program. will be using python with jupyter notebook and libraries such as Numpy, Pandas, Matlibplot and seaborn data analysis.

# First Project
## Investigate A movie dataset and communicate our findings


# Second Project

## Analyze A/B Test, to find wich landing page for a website is better the new or the old


# Third Project
## Ford Go Bike Dataset Exploration


## Dataset 

> This data set is taken from https://www.kaggle.com/chirag02/ford-gobike-2019feb-tripdata.
Ford Go bike services provides rental services for bikes This dataset includes trips taken by users
in month of February 2019 covering the greater San Francisco Bay and after preliminary wrangling
, removing outliers and adding new featuers the dataset now contains 174952 rows and 16 columns and 
information about the trips taken by the users such as their: duration, station, users age, user type, 
user gender, start date and hour ect.


## Summary of Findings
1- Univariate:
The bikers who are subscribers tend to rent more than the customer bikers, 
also bikers in general tend to rent more bikes on week days than weeks ends which is 
also supported by having the highest rentals per on 8 am and 5 pm. which corrsponds to 
normal working hours. also the bikers ride duration in general is less than 60 mins and with
the highest amount of rides between 8 to 10 mins. we also looked at the top five busiest Stations

2-Bivariate:
We observed that for the subscribers the week days are the most active days with weekends as the lowest active 
days while the customers had a more normal distribution between the the entier week in terms of renatl count. 
which suggests that subscribers use the rental service to commute to thier jobs during the weekdays

We observed that the avg trip duration will be longer for customers than subscribers which is interesting as we
know subscribers use the rental service more but it seems they only use it for short daily activites.

We observed that other take the highest avg duration per min then secondly female then finally male with the least 
avg duration we also should investigate this further by adding the age to our chart later in the Multivariant section

We observed that the avg age of male bikers is 35 and the avg female age is 36 while the others avg age is 38

we observed that the duration per min starts to increase very slightly as the age decrease which is as expected

We also observed Start and end stations top and lowest three in terms of traffic which will help to determine 
which station to take better care of or allocate more resource to for example

3- Multivariate:
We observed that Subscribers have almost similar ride duration throught the week while the customers take longer Rides
through the entier week but the difference is especially clear between the weekends of the customer and subscribers where
the highest difference is represented and also the duration for the customer weekends is around 3 mins longer than
the avg duration for the customer week days so I guess the customers like to enjoy longer rider on thier day off.

We observed that through the week days from monday to friday the busiest time for users who are customers would be 
around 5 pm while for the subscribers it would be around 8 am and at the weekend for the customer it would be around
1 pm. while for subscribers its evenly divided between 1pm at saturday and 4 pm at sunday. this supports our suggestion
that users Mostly use the service for work during the week days and for leisurely activites during the weekend

We observed that For the customers the gender type who enjoys the longest ride ar femals with record of 16 min avg while
for the subscribers we find that others have the highest avg of 11 min

## Key Insights for Presentation

In general the busiest time for the rental service will be on weekdays especially on Tuesday and Thursday at 8 am and 5 pm.
For user type customers that the busiest time wil be on Thursday at 5pm. and Friday at 8 am.
For user type Subscriber that the busiest time wil be on Tuesday and Thursday at 8 am.
About 90 % of the rental services users are Subscribers.

Thus, We can estimate that users mostly use the rental service to commute to thier jobs during the weekdays as the start hours also corosponds with normal office ours

The average ride duration is betwen 8 min to 10 min In general.
user type customers seem to enjoy longer ride duration and especially on weekends with an average duration of 17 min while the sibscribers had an average duration of 10 min on Saturday and Sunday
user type customer and gender female enjoy the longest ride with avg duration of about 16 mins.

thus, I guess the users in general like to enjoy longer rider on thier day off especially user type customers who are female.

The Top three busiest start stations are 'Market St at 10th St', 'San Francisco Caltrain Station 2 (Townsend St at 4th St)' and 'Berry St at 4th St'
Top Three busiest end stations are 'San Francisco Caltrain Station 2 (Townsend St at 4th St)','Market St at 10th St' and 'Montgomery St BART Station (Market St at 2nd St)'
the Lowest three busiest start stations are '16th St Depot', 'Palm St at Willow St'and '21st Ave at International Blvd'
the Lowest three busiest end stations are '16th St Depot', 'Willow St at Vine St' and '21st Ave at International Blvd'

thus, The top three busiest start stations provide rental serivce for about 5% and top three busiest end station provide rental serivce for about 6% while the lowest three busiest stations both end and start stations combiend provides rental service for merley about 0.01% out of 329 stations


