# About Project
In this project, I have done an experiment with K-Means Clustering Algorithm (or Unsupervised Machine Learning) on the famous iris dataset.
As we know, the iris dataset has 3 target labels viz. iris setosa, iris versicolor and iris virginica labeled as 0, 1 and 2 respectively, I have given the clustering algorithm only the features of the iris dataset to get the predicted labels and to compare with the true ones. 

# Data Used
The data used is the iris dataset available in the sklearn library itself.
I have worked with only the petal features(length and width) in this experiment.

# Model training and predictions
I have trained the model(KMeans) with the data and have plotted the predictions along with their predicted labels(using colors as the respective clusters) with the help of Matplotlib.

# Further improvements
I have applied the Elbow Method to find out the optimum value for n_clusters and further even scaled down the features using MinMaxScaler.
