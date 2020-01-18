# Topic-Modelling-on-a-million-news-headlines
Extracting topics from a million news headlines using wordtovec and LDA


Topic Modelling from a million news headlines.
Media, journals and newspaper around the world everyday have to cluster all th data they have into specific topics in order to show the articles or news in a structured manner under specific topics. Imagine having a digital library where the books are randomly placed irrespective of their topics. How difficult it will be to search for them or search for the books that belomgs to specific topics we are interested in. Fortunately, we have deep learning and analytical tools to rescue us from these situations.

In this project, I am going to extract topics from a million news headlines sourced from the reputable Australian news source ABC (Australian Broadcasting Corp.). The dataset is available in Kaggle.

https://www.kaggle.com/therohk/million-headlines

Dataset Content

publish_date: Date of publishing for the article in yyyyMMdd format

headline_text: Text of the headline in Ascii , English , lowercase

Start Date: 2003-02-19 ; End Date: 2019-12-31

We will explore this in two ways:

1) In the first case, we will create embeddings for each headlines using 'Google News wordtovec embeddings' which takes care of the semantic and meaning and cluster the headlines into 8 clusters and see the most frequent words in the different clusters

2) In the second case, we will use LDA ( Latent Dirichlet Allocation) method to model the topics from these headlines. LDA assumes that each headline is taken from a nuber of topics and each topic consists fo several words.
