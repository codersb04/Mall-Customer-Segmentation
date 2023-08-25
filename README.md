# Mall-Customer-Segmentation
## Task:
Build a model to create different clusters using the mall customer data. **KMeans Clustering** is used in this task.
## Dataset:
The dataset is taken from Kaggle's "Mall Customer Segmentation Data Market Basket Analysis". Data set contains 200 data with 5 features. The features are:
1. CustomerID
2. Gender
3. Annual Income
4. Spending Score</br></br>
link: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
## Steps Involved:
### Importing Libraries:
libraries used here are:
1. numpy
2. pandas
3. matlplotlib.pyplot
4. seaborn
5. Kmeans from sklearn.cluster
### Data collection and Analysis:
1. Import data using read_csv function
2. Analyse the data using the head, info and shape function
3. Check for Missing value
4. Choosing the Annual Income and Spending Score column
### Find the number of Clusters:
1. Run a for loop between the values 1 and 10 as the number of clusters for the values of Annual Income and Spending Score
2. Get the values for WCSS(Within Clusters of Square: distance of centroid from each data points)
3. Plot the Elbow point graph and get the optimal number of clusters, which is 5 in this case.
### Training the K-Means Clustering Model:
1. Build the model using the optimal cluster value
2. Get the cluster number for each data point
### Visualizing the data point
1. Plot the clusters using a scatter plot with Annual Income on X-axis and Spending Score on Y-axis.
2. Plot the centroid along with the above plot</br></br></br>

Reference: Project 13. Customer Segmentation using K-Means Clustering with Python | Machine Learning Projects, Siddhardhan, https://www.youtube.com/watch?v=SrY0sTJchHE&list=PLfFghEzKVmjvuSA67LszN1dZ-Dd_pkus6&index=15
