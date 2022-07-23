# bikesharing overview

An analysis of citi-bike data for the month of august in 2019. 

Tableau Analysis: https://public.tableau.com/app/profile/john.nelson6899/viz/CitiBIkeChallenge/BikeShareAnalysis?publish=yes

# Purpose

A client wished to analyze bike sharing data from NYC to determine if a bike-share program would work in Des Moines, Iowa.  The analysis was performed on citibike data from NYC, and will be used to extrapolate the viability of a bike-share program for our client.  Investors were interested in the data, so we presented it using tablaeu (and this readme file).

# Resources

- tableau public
- jupyter notebook
- python - pandas
- python - datetime 
- citibike data (08/2019)

# Analysis

## Trip duration for all users:

<img width="766" alt="Screen Shot 2022-07-23 at 3 27 35 PM" src="https://user-images.githubusercontent.com/6634774/180620099-e36d3b80-8e8d-4475-8d66-04aae5b4f83f.png">

The graph above, shows us that most users trips are below 10 minutes in length.  This would lead us to conclude, that no station should be longer than a 10 minute bike ride from it's closest station.  

## Trip duration by gender:

<img width="766" alt="Screen Shot 2022-07-23 at 3 28 02 PM" src="https://user-images.githubusercontent.com/6634774/180620119-1488bc2e-ff2b-4316-b295-7c76730efdc2.png">

From the graph above, we can condlue that males and females have very similar average ride times.  

## Trip popularity by weekday and hour:

<img width="522" alt="Screen Shot 2022-07-23 at 3 32 12 PM" src="https://user-images.githubusercontent.com/6634774/180620252-c4695520-d441-4031-b6cf-84cb755d4c42.png">

The heaviest trafficked times are those during weekdays for morning and evening commute times, and weekends from the 11am - 5pm range.  We can see based on the color signatures, that the weekdays have higher spikes in the AM & PM commute times, while the weekend has a steady color gradient for most of the day.  I would suggest that for any new program, they avoid doing any maintence of bikes during those times, and make sure that heavily trafficked stations are fully stocked with bikes before the morning/evening rush on the weekedays. 


## Trip popularity by weekday, hour and gender: 

<img width="1343" alt="Screen Shot 2022-07-23 at 3 33 11 PM" src="https://user-images.githubusercontent.com/6634774/180620282-f20fba7c-afc4-4dc6-aee0-571917d68ebd.png">

Again this graph confirms the same as above, the highest trafficked times for all genders are morning/evening commutes and weekend days between 11am-5pm.

## Trips by customer type, weekday and gender:

<img width="355" alt="Screen Shot 2022-07-23 at 3 33 43 PM" src="https://user-images.githubusercontent.com/6634774/180620294-9e491520-eba4-46fc-a24a-bb646c0be45e.png">

Based on this chart, we can see that thursday and friday are the days with the most bikes requested by subscribers.  Thus, i would suggest running a subscriber promotion on those days, or reserving a certain number of bikes at popular subscriber stations for subscribers only, because it is clear that subscribers check out more bikes than non-subscribers do.  


## User Type:

<img width="173" alt="Screen Shot 2022-07-23 at 3 34 19 PM" src="https://user-images.githubusercontent.com/6634774/180620322-905b4f14-23c2-4ab2-8507-a38020a0835d.png">

Based on the popularity of the subscriber model, I would suggest that any new city run promotions for subscribing during the summer months and during morning/evening commutes on thursday/friday.  Also select weekends throughout the year, it would be interesting to see how a subscriber promotion could influence or drive subscribtion sales.


## Bike usage map:

<img width="1441" alt="Screen Shot 2022-07-23 at 3 34 51 PM" src="https://user-images.githubusercontent.com/6634774/180620335-2384a911-b803-4a05-ad64-145134e9261b.png">

This map indicates (for NYC), the most popular starting locations.  They are highly trafficked, high population and high tourist areas, including major public transport hubs.  For any new city staring a bike sharing program, I would suggest they start building from these popular areas and expand outwards. 

## Additional Data Needed

1. We need more data as to how the bikeshare program works year round.  It seems obvious that during colder months we can expect less riders, but I would like to see a visualization on how drastically that number drops.  Based on that information, we may take some bikes off the stations and stor them to prolong their longeivity in the bike system. 
2. Additionally to full year data, temperature data would work great here too.  Based on the forecast, we could instruct our employees to stock extra bikes or pull some bikes for repair/maintence if needed.
3. Maintence cost per bike.  Currently we have no data on how much each bike costs to maintain, the cost per trip and the revenue.  With this information we could judge the success of a bike share campaign with better detail. 


