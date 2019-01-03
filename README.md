# Content based recommendation system based on [Kaggle Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
In `EDA` notebook data is explored, cleaned and preprocessed to be more consistent for recommendation system.
In `simple_rec` notebook simple content based recommendation system is developed. This system uses movie metadata, such as genre, director, actors and description of a plot to find similar movie. Those factors can be weigthed to become more important in recommendation. Usage of metadata except description of a plot is a pretty straightforward. Description of a plot is moved in vector representation using different approaches. Bag of words, tf-idf, mean of word embeddings, mean of weighted by tf-idf word embeddings and  text embeddings. All of them produce similar result, but combined recommendation seems to be more accurate.
 
 ### Example of recommendations
 ![](/recommendations/A%20Fistful%20of%20Dollars.png?raw=true)
 ![](/recommendations/Fargo.png?raw=true)
 ![](/recommendations/Looper.png?raw=true)
