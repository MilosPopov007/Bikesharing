# Bikesharing

Tableau Data visualization of a New York Citi Bike data set, in order to present a venture business idea for a bike sharing company

[NY City Citibike Data Analysis Tableau](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust?publish=yes)

Last summer, I and my friend Kate took the trip of a lifetime, New York City, for two full weeks, exploring the historic landmarks like Central Park, the Statue of Liberty, Broadway and the Empire State Building. It was a magical experience, and as we flew home together, we looked through our vacation photos and had a realization. One of the key ingredients to the magic was an unlikely suspect "City bike". Me and Kate had biked everywhere, which allowed us to really get to know the city and interact with the people who live there and who are using bikes for their commutes. A gem of an idea starts to form in our mind. What if we could start a similar bike share business in our hometown Colorado. This is an exciting prospect, but I know, we have to think realistically, the mechanics of making this business work might be quite different in Colorado than in New York City. We decided that the first step is to figure out how the bike share business actually works in New York City. Kate is gregarious, friendly, and fearless. She is definitely the face of our proposal.

## Results:

For this project, we'll use data from the Citi Bike ([https://citibikenyc.com/](https://citibikenyc.com/)) program in New York City. This data includes a variety of fields ([https://citibikenyc.com/system-data](https://citibikenyc.com/system-data)) stored in a flat file, a CSV. We'll use data from August because there is likely more traffic during the summer months.

Using Python and Pandas functions, I convert the "trip duration" column from an integer to a datetime data type to get the time in hours, minutes, and seconds (00:00:00). After  converting the "trip duration" column to a datetime dataytpe, I exported the [DataFrame](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC_Citibike_Challenge.ipynb) as a CSV file to use for the trip analysis.


![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/Number%20of%20Rides.png)

[Number of Rides Citi Bike: NYC's Official Bike Sharing System (The Month of August)](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust)

After thinking through various questions, you settle on the first question you would like the data to answer: how many bike trips were recorded during the month of August? Since August is a beautiful time of the year to rent a bike, we want to use this data as a starting point to determine how many rides we could expect. NY Citibike recorded 2,344,224 trips in the month of August 2019.


![This is an image](https://github.com/MilosPopov007/Bikesharing/blob/main/NYC%20Bike/August%20Peak%20Hours.png)
[August Peak Hours](https://public.tableau.com/app/profile/milos.popov/viz/Module15Challenge_16754567361060/NumberofRidesCitiBikeNYCsOfficialBikeSharingSystemTheMonthofAugust?publish=yes)  

A key piece of data we need is the peak usage hours for the month of August. This will help us get a better idea of how many bikes we might need for our local business as well as figure out during which parts of the day we'll need the most bikes. For example, if we need to do maintenance on a bike, knowing the peak usage hours will help us plan for the best time to do that. Looking at Bar graph we can conclude that peak hours are around 8 a.m. and 5 p.m. this data indicates  that a lot of Newyorkers use Citibike for their work commute.
