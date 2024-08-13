# Twitter-Sentiment-Analysis
A Python script that analyses sentiment on a given topic from tweets data provided by Twitter.
Getting Started
The project requires authentication via the Twitter API. A new application needs to be created to get the necessary keys. A few libraries also need to be installed for the script to run properly.

Prerequisites
Tweepy, the official Python library for accessing the Twitter API
TextBlob, a Python library for processing textual data
NLTK dataset, to help better natural language processing
Keys from the Twitter Developer Application Management site
Consumer key
Consumer secret
Access token
Access token secret
Installing
The Tweepy library can be installed by using the command

pip3 install tweepy

The TextBlob library can be installed using

pip3 install textblob

The NLTK corpora can be downloaded by using the following command

python3 -m textblob.download_corpora
These files will provide better natural language processing capabilites for the TextBlob library.

Note: A missing cerificate error can arise when trying to download the NLTK corpus files. To fix the issue, navigate to the Python folder /Applications/Python 3.6 and run the Install Certificates.command file.


To obtain the consumer keys and access tokens from the Twitter Dev Application Management site, a new app needs to be created using a Twitter account.

Open apps.twitter.com and use the Create New App button.
Complete the form with the necessary application details. The application name must be unique.
Navitgate to the Keys and Access Tokens tab.
Copy Consumer Key, Consumer Secret, Access Token and Access Token Secret and update the variables consumer_key, consumer_secret, access_token, and access_token_secret in the sentiment_analysis.py file accordingly.


