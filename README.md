# Cryptocurrencies

# Analysis Overview
The purpose of this project is to use unsupervised machine learning to analyze a cryptocurrencies database and identify tradeable cryptocurrencies according to their characteristics.

We use the following methods for the analysis:

preprocessing the database,
reducing the data dimension using Principal Component Analysis,
clustering cryptocurrencies using K-Means,
visualizing classification results with 2D and 3D scatter plots.

# Resources
Software: Python, Anaconda Navigator, Conda and Jupyter Notebook.

# Results

Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.

Clustering Cryptocurrencies using K-Means - Elbow Curve

We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.
We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.

![image](https://user-images.githubusercontent.com/90175232/152627858-71b7933f-b1c6-40b8-b48d-0406dff6979d.png)

The best k value is 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

# Visualizing Cryptocurrencies Results
3D-Scatter plot with clusters

![image](https://user-images.githubusercontent.com/90175232/152627903-e1e0d8ed-4eb3-4ff0-9208-f775c7154758.png)


This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.

2D-Scatter plot with clusters

![image](https://user-images.githubusercontent.com/90175232/152627916-8cfd17a8-40da-4ce2-a27e-d18c869bd187.png)


This 2-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to two principal components.

Both these scatter plots show the distribution and the four clusters of cryptocurrencies.
We can identify the outliers like the unique cryptocurrency in the class #2.

#Tradable Cryptocurrencies Table

Most of the cryptocurrencies are part of class #0 and #1.
The snapshot above shows that BitTorrent is the only cryptocurrency in class #2.

2D-Scatter plot with TotalCoinMined vs TotalCoinSupply


Plotting the scatter plot from two cryptocurrency features directly does not efficiently segregate the different classes. Then using the PCA algorithm is the right method for better visualizations.

Summary
We have identified the classification of 532 cryptocurrencies based on similarities of their features.
