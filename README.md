### To find the similarity score and matching string result of multi string columns, use difflib python library: https://docs.python.org/2/library/difflib.html

***Difflib.SequenceMatcher will provide scores by comparing strings in the columns.***

***Difflib.find_longest_match will provide matching partial string result:***

For more details, check the code.

***For string clustering on sentences, you can implement TF-IDF and K-means clustering method. 
The code is modified version of the code available from the post: http://www.lumenai.fr/blog/quick-review-on-text-clustering-and-text-similarity-approaches***

"Word embeddings are low dimensional vectors obtained by training a neural network on a large corpus to predict a word given a context (Continuous Bag Of Words model) or to predict the context given a word (skip gram model). The context is a window of surrounding words. The most known for word embeddings is Tomas Mikolov's Word2vec."

The great example of k-means clustering using tf-idf vectors with the scikit-learn implementation

***Read more about TfidfVectorizer: https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html***

***Read more about KMeans:
https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html***

