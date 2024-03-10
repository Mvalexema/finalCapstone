# **Sentiment Analysts of Amazon Product Reviews**
*Dataset: Datafiniti Consumer Reviews of Amazon Products*
* The file sentiment_analysis.ipynb represents the sentiment analysis using Python functions. 
The sentiment analysis is focused on the calculation of the sentiment measures and the representation of results in a useful for the user way.
* The file represents a Jupyter Notebook and contains several blocks: import of libraries, description of functions, and graphical representation of results.
* The dataset Datafiniti_Amazon_Consumer_Reviews_of_Amazon_Products.csv is sourced from [kaggle.com] (https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products) and represents a CSV file.
* The CSV dataset is preprocessed using dropna and stop_words functions.
* The sentiment analysis uses the polarity function and calculates cumulative polarity for each sentence and the whole dataset to represent the final scores.
* The positive and negative words in the dataset help to represent the results using TextBlob and WordCloud.
* The analysis also calculates the standard deviation to check the statistical meaning of the result and concludes the positive sentiment of the dataset.
* The installation and usage of the file will require Jupyther Notebook and the installation of libraries such as Pandas, Numpy, SpaCy, TextBlob.