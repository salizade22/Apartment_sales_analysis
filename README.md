# Research on apartment sales ads

You will have the data from a real estate agency. It is an archive of sales ads for realty in St. Petersburg, Russia, and the surrounding areas collected over the past few years.  Your task is to define the parameters. This will make it possible to build an automated system that is capable of detecting anomalies and fraudulent activity.

There are two different types of data available for every apartment for sale. The first type is a user’s input. The second type is received automatically based upon the map data. For example, the distance from the city center, airport, the nearest park or body of water. 

## Data Description 
* real_estate_data_us.csv:

| Column     | Description                                |
|------------|--------------------------------------------|
| airport_dist | the distance to the airport in meters (m.).|
|balconies | the number of balconies.|
|ceiling_height | the ceiling height in meters (m.).|
|city_center_dist | the distance to the Saint Petersburg center in meters (m.).|
|days_listed  | how many days the ad was displayed (from publication to removal).|
|date_posted | the publication date.|
|floor | the apartment floor number.|
|floors_total | the total number of floors in the building.|
|bike_parking | whether there is parking for bikes or not (Boolean type).|
|kitchen_area | the kitchen area in square meters (sq.m.).|
|last_price | the price at the time when the ad was removed (dollars).|
|living_area | the living area in square meters (sq.m.).|
|locality_name | the locality name.|
|is_open_plan | an open plan design (Boolean type).|
|parks_within_3000 | the number of parks in a 3 km. radius.|
|park_dist | the distance to the nearest park in meters (m.).|
|ponds_within_3000 | the number of bodies of water in a 3 km. radius.|
|pond_dist | the distance to the nearest body of water (m.).|
|bedrooms | the number of bedrooms.|
|is_studio | whether it's a studio or not (Boolean type).|
|total_area | the total area in square meters (sq.m.).|
|total_images | the number of photos of the apartment in the ad.|
