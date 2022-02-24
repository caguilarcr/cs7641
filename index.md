# NBA Game Prediction Models Analysis

## Introduction

Being a sports analyst requires one to efficiently predict outcomes of games and figure out which players are most likely to score high number of points, provide assists, gather rebounds, etc. in each team. 

Another problem for analysts is figuring out which players to draft/trade who can positively impact the winning probabilities of one’s team by gelling with the given set of players. 

We try to tackle the two objectives above by using various ML approaches and figure out which performs the best.

**We found the following papers relevant to our initial analysis:**

[1] uses Hybrid Fuzzy-SVM (HFSVM) model. A fuzzy membership function is applied to the input data which makes different contributions to the decision surface learning. This enhances SVM to reduce the effect of noise and outliers. But HFSVM like SVM is not suitable for large datasets. [2] Used a dataset of 650 matches to predict National Basketball Association (NBA) results. The paper uses Bayesian Belief Networks, Feed Forward Neural Networks, Probabilistic Neural Networks, Generalized Neural Networks, among others. Their model was able to outperform experts from USA Today. [3]'s approach relies heavily on feature independence assumption. They have used Naive Bayes to predict winning and linear regression to predict the spread. Variable selection is used to limit the number of features. 

All three aproaches lack application of dimensionality reduction, application of diverse set of classifiers (that don’t rely on feature independence assumption etc.) and count based Poisson regression models. We also plan to use a dataset which is 3 times bigger than the dataset used in these three.

## Problem Definition

As an initial analysis we would try to predict probability of winning.

However, if this proves to be less challenging than expected we have the following problem in mind:

* Clustering players based on performance and playing type, to suggest best transfers for a team.
* Visualize (and encode) the composition of player types in known successful teams and use these to suggest new players.

## Methods

We plan to use the following methods:

* Dimensionality Reduction – PCA, UMAP etc.
* Clustering – DBSCAN, HDBSCAN, K-Means, GMM etc.
* Prediction - Regression analysis, SVM, Logistic Regression, Neural Networks, Boosting/Bagging methods etc.


## Potential Results


## Proposed Timeline
![Timeline](/assets/ganttchart.png)

## References

[1] 	[H. Kaur and S. Jain, "Machine Learning Approaches to Predict Basketball Game Outcome," 2017.](https://ieeexplore.ieee.org/document/8344688)

[2] 	[B. Loeffelholz, E. Bednar and K. W. Bauer, "Predicting NBA Games Using Neural Networks," Journal of Quantitative Analysis in Sports, vol. 5, no. 1, 1 2009.](https://www.degruyter.com/document/doi/10.2202/1559-0410.1156/html)

[3] 	[D. Miljković, L. Gajić, A. Kovačević and Z. Konjović, "The use of data mining for basketball matches outcomes prediction," SIISY 2010 - 8th IEEE International Symposium on Intelligent Systems and Informatics, pp. 309-312, 2010.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5647440)
