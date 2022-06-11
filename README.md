# MF810-Final-Project

## Sentiment Analysis on Open Research Data of COVID 19

For the sake of the great influence of the Covid-19 pandemic, there are thousands of relevant scholarly articles published. Our group members are curious about the attitude of the articles which imply if this pandemic would become better and better. Given such a background, in order to study the attitude of these articles in the process of the pandemic, our group decided to use sentiment analysis methods in this research. We assumed that the positive, negative, and neutral label of the articles titles and body text in the analysis can reflect the attitude of the scholar author toward the pandemic. 
Our study uses a freely available dataset on Kaggle offered by the White House and a coalition of leading research groups named the COVID-19 Open Research Dataset (CORD-19). CORD-19 is a resource of over 1,000,000 scholarly articles, including over 350,000 with full text, about COVID-19, SARS-CoV-2, and related coronaviruses. We aimed to utilize this dataset to analyze sentiment of the articles to have an insight into the attitude of the public towards the COVID.

## Data:
COVID-19 Open Research Dataset 
https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge

## Methodology: 
SQL, Spark, NLP techniques

## Implementation:
We mainly used Spark dataframe and RDDs to store the data and used both Pandas and Spark SQL for data manipulation. In this part, we will elaborate on the technical details, the challenges we faced and how we resolved in the following sections. 
Considering the data storage, data importing and code sharing issues, we conducted part of the computation processes on Google Colab. To monitor the time and condition for job execution, we also ran our code on Jupyter notebook in Docker.

## Reference sources:
https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge

https://www.kaggle.com/code/kowalskyyy999/pyspark-running-on-gpu

https://www.kaggle.com/code/davidmezzetti/cord-19-analysis-with-sentence-embeddings/notebook

https://www.kaggle.com/code/davidmezzetti/cord-19-population/notebook

https://www.kaggle.com/code/jswxhd/risk-factor-mining-cord-19-articles-2021#Topic-Extraction-II:-SentenceBert-+-K-Means-Clustering-+-TF-IDF

spark:
https://www.kaggle.com/code/acmiyaguchi/pyspark-dataframe-preprocessing-for-cord-19
https://www.kaggle.com/code/ashikm96/sentiment-analysis-covid-19-news-gdelt-pyspark
