# The-Android-App-Market-on-Google-Play

A projectinvolving loading, cleaning, and visualization of scraped Google Play Store data to understand the Android app market.

This project gives an opportunity to apply the skills from Intermediate Python and Data Manipulation with Pandas courses from 'Data Scientist with Python' specialization. (https://learn.datacamp.com/career-tracks/data-scientist-with-python?version=4).

The data for this project was scraped from the Google Play website. While there are many popular datasets for Apple App Store, there aren't many for Google Play apps, which is partially due to the increased difficulty in scraping the latter as compared to the former. The data files are as follows:

apps.csv: contains all the details of the applications on Google Play. There are 13 features that describe a given app.

user_reviews.csv: contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity.

