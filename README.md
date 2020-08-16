# Clustering neighborhoods in Toronto
This project aims to use Foursquare API to explore neighborhoods in Toronto City, Canada to get the most common venue categories in each neighborhood, and then use this feature to group the neighborhoods into clusters.

For the Toronto neighborhood data, a Wikipedia page exists that has all the information we need to explore and cluster the neighborhoods in Toronto. We will scrape the Wikipedia page and wrangle the data, clean it, and then read it into a pandas dataframe so that it is in a structured format.

We will use the k-means clustering algorithm to create the clusters of venues. Finally, we will use the Folium library to visualize the neighborhoods in New York City and their emerging clusters.

