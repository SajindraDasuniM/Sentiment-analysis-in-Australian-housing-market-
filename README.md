# Sentiment-analysis-in-Australian-housing-market-
One of the main objectives of this research is to analyze real estate news using NLP(Natural 
Language processing) to uncover key topics in real estate news in Australia. Another objective is 
to develop a prototype to identify the topics and sentiment trends over time.  
In this analysis, Selenium was used for web crawling to extract relevant data from trusted 
Australian news sources. News categories were identified using topic modelling (Gensim LDA 
model) and then MLP(Multilayer Perceptron) was trained to predict the topics for unseen articles 
with 91% overall accuracy. Finally pretrained BERT(distilbert-base-uncased-finetuned-sst-2
english) model was used for sentiment analysis to determine the behavior of each category over 
the time. Four main topics were identified related to real estate news. They are Construction and 
finance, Economic conditions, Government policy & investment and Property prices.  
