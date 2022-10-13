This project involves the use of K-Means Clustering to find the best accommodation for students/office-goers in Pune by classifying accommodation for incoming students on the basis of their preferences on amenities, budget and proximity to the location.

I divided the project into 5 parts-
1. Getting Started-I loaded the food coded dataset into a pandas dataframe and looked at its attributes.
2. Data Exploration and Visualisation-I did some basic preprocessing of the data and visualised it into a boxplot.I had a boxplot of the cleaned dataset and could make some insights looking at it.
3. K Means Clustering- I ran K Means Clustering on the dataset and used trial and error to get the best value of K.I had the optimum K value for the dataset, and the parameters on which the clusters are differentiated.
4. Getting Geloloactional API-I used FourSquare API to get Gelolocational data.After doing some basic preprocessing on the geolocational data,I had a dataframe with the locations (in latitude, longitude) format, along with the counts of how many amenities are present around each location.
5. Plotting the clustered locations on a map-I again applied K Means on the dataset of the locations which we chose, which will help us find the best location for each population group that we found in Task 3.Then I used Foliumto plot my results on the map of a world,centered on Pune

# Boxplot
![boxplot_kmeans](https://user-images.githubusercontent.com/76242216/195570230-7a9063f9-3346-4b09-a15b-a8b2c21263d2.png)

From This Boxplot,we can see different characteristics of people based on their income.Lower Income people tend to eat out less,look for cheaper options while eating out,
