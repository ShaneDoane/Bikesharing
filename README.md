# Bikesharing
Analyzing NYC Citi Bike data with Tableau

## Overview
The purpose of this analysis was to understand the NYC Citi Bike system to determine the viability of a similar bikeshare business in Des Moines, Iowa. Data was obtained through https://www.citibikenyc.com/system-data and analysis was conducted on August 2019 trip data. I ran different analyses on users by gender and subscriber status, trip duration and location, and timing of trips.

## Results
[See dashboard](https://public.tableau.com/app/profile/shane.doane/viz/NYC_Citi_Bike_Challenge_16486036988930/NYC_Cit_Bike_Story?publish=yes)

### User Analysis
Most Citi Bike users are Male. 

![image](https://user-images.githubusercontent.com/93338132/161446816-26b37df3-377e-4484-a086-fb393421ac72.png)

Subscribers account for over 3/4 of total rides. Males also account for nearly 3/4 of rides. 
Guest customers are more likely to not list their gender.

![image](https://user-images.githubusercontent.com/93338132/161446849-7ff74281-03e2-4292-933a-6dd22675ee96.png)

### Trip Analysis
Nearly all trips are under 1 hour, with most under 20 minutes

![image](https://user-images.githubusercontent.com/93338132/161447557-915db35f-f20d-48cc-8b6a-f5b97b32b987.png)

This is consistent between genders.

![image](https://user-images.githubusercontent.com/93338132/161447533-79528309-3301-4071-a849-b1e659249bb8.png)

Weekday trips are concentrated during rush hors and weekend trips are spread throughout the day

![image](https://user-images.githubusercontent.com/93338132/161447018-f9ab8e57-ddaf-4370-ab52-6af8d0847182.png)

Gender does not seem to affect trip timing as much as trip volume.

![image](https://user-images.githubusercontent.com/93338132/161447390-4da21c55-7e18-44e9-9e89-97812a560525.png)

Trips are concentrated in Manhattan (New York County), especially south of Central Park, which is the densest area of New York. Brooklyn (Kings County) also sees some trip density in its most populated neighborhoods

![image](https://user-images.githubusercontent.com/93338132/161447178-c59dfdfa-acc1-411b-b918-629aab43567b.png)

### Additional Considerations
New York City is one of the top tourist destinations in the world - Des Moines is not. Therefore, it is important to better understand the effect of tourism on the Citi Bike data so we can adapt our strategy to serve a customer base with different needs. Guest customers are more likely to be tourists, inferred from their trips starting near major attractions more than subscribers and from their trip timing, outlined below. Not all guest customers are tourists, but we can make some directional judgements based on the below.

Guest trips are concentrated on weekends

![image](https://user-images.githubusercontent.com/93338132/161447339-ff480655-a07a-427f-827b-36f4e30fcaf6.png)

Subscriber trips are concentrated on weekdays, but there is considerable weekend volume

![image](https://user-images.githubusercontent.com/93338132/161447366-8e8fded0-b635-4d03-81b4-4d0f4002dfad.png)

### Summary 
Overall, the NYC Citi Bike business thrives in Manhattan and the densest parts of neighboring Brooklyn. Both of these areas are wealthier and more densely populated than other parts of the city. Most users are male and most users are subscribing, repeat customers. Trips are concentrated in dense areas and near major points of interest. 

To adapt this business for Des Moines, we can make assumptions based on these findings. We should concentrate bikes in the Downtown area and near major destinations like the river, Capitol or the Botanical Garden. 
