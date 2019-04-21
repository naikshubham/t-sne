
# t-distributed stochastic neighbor embedding

#### Description 
- T-distributed Stochastic Neighbor Embedding (t-SNE) is a machine learning algorithm for visualization developed by Laurens van der Maaten and Geoffrey Hinton.[1] It is a nonlinear dimensionality reduction technique well-suited for embedding high-dimensional data for visualization in a low-dimensional space of two or three dimensions. Specifically, it models each high-dimensional object by a two- or three-dimensional point in such a way that similar objects are modeled by nearby points and dissimilar objects are modeled by distant points with high probability.

#### Dataset used for Visualization <br>

- Credit Card Fraud Detection dataset : The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. 
- Dataset can be downloaded from kaggle or the below link: https://www.kaggle.com/saimarapareddy/credit-card-fraud-detection/data

#### Color coding used
- Orange : Class 1 -> which consitute of Fraud transactions.
- Blue   : Class 0 -> which consitute of Non-Fraudlent transactions.



#### The t-SNE algorithm comprises two main stages.<br>

- First, t-SNE constructs a probability distribution over pairs of high-dimensional objects in such a way that similar objects have a high probability of being picked, whilst dissimilar points have an extremely small probability of being picked.<br>

- Second, t-SNE defines a similar probability distribution over the points in the low-dimensional map, and it minimizes the Kullback–Leibler divergence between the two distributions with respect to the locations of the points in the map.

### Results

#### Below are the t-sne visualization results
- For perplexity = 30 and step = 5000 on 10000 samples
<img src="t-sne graph perplexity 30.png">

- For perplexity = 50 and step = 5000 on 10000 samples
<img src="t-sne graph perplexity 50.png">

- For perplexity = 100 and step = 5000 on 10000 samples
<img src="t-sne graph perplexity 100.png">

