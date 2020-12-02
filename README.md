# Dynamic-Word-Embeddings
A word2vec model that stitches together multiple models through Procrustes alignment along a time series. Enables diachronic analysis of words. 
<br/>
Process includes:
1. Splitting dataset into time segments
2. Generating gensim model for each time segment
3. Use Procrustes alignment to initliaze the models
4. Visualize the Cosine Distance over time from the first year

Results:

![](/
