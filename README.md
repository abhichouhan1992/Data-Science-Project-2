# Data-Science-Project-2
Mall Customers Segmentation using K-Means clustering
# Introduction
The dataset used is of Mall customers which has 200 samples with there features; CustomerID genre,age, annual income and spending score.
# Problem Domain
We have Csv file of Mall_Customers dataset and now we see There are 5 features in dataset.one feature is in string form and remaining are in numerical form.All features are independent of each other so Unsupervised Machine Learning is best for making model.
# Solution Domain
For Mall Customer dataset K-means Clustering Algorithm is used. Since this algorithm works on forming clusters with similar ,where data points within each cluster are more similar to each other than to those in other clusters. it's main aim is to minimize the variance within each cluster. The term ‘K’ is a number,
"For example if K = 2 it refers to 'two' clusters".
Two points are assigned as centroids.
(For every point, the distance is measured from both the centroids, and whichever distance is less, that point is assigned to that centroid)
Simple and easy to implement: The k-means algorithm is easy to understand and implement, making it a popular choice for clustering tasks.
Fast and efficient: K-means is computationally efficient and can handle large datasets with high dimensionality. Scalability: K-means can handle large datasets with a large number of data points and can be easily scaled to handle even larger datasets. 
Flexibility: K-means can be easily adapted to different applications and can be used with different distance metrics and initialization methods.
# Technology Used
We used Jupyter Notebook for Iris dataset algorithm and also used diffent types of library from python such as numpy, pandas ,matplotlib, seaborn and Scikit-Learn. 
# Conclusion
In conclusion, K-means clustering is a powerful unsupervised machine learning algorithm for grouping unlabeled datasets. Its objective is to divide data into clusters, making similar data points part of the same group.The algorithm initializes cluster centroids and iteratively assigns data points to the nearest centroid, updating centroids based on the mean of points in each cluster.
Real life example:-
Customer segmentation in marketing, where k-means groups customers based on purchasing behavior ,allowing businesses to tailor marketing strategies for different segments.
Academic Performance:-Based on the scores, students are categorized into grades like A, B, or C. 
Diagnostic systems:-The medical profession uses k-means in creating smarter medical decision support systems,especially in the treatment of liver ailments.
Search engines:-Clustering forms a backbone of search engines. When a search is performed ,the search results need to be grouped, and the search engines very often use clustering to do this. 
Wireless sensor networks:-The clustering algorithm plays the role of finding the cluster heads ,which collect all the data in its respective cluster.
