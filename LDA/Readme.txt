Introduction

In this notebook, I shall conduct a very basic attempt at topic modelling this Spooky Author dataset. Topic modelling is the process in which we try uncover abstract themes or "topics" based on the underlying documents and words in a corpus of text. I will introduce two standard topic modelling techniques here with the first technique known as Latent Dirichlet Allocation (LDA) I will also take the opportunity to introduce some Natural Language Processing basics such as Tokenization, Stemming and vectorization of the raw text which should also hopefully come in handy when making predictions with learning models.

The outline of this notebook is as follows:

Exploratory Data Analysis (EDA) and Wordclouds - Analyzing the data by generating simple statistics such word frequencies over the different authors as well as plotting some wordclouds (with image masks). Natural Language Processing (NLP) with NLTK (Natural Language Toolkit) - Introducing basic text processing methods such as tokenizations, stop word removal, stemming and vectorizing text via term frequencies (TF) as well as the inverse document frequencies (TF-IDF)

Topic Modelling with LDA.
