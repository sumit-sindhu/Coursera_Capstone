# Coursera Capstone: IBM Applied Data Science Capstone

## Opening a New Restaurant In Mumbai, India

### Business Problem
- Location of the restaurant is one of the most important decisions.
- **Objective:** To analyze and select the best locations in the city of Mumbai, India, to open a new restaurant.
- **Business question:** In the city of Mumbai, if a property developer is looking to open a new restaurant, where would you recommend that they open it?

### Data
- **Data required:**
    - List of neighborhoods in Mumbai
    - Latitude and longitude coordinates of the neighborhoods
    - Venue data, particularly data related to shopping malls
- **Sources of data:**
    - [Wikipedia page for neighborhoods](https://en.wikipedia.org/wiki/Category:Suburbs_of_Mumbai)
    - Geocoder package for latitude and longitude coordinates 
    - Foursquare API for venue data

### Methodology
- Web scraping Wikipedia page for neighborhoods list
- Getting latitude and longitude coordinates using Geocoder
- Using Foursquare API to get venue data
- Grouping data by neighborhood and taking the mean of the frequency of occurrence of each venue category
- Filtering venue category by Restaurant
- Performing clustering on the data by using k-means clustering
- Visualizing the clusters in a map using Folium

### Results
K-means clustering shows 5 clusters based on the frequency of occurrence for “Restaurant”:

- **Cluster 0 and Cluster 4:** Have the most number of restaurants while clusters 1, 2, and 3 have a moderate number of clusters.
- Restaurants in Cluster 0 and Cluster 4 have the most competition while restaurants in clusters 1, 2, and 3 have moderate competition. 
- This represents a great opportunity for a person to open a restaurant in these areas.
- While Clusters 0 and 4 have an oversupply of restaurants, they may have an adequate amount of customers due to that area being well developed. But the other areas are also well developed and have an undersupply of restaurants. So it is a great opportunity to open a restaurant there.



### Conclusion
- The neighborhoods in Cluster 1 or 3 are the most preferred locations to open a new restaurant.
- Findings of this project will help the relevant stakeholders to capitalize on the opportunities on high potential locations while avoiding overcrowded areas in their decisions to open a new restaurant.

