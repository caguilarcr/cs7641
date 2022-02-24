
## Introduction

[1] Predicts the outcomes of basketball games. The author improves on the shortcomings of SVM model by development of a Hybrid Fuzzy-SVM (HFSVM) model. A fuzzy membership function is applied to the input data which makes different contributions to the decision surface learning. This enhances SVM to reduce the effect of noise and outliers in data inputs directly reducing the net error effect. While HFSVM performs better than SVM for classification, it is still not suitable for large datasets. Therefore, we will explore several other methods including regression analysis, neural networks, random forests, etc. which often overcome the shortcomings of SVM/HFSVM.

[2]Describes an approach towards result and spread prediction in basketball. They have used the data from 2009/10 NBA season for modeling. Their approach relies heavily on feature independence assumption. They have used Naive Bayes to classify whether a team will win and linear regression to predict the spread. Variable selection is used to limit the number of features. The approach could be improved by using Dimensionality Reduction, a diverse set of more powerful classifiers that don’t rely on feature independence assumption, Poisson regression.

[3] Using a dataset of 650 matches to predict National Basketball Association (NBA) results. They used field-goal, three-point percentage, and free-throw percentage; offensive and defensive rebounds; points, turnovers, assists, steals, blocks, turnovers, personal fouls, and points. The authors tried prediction with Bayesian Belief Networks, Feed Forward Neural Networks, Probabilistic Neural Networks, Generalized Neural Networks, among others. They found that averages of variables in the current season performed better than average statistics across the past five matches. Their best correctly predicted the winning team 74.3% of the time on average, which was better than experts from USA Today 2008 who achieved 68.7%.


## Problem Definition

As an initial analysis we would try to predict probability of winning.
However, if this proves to be less challenging than expected we have the following problem in mind:
•	Clustering players based on performance and playing type, to suggest best transfers for a team.
•	We will use clustering to group players based on their performance (game level) data. Then visualize the composition of player types in known successful teams and use these to suggest new players.


## Methods

Dimensionality Reduction – PCA, UMAP etc.

Clustering – DBSCAN, HDBSCAN, K-Means, GMM etc.

Prediction - Regression analysis, SVM, Logistic Regression, Neural Networks, Boosting/Bagging methods etc.


## Potential Results

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam sed accumsan erat. Nullam id ligula consequat, imperdiet tortor vel, tempor lorem. Aenean mi lectus, sollicitudin nec urna non, lobortis pulvinar mi. Integer quam lacus, auctor at tellus ac, egestas malesuada mauris. Curabitur vehicula, leo ut semper pretium, diam nisl placerat nisl, nec suscipit dui neque sit amet sem. Donec blandit, odio varius condimentum mattis, augue neque posuere tellus, nec congue urna nisl vel dui. Donec fringilla erat vitae massa viverra ultrices. Pellentesque nunc dolor, feugiat ut mi ut, rutrum sagittis odio. Mauris ut convallis turpis, sit amet blandit neque. Suspendisse eu justo blandit, placerat odio vitae, tempor massa. Donec pulvinar cursus nisl, eu rutrum nulla congue vel. Nunc non dapibus nisi. Nunc non nisl at neque laoreet iaculis. Donec congue ligula non sem maximus, sit amet hendrerit lorem fermentum. Sed dapibus massa massa, at faucibus nisl pharetra id. Cras tristique tempor neque, quis hendrerit erat feugiat non.

Aliquam erat volutpat. Aliquam ac est at felis ullamcorper posuere sit amet et dui. Vestibulum semper faucibus mattis. Nullam urna mi, malesuada a turpis quis, semper ultrices nunc. Nam arcu elit, maximus at cursus eu, ultricies vel purus. Fusce sit amet lorem semper, venenatis velit sed, varius massa. Proin ut purus faucibus dolor ultrices pellentesque sit amet nec nibh. Fusce tincidunt aliquam lacus molestie pellentesque. Donec maximus magna nisl, at imperdiet augue molestie vel. Etiam nisl nulla, rutrum in accumsan ac, egestas vitae velit. Duis ornare tortor in nulla vulputate tincidunt. Mauris leo elit, egestas at sodales eu, auctor a justo. Vivamus diam eros, efficitur id felis quis, luctus pulvinar libero. Praesent imperdiet faucibus dapibus. Morbi quis risus libero. Maecenas pharetra eros ut metus tempor, nec egestas sem rutrum.



## Proposed Timeline
![Timeline](/assets/ganttchart.png)

## References
[1] 	H. Kaur and S. Jain, "Machine Learning Approaches to Predict Basketball Game Outcome," 2017.

[2] 	B. Loeffelholz, E. Bednar and K. W. Bauer, "Predicting NBA Games Using Neural Networks," Journal of Quantitative Analysis in Sports, vol. 5, no. 1, 1 2009. 

[3] 	D. Miljković, L. Gajić, A. Kovačević and Z. Konjović, "The use of data mining for basketball matches outcomes prediction," SIISY 2010 - 8th IEEE International Symposium on Intelligent Systems and Informatics, pp. 309-312, 2010. 

