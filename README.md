# Sentiment-Analysis-on-IMDB-Movie-Reviews---Python-Projects
Sentiment Analysis on IMDB Movie Reviews This project demonstrates my understanding on:

Data collection
Data Scraping on website for this project i scrapped data on (IMDB website to gather movie reviews and ratings).
Inspecting the underline HTML structure of the web page and extracting the information.
Formatting required information and write to a csv file.
Text data analysis
Perform text (pre-)processing.
Applying stopwords and stemming functions.
Visualising reviews through WordCloud.
Performing sentiment analysis on the processed reviews using VADER.
Applying machine learning for sentiment prediction.
Applying and evaluating different approaches for sentiment prediction.
Interpreting the results of findings and draw conclusions.
The Dataset: In this project, i used IMDB reviews and ratings for sentiment analysis. Using a sentiment analysis tool called VADER (Valence Aware Dictionary and Sentiment Reasoner). VADER is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media. The lexical features (e.g., words) are generally labelled according to their semantic orientation as either positive or negative. It provides compound sentiment scores i.e., it tells us about how positive or negative a sentiment is.

The Task: I completed the following sub-tasks:

Data collection: I scraped 'user reviews' and 'ratings' of the movies from IMDB website through Quiz. Picked movies with more than 100 reviews to gather sufficient data to complete the task.

Report: I wrote a summary on the evaluation and the interpretation of the results. Evaluating the sentiment predictions using VADER sentiment analyser and machine learning against 'User Rating'. I also explained my understanding with the help of examples, the reviews that were correctly classified and reviews that were incorrectly classified; and formed discussions around them to discover why reviews are incorrectly or correctly classified. Picked up on incorrectly predicted sentiments and discussed the possible reasons of mis�classifications. Such as reviews with subtle use of positive and negative words or opinions. Provided the limitations of the tools or methods used that could have caused inconsistent results.

**Link of Actual Python Project**

http://localhost:8888/notebooks/Sentiments%20Analysis%20on%20IMDB%20Movie%20Reviews.ipynb

**URLs of the Movies Analyzed**

#Movie 1 Shutter Island url1 = 'https://www.imdb.com/title/tt1130884/reviews/?ref_=tt_ql_urv' #Movie 2 Platoon url2 = 'https://www.imdb.com/title/tt0091763/reviews/?ref_=tt_ql_urv' #Movie 3 Okkadu url3 = 'https://www.imdb.com/title/tt0366840/reviews/?ref_=tt_ql_urv' #Movie 4 Padaiyappa url4 = 'https://www.imdb.com/title/tt0213969/reviews/?ref_=tt_ql_urv' #Movie 5 Jaws 3-D url5 = 'https://www.imdb.com/title/tt0085750/reviews/?ref_=tt_ql_urv' #Movie 6 Mahanati url6 = 'https://www.imdb.com/title/tt7465992/reviews/?ref_=tt_ql_urv' #Added Shutter Island Rating 1 to balance my positive and negative reviews url7 = 'https://www.imdb.com/title/tt1130884/reviews?sort=curated&dir=desc&ratingFilter=1'
