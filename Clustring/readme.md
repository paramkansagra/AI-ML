Clustring is grouping unlabelled data

Supervised learning :- Regression and classification
    In supervised learning we have a test data and then we have some answer data
    we will feed the training input and we excpect a certain output only
    so here we are supervising the learning of the model

Unsupervised learning :- Clustering
    Here we dont have any answers the model has to think for itself what is the data and what could be the possible output for the same

K-Means clustering :-
    It is a centeroid based algorithm 
    In each cluster we have a centeroid and the main aim is to reduce the distance between the data points and the cluster they belong to

Steps:- 
    1. Select K number of clusters
    2. Select K random points as the centeroid of the clusters
    3. Assign each data point to their closest centroid, which will form the predefined K clusters
    4. Calculate the variance and place a new centroid of each cluster

    Repeat

Elbow method :- Optimized way of finding the number of clusters
    First apply the K means clustering N number of times and then do the elbow method to find the optimal number of clusters
    
    More the number of clusters less is the WCSS

K means++ :-
