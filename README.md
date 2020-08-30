Medium Post Link:  https://medium.com/@puneet.gajwal99/twitter-sentiment-and-time-series-analysis-e032f8b0f951

# Twitter-Unsupervised-Sentiment-Analysis-and-Time-Series-Visualization

In this project, there are several notebooks and images for whose description is necessary.

1: Time Series.ipynb: Here I considered time as an important parameter to get insights of the data. There were several plots associated with this notebook such as hour vs tweets.png, tweets per hour.png , tweets per year.png. I also did one visualization with Tableau as it was more convenient there. Had done few visualizations actually but only one felt to be relevant.

2: Word Cloud.ipynb :  As the name suggest, I created word cloud from the vocabulary that we had. Idea was to create word cloud from most frequent words but due to memory constraint, I was only able to select random 100 words from our vocabulary and create word cloud from that.

3: Word2Vec.ipynb: This is where I did most of the work. Here, entire data was used to create vocabulary. I only considered "tecxt" part of the data and carried out all the operations on that. I used SnowballStemmer as it always does the job right and removed stop words. Also used Rejex library from python which removes whatever you want from data and finally after all the cleaning, I created my word2vector representation of vocabulary.

4: K-Means.ipynb: Here I used our saved word2vec representation of vocabulary to train K-Means model which was the first one to predict the sentiment. Only if time allowed, I would've moved to some advance clustering algos such as DBSCAN. I wanted it to be simple. I made prediction for each word in my Vocab to find if it has a positive or a negative sentiment.

5: KMeans with TF-IDF.ipynb: As the name says, this notebook just contains KMeans but the vector was created with with TF-IDF and then the predcition was made.

If time and memory were not the concern, better approaches and more fine tuning of vecctor representation of our vocabulary could've been achieved.
