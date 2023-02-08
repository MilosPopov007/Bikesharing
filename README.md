# Bikesharing

Tableau Data visualization of a New York Citi Bike data set, in order to present a venture business idea for a bike sharing company

[NY City Citibike Data Analysis Tableau](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust?publish=yes)

Last summer, I and my friend Kate took the trip of a lifetime, New York City, for two full weeks, exploring the historic landmarks like Central Park, the Statue of Liberty, Broadway and the Empire State Building. It was a magical experience, and as we flew home together, we looked through our vacation photos and had a realization. One of the key ingredients to the magic was an unlikely suspect "City bike". Me and Kate had biked everywhere, which allowed us to really get to know the city and interact with the people who live there and who are using bikes for their commutes. A gem of an idea starts to form in our mind. What if we could start a similar bike share business in our hometown Colorado. This is an exciting prospect, but I know, we have to think realistically, the mechanics of making this business work might be quite different in Colorado than in New York City. We decided that the first step is to figure out how the bike share business actually works in New York City. Kate is gregarious, friendly, and fearless. She is definitely the face of our proposal.

## Results:

For this project, we'll use data from the Citi Bike ([https://citibikenyc.com/](https://citibikenyc.com/)) program in New York City. This data includes a variety of fields ([https://citibikenyc.com/system-data](https://citibikenyc.com/system-data)) stored in a flat file, a CSV. I use data from August because there is likely more traffic during the summer months.

Using Python and Pandas functions, I convert the "trip duration" column from an integer to a datetime data type to get the time in hours, minutes, and seconds (00:00:00). After  converting the "trip duration" column to a datetime dataytpe, I exported the [DataFrame](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC_Citibike_Challenge.ipynb) as a CSV file to use for the trip analysis.


![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/Number%20of%20Rides.png)

[Number of Rides Citi Bike: NYC's Official Bike Sharing System (The Month of August)](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust)

After thinking through various questions, you settle on the first question you would like the data to answer: how many bike trips were recorded during the month of August? Since August is a beautiful time of the year to rent a bike, we want to use this data as a starting point to determine how many rides we could expect. NY Citibike recorded 2,344,224 trips in the month of August 2019.


![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/August%20Peak%20Hours.png)

[August Peak Hours](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust?publish=yes)  

A key piece of data we need is the peak usage hours for the month of August. This will help us get a better idea of how many bikes we might need for our local business as well as figure out during which parts of the day we'll need the most bikes. For example, if we need to do maintenance on a bike, knowing the peak usage hours will help us plan for the best time to do that. Looking at Bar graph we can conclude that peak hours are around 8 a.m. and 5 p.m. this data indicates  that a lot of Newyorkers use Citibike for their work commute.


![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/Customer%20Type.png)

[Customer Type](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/CustomerType?publish=yes)


The Proportion of Short Term Customers to Annual Subscribers Data shows us that the number of trips by Subscribers of NY Citi Bike was 1,900,359 vs. Single Customer Rides of 443,865 for the month of August. New York Citi Bike offers Annual Membership Subscription, Single Ride and Daily Pass ([https://citibikenyc.com/pricing](https://citibikenyc.com/pricing)). We want as many subscribers as we can get.  Promoting a healthy lifestyle and with the  help of a rising gas prices we are on the right track.

![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/Top%20Starting%20Locations.png)

[Top Starting Locations](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust)

Now we're going to use the data to find the most popular stations in the city for starting a bike journey. This data will help us plan the  bike numbers for certain locations.

![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/Top%20Ending%20Locations.png)

[Top Ending Locations](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust)

Now we know where customers are beginning their bike rental journeys. But where do they drop off the bikes ? Symbol map will show us most popular places to end a bike ride.

![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/Average%20trip%20duration%20by%20age.png)

[Average Trip Duration by Age](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust) 

Let's take a look at the average duration of a bike ride, by age. This will help us set expectations for our trip duration. On average users 20 to 30 years old are likely to take longer rides.

![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/Bike%20repairs.png)

[Bike Rapairs](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust)

Bike maintenance will likely be one of the biggest expenses. The bikes used most frequently will probably be the ones that require the most maintenance, so we'll need to determine which bikes have the highest sum of "Number of Rides". Treemap will give an idea of how often each bike is used, and then note which ones are used most frequently.

![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/Bike%20Utilization.png)

[Bike Utilization](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust)

The bubbles in this plot show the bike utilization levels. If a bike has a higher utilization level, it will be a larger bubble. This will continue to help us understand the needs of a bike-sharing business.

![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/Checkout%20times%20for%20users.png)

[Checkout Times for Users](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust)

In this visualization, I graph the length of time that bikes are checked out for all riders. Most checkout times are under 20 min.

![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/Checkout%20time%20by%20gender.png)

[Checkout Times by Gender](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust)

Visualization graph for the length of time that bikes are checked out for each gender. Men are among the primary users of Citibike.

![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/Trips%20by%20weekday%20for%20each%20hour.png)

[Trips by Weekday for Each Hour](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust)

Trips by Weekday for Each Hour will help us plan bike utilization "Rush Hours". The darker red on the heat map shows us the "Peaks". <br />
We can conclude that NY Citi Bike is widely used for daily work commute. "Rush Hours" are 8 a.m. and 5 p.m.

![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/Trips%20by%20Gender%20.png)

[ Trips by Gender (Weekday per Hour)](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust)

 Red on the heat map shows us the "Peaks" utilization for each gender. This will be good data for our marketing strategy.
 
 ![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/Users%20trips%20by%20Gender.png)
 
 [User Trips by Gender by Weekday](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust)
 
Another piece of data we want to look into is the number of short-term customers and annual subscribers to the Citi Bike service. This will help us determine the types of customers we could expect for a bike-sharing company. NY Citibike primary subscribers are men.


### Summary:

Bike-share programs generate a number of economic and personal benefits. 
Less pollution - Not only do bike-share systems intend to reduce traffic congestion, they also aim to reduce air pollution through decreased automobile usage, and indirectly through the reduction of congestion. The study on D.C.'s Capital Bikeshare estimated that the reduction in traffic congestion would be equivalent to roughly $1.28 million in annual benefits, accrued through the reduction in congestion-induced CO2 emissions.[^1] 
[^1]: Hamilton, Timothy; Wichman, Casey (20 August 2015). Bicycle Infrastructure and Traffic Congestion: Evidence from DC's Capital Bikeshare (Technical report).

Separate study of transportation in Australia estimated that 1.5 kilograms of CO2 equivalent emissions are avoided by an urban resident who travels 5 kilometers by cycling rather than by car during rush hour periods.[^2] 
[^2]: Bonham, Jennifer (2005). "Economics of everyday cycling and cycling facilities". Cycling Futures.
