# Cryptocurrencies
In this project, we assisted the senior manager, Martha, at Accountability Accounting in preparing a report of the cryptocurrencies 
that are in the trading market. We used Unsupervised Machine Learning methods to classify the vast amount of cryptocurrencies that are 
currently in the market.

The Steps to Preparing and Analyzing the Cryptocurrency Data Include:
1. Data Preprocessing
    - Load data in a Pandas dataframe
    - Remove irrelevant data such as cryptocurrencies that aren't trading.
    - Remove any cryptocurrencies with null values.
    - Remove non-numerical features that are unnecessary in our analysis.
    - Process data so that it can be run through a machine learning model.
    
2. Reducing Data Dimensions using PCA
    - Use a PCA algorithm the reduce the dimensions to 3 principal components.
    - Input results onto a new dataframe.
  
3. Clustering Cryptocurrencies Using K-Means
    - Visualize PCA Data Frame on Elbow Curve to determine best K value for K-Means Algorithm.
    - Run K-means Algorithm on PCA dataframe.
    - Create a DataFrame including the preprocessed dataframe, the PCA dataframe, and the Class results from K-Means Algorithm.
  
4. Visualizing Results
    - Create 3D scatter plot to display PCA clusters with cryptocurrency name and data for each point.
    - Create a data table with all the current tradeable cryptocurrencies.
    - Create a scatter plot to present the clustered data showing the contrast of the number of available coins versus the total number of mined coins.
