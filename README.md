# Likelihood-of-virality
Given a news article, predicting the likelihood of its virality.
I have used the library beautiful soup for crawling viral news headlines from The Times of India website.
Further, I have used word2vec for getting the representation of each word and used k-means algorithm to form clusters of the types of viral news.
According to the distance of the input news headline from the cluster centroids, I have predicted the likelihood of virality of the particular news.
