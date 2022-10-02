# Cryptocurrencies

# Overview of Project

Cryptocurrency is a digital currency which is an alternative form of payment created using encryption algorithms. With so many different versions of digital currency, where does one begin.

Unsupervised Machine Learning is used when you know you don't know the question you are asking of the data. In other words, unsupervised learning is used when there is no known output or used to discover patterns or groups in data.

The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies . A report will be created that includes the traded cryptocurrencies and classified by group according to featues for this possible investment. Features are the variables used to make a prediction.

 
This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.
The following methods for the analysis was used:

- Preprocessing the database,
- Reducing the data dimension using Principal Component Analysis,
- Clustering cryptocurrencies using K-Means,
- Visualizing classification results with 2D and 3D scatter plots.

# Resources

- Data Source: crypto_data.csv

- Software: Python and Jupyter Notebook

# Results

### Clustering Cryptocurrencies using K-Means - Elbow Curve

We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.

The elbow curve was preduced below using the K-Means method iterating on k values from 1 to 10.

![Elbow_curve]](https://github.com/acegal1/Cryptocurrencies/blob/main/images/elbow_curve.png)


The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

### Visualizing Cryptocurrencies Results

3D-Scatter plot with clusters

![3DPLOT](https://github.com/acegal1/Cryptocurrencies/blob/main/images/3DScatter_plot.png)

This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.

2D-Scatter plot with clusters

![Scatter_plot](https://github.com/acegal1/Cryptocurrencies/blob/main/images/2D-Scatter_plot.png)

This 2-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to two principal components.

Both these scatter plots show the distribution and the four clusters of cryptocurrencies.
We can identify the outliers like the unique cryptocurrency in the class #2.

### Tradable Cryptocurrencies Table

![Crypto Table](https://github.com/acegal1/Cryptocurrencies/blob/main/images/Trabable_Crypto.png)


# Summary
Identified 532 cryptocurrencies classifications based on similarities of their features. Features are the variables used to make a prediction. Particularities of each group need to be analyzed to determined their performance and potential interest. 

