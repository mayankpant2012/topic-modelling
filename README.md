# topic-modelling
This project is based on Natural Language Processing(NLP). The project deals with extracting topics for news articles and also extract details such as person name, location and organization for each story.

Execute the topic_modelling_NLP.ipynb file to run the project.

Dataset – The dataset contains two files Startup_data.xlsx and cities_r2.csv

- The cities_r2.csv file would help in finding the names of cities in each news article.

<h3>The attributes of Startup_data.xlsx are:-</h3>

1. STARTUP NEWS -> The news article posted online on website (HEADLINE).
2. SUMMARY -> A shorthand summary of the news article.
3. POSTED BY -> Name of person who posted the startup news.
4. DESCRIPTION -> The complete information or story of that news.

The project makes use of the Latent Dirichlet allocation(LDA) algorithm, to carry out the topic modelling task.

Named Entity Recognition(NER) is used to extract details such as person name, location and organization for each story.

Tools used:
1. Python (3.7.1)
2. Jupyter Notebook (4.4.0)
3. pandas (0.23.4)
4. NumPy (1.15.4)
5. implementation of NLP using: spaCy (2.1.6)
6. implementation of LDA using: Gensim (3.8.0)

