# Cool CryptoCurrency Cluster
![pexels-worldspectrum-1097947](https://user-images.githubusercontent.com/80294571/131062784-7a3c2628-6cd9-42d5-952e-5917ab9f277e.jpg)

## Background:
In this project, I will be using tools such as unsupervised learning and Amazon SageMaker to initiate clustering cryptocurrencies and to create plots that will present the results.
### Tasks:
1. **Data PreProcessing**: Prepare data for dimension reduction with PCA and clustering using K-Means
2. **Reducing Data Dimensions Using PCA**: Reducing data dimensions using the PCA algorithm from sklearn
3. **Clustering Cryptocurrencies Using K-Means**: Predict clusters using the cryptocurrencies data using the KMeans algorithm from sklearn.
4. **Visualizing Results**: Create plots and data tables to present the results

## Steps:
### Loading and PreProcessing Data:
1. Load data, create DataFrame w/neccessary coulmns
![image](https://user-images.githubusercontent.com/80294571/131064542-02db9a92-b63d-487d-8cd6-72e7d6c91eb3.png)
2. Remove rows with cryptocurrencies that don't have any coins mined
![image](https://user-images.githubusercontent.com/80294571/131064931-0aeed86d-32ba-45c5-b227-cf313cfe1f50.png)
3. Drop the "CoinName" column, it wont be used in the clustering algorithm
![image](https://user-images.githubusercontent.com/80294571/131065144-e5ecab38-c5a7-4909-a397-0abed6cf534e.png)

### Reducing Dimensions Using PCA:
1. Reduce dimensions to 3 principal components. Then load into DataFrame w/principle components data
![image](https://user-images.githubusercontent.com/80294571/131065477-535d61bc-4a09-4945-bb8d-491cb8e8c697.png)

### Clustering Cryptocurrencies Using K-Means:
1. Finding the best value for k using the Elbow Curve, using the inertia model
![image](https://user-images.githubusercontent.com/80294571/131065632-f83ee978-d6a3-4ebc-bc0a-a058f81936fa.png)
2. Initialized the K-Means model, fit eh K-Means model, create a DataFrame including predicted clusters & cryptocurrencies features
![image](https://user-images.githubusercontent.com/80294571/131065959-ca1c7945-de96-4371-8a16-f2415f0512cf.png)

## Data Visualization:
### Table of Cryptocurrencies:
![image](https://user-images.githubusercontent.com/80294571/131066060-624d71bd-903c-4904-8011-086a29593418.png)

### Scatter Plot of Cryptocurrencies:
![image](https://user-images.githubusercontent.com/80294571/131066167-385c65b0-ca70-4ce3-9ee4-b28c58f25f39.png)


