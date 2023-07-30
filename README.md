# Information-Retrieval-From-Food-Journals using LLMs
 Text files inside data folder contains metadata from around 5000 journal articles within the food technology sector. Within this data, you will see variables such as 'authors', 'journal', 'year' and 'abstract'. 
 Task is to import this data, analyse it using your NLP skills, highlight any conclusions or findings you make and display such output on a dashboard. 

# Directory Structure

- [Information Retrieval From Food Journals.ipynb](./Information%20Retrieval%20From%20Food%20Journals.ipynb): Notebook contains code related to analysis.
- [presentation_information_retrieval.pdf](./presentation_information_retrieval.pdf): A presentation about the analysis
- [charts](./Charts): Contains all the charts that were drawn on this project.
- [data](./data): Contains all the data files which are getting analyzed.


# Following are few insights that i have fetched form data-

# Abstract Basic Stats

![Chart](Charts/abstract_length_dist.png)
![Chart](Charts/unigrams.png)
![Chart](Charts/bigrams.png)

# Most frequent noun Phrases in abstract
![Chart](Charts/noun_phrases.png)

# Sentiment Ansysis on abstract
![Chart](Charts/sentiment.png)

# Topic Modelling Usin LDA

![Chart](Charts/lda.png)

# Top Keywords according to LDA
![Chart](Charts/lda_top_keywords.png)

# Topic Modelling Usin BERTopic
![Chart](Charts/bert_topic_cluster.png)
# Top Keywords according to BERTopic
![Chart](Charts/bert_top_keywords.png)
# Similarity between topics
![Chart](Charts/bert_topic_semilarity.png)
# Topic's trend over time
![Chart](Charts/bert_topic_over_time.png)

# Populer chamical componds being discussed
![Chart](Charts/top_chamicals.png)

# Populer food items being discussed
![Chart](Charts/top_foods.png)

# Top 10 Authors
![Chart](Charts/top_authors.png)

# Top 10 Journals
![Chart](Charts/top_journals.png)

# Top 10 Collaborations
![Chart](Charts/collaborations_freq.png)
