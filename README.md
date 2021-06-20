# [Analyzing-Millions-of-NYC-Parking-Violations](https://github.com/OjeWilliams/Analyzing-Millions-of-NYC-Parking-Violations)

This project involves interacting and analyzing NYC parking violations over the last decade through the Socrata Open Data API. To achieve this I utilized a EC2 instance from Amazon Web Services, the Linux terminal, Docker, Elasticsearch and finally Kibana.

Parking tickets are a headache for most people but for some states it's a tremendous money maker with them raking in millions if not billions in fees and fines. Luckily, we are afforded a chance to analyze this data through NYC Open Data which is a free public data site which offers an api for this very purpose. The Open Parking and Camera Violations api is a very large data source that can be much more easily and efficiently handled through cloud computing and thats what we plan to do here. <br />

The Average Payment,Fine and Penalty amount over the last decade
  ![](/images/YearlyAvgs.png)

<br />

The Top 50 Parking Violations Wordcloud
  ![](/images/TopViolations.png)
  <br />


Total Dashboard
![](/images/kibanadashboard.png) 
 <br />
  <br />


# [Analyzing Yelp Reviews Dataset](https://github.com/OjeWilliams/Analyzing-Yelp-Reviews-Dataset/blob/main/README.md)
 This project involves diving into a dataset of [Yelp](https://www.kaggle.com/yelp-dataset/yelp-dataset) reviews and seeing what interesting things we can find. The dataset is a collection of Yelp's reviews, user data and businesses across 8 metropolitan areas in the USA and Canada. The Yelp Dataset is a great resource for us to Extract, Load and Transform as a Big Data project. The dataset is quite large (11gb) and therefore to investigate it we will leverage a Spark Cluster on AWS EMR for loading the data as well as an S3 bucket for uploading the data while all analysis was completed using Pyspark, SQL inside a Jupyter Notebook. 
As part of the analysis I investigated the skewness of the data as well as the trustworthyness of Elite reviews.

Top Business Categories 
![](/images/Top-Categories-by-Business.png)
<br />

Yelp Review Skewness
![](/images/Yelp-Review-Skewness.png)
<br />

Review Comparison
![](/images/Review-Comparison.png)
<br />
<br />

# [Game of Thrones Script Analysis](https://github.com/OjeWilliams/NLP_Analysis)
Game of Thrones (GOT), is a fantasy drama television series that contains 73 episodes in 8 seasons. We analyzed a complete set of the script from all the characters for all seasons through Natural Language Processing techniques such as sentiment analysis, aspect mining, tokenization, and Named Entity Recognition (NER). We tackled topics such as the change in main characters' sentiment, frequent words used in each family, and the comparison of the word usage of the two main characters. This allowed us to provide better and deeper insights to the audience. The GOT script analysis can help the audience understand the impact of each main character such as Tyrion, classify the attitude of each family, and learn alot about any of the main characters in 10 mins or less.

Most Talkative Characters
![](/images/Talkative.png)
<br />
<br />

Sentiment Spread
![](/images/Sentiment-Spread.png)
<br />
<br />

Tyrions Sentiment Over the Series
![](/images/Tyrion.png)
<br />
<br />


# [Streaming Yahoo Finance Data with AWS Lambda](https://github.com/OjeWilliams/Streaming-Yahoo-Finance-Data-with-AWS-Lambda)
This project involves setting up a few AWS technologies to generate near real time finance data records for interactive querying. This will allow us to capture and analyze data that is being constantly generated in or near to real time. We will utilize the [yfinance](https://github.com/ranaroussi/yfinance) module that provides a suitable and effective way to download and view historical market data from [Yahoo! finance](https://finance.yahoo.com/).
  We will be taking a look at the following stocks: 
 - Facebook (FB), Shopify (SHOP), Beyond Meat (BYND), Netflix (NFLX), Pinterest (PINS)
 - Square (SQ), The Trade Desk (TTD), Okta (OKTA), Snap (SNAP), Datadog (DDOG)
 
The aim is to leverage an AWS Lamda function as well as AWS Kinesis, S3, Glue and Athena to capture data over a specific time period and run a few queries as well as provide some analsyis and visualizations.


