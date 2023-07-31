# CanadaPostReview_SentimentAnalysis
## Problem Statement and Scope
### Problem Statement 
The problem we aim to address in this data science project is to perform sentiment analysis on customer reviews for Canada Post. By analyzing a diverse set of reviews from Google, Reddit, and Trust Pilot, we seek to gain valuable insights into the perceptions of customers towards each courier service.
### Scope
1. Data Collection: Collected sample dataset of customer reviews from Google reviews, Reddit, and Trust Pilot.
2. Sentiment Analysis: Utilized NLP techniques and LDA and SIA, and classified the sentiment of each review as positive, negative.
3. Cross-Platform Comparison: By comparing sentiment scores, identified variations in customer feedback and assessed the impact of platform-specific factors on customer perceptions.
4. Thematic Insights: Went beyond sentiment and extracted common themes and topics mentioned in positive and negative reviews for each company (service, convenience, damages and waiting times). 
5. Actionable Recommendations: Based on findings, provided actionable recommendations to Canada Post, for enhancing customer satisfaction and optimize their courier services.

## Data Scraping 
The reviews data were scraped with three different methods. The GoogleReviews data were scraped by INSTANT DATA SCRAPER, Reddit by Reddit API and TrustPilot by Selenium WebDriver. 

## Libraries 
Re for removing special characters in reviews\n
nltk

Stopwords (nltk.corpus) for identifying stopwords
SentimentIntensityAnalyzer (nltk.sentiment) for performing sentiment analysis on text
TfidfVectorizer (sklearn.feature_extraction.text) for converting text documents into numerical feature vectors 
LatentDirichletAllocation (sklearn.decomposition) for Topic Modelling

## Conclusion
![image](https://github.com/masonma99/CanadaPostReview_SentimentAnalysis/assets/108998129/8e01e43f-a859-4e1c-894a-48b59645670c)
