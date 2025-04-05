## Movie Recommendation System with Sentiment Analysis
This project is a web-based Movie Recommendation System that provides personalized movie suggestions along with movie posters, trailers, and review sentiments to enhance user experience.

## Project Overview
This system combines content-based recommendation and sentiment analysis to suggest movies that users are likely to enjoy. It also fetches real-time data such as posters, trailers, and reviews from the TMDb API, offering a rich and interactive movie discovery experience.

##  Features
🔎 Personalized movie recommendations using TMDb metadata

🧠 Sentiment analysis on TMDb user reviews to classify movies as Positive or Negative

🎥 Embedded YouTube trailers for suggested movies

🎞️ High-quality posters retrieved from TMDb

📊 Simple and interactive web interface built with Flask

🧰 Pickle file for pre-trained sentiment model included

## Dataset Used
Source: TMDb Movie Dataset - Kaggle

The dataset includes movie titles, genres, overviews, ratings, popularity, and other metadata used for generating content-based recommendations.

## Tools and Technologies
Python, Flask for backend and web framework

Pandas, Scikit-learn for data processing and model training

NLTK/TextBlob/VADER (depending on your setup) for sentiment analysis

TMDb API for movie posters, trailers (via YouTube links), and reviews

HTML/CSS for frontend design

## TMDb API
This project uses the TMDb API to:

Retrieve movie posters dynamically

Fetch YouTube trailer links

Collect and analyze user reviews for sentiment classification

## Note: You'll need a TMDb API key to run this project. You can get one by creating an account at https://www.themoviedb.org and generating an API key.
