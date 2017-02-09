Basic concepts in Machine Learning
----------------------------------

1. Supervised Learning
  1. Learning from labeled examples - e.g. sentiment prediction - given sentences labeled as positive or negative train a model which classifies a new sentence
  1. Regression - model outputs a continuous valued output - say predicting price of a house given past data
    1. Linear models
    1. SVMs
    1. Neural nets
  1. Classification - model assigns class labels to inputs - e.g. given an image say whether it is an apple or an orange.
    1. Logistic regression
    1. SVM
    1. Neural nets
    1. Decision trees
    1. Random forests
1. Unsupervised learning
  1. Learning from unlabeled data - e.g. say we have 3 sizes of shoes - and we want to find the optimal sizes so that most of the users fall into one of these buckets. One way is to run a clustering algorithm that identifies 3 clusters with the property that the points within a cluster are as close as possible and points in different clusters are as far as possible.
  1. Clustering
    1. K-means
  1. Dimensionality reduction
    1. Principal component analysis
1. Reinforcement learning
  1. e.g. a program which learns to play checkers by playing many games against itself or other opponents
