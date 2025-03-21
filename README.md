<div style="text-align: left"> 

**Part 1-**

The CSE_569_Maximum_Likelihood_Estimation.ipynb file implements a 2 class classifier. The dataset is a subset of data from the MNIST dataset. The feature dimensions are reduced by Principal component analysis.
With the assumption that the data from each class is follows a multivariate normal distribution. We then use maximum likelihood estimation to estimate the mean and the covariance vector.
The MLE estimate of the densities is used to calcuate the the posterior probabilites of each class given a test data point.
Finally We make a classification decision as the class with the higher posterior probability.

**Part 2-**
CSE_569_MLP.ipynb file implements a 3 layer MLP. The loss function used is a MSE loss. A momentum term is also used to speed up convergence. We also plot the train, test and validation learning curves.
</div>
