# Sentiment_Bot_New
Hello, welcome to my Sentiment_Bot repo.
This Sentiment bot that uses Reddit's API to determine if a given subreddit is mainly positive or negative.

# Project Descrription 
I wanted to teach myself machine learning and am also new to python as well. So this is a little project to sharpen my skills.
The code itself isn't very efficient, I was just trying to get it to work.
This was a really fun project and I plan to update it in the future. 
### Things I want to add in the future would be...
- Using the data from the sentiment bot to train my own model of machine learning.
- Clean up the code and make it more efficient
- Make it more dynamic in the sense of using data from different apis

# Note
The project is not fully complete yet, I will be updating it as I work on it so the documentation is not complete yet.

# Setup
- I used reddits api in order to search and grab posts from subreddits. The documentation for that is [here](https://www.reddit.com/dev/api/)
- You will need your Client ID, as well as your Secret Key
- Once you have your headers and token 

## Environment
- I am running this project through VS Code using the Jupyter pluggin.
- Python v3.11.9

## Dependencies
- Using [TextBlob](https://textblob.readthedocs.io/en/dev/) to grab the Sentiment 
   - pip install textblob
- Dataclasses from dataclass
   - pip install dataclass
- requests is used to make calls to the api
   - pip install request
   - I did have a weird issue with this in my environment. I has to use import pip._vendor.requests as requests for it to work (Something with VSCode and Jupyter pluggin
- pandas for dataframes
   - pip install pandas
 - I did use some other things like dotenv, and os in order to hide my key and passwords. I recommend you do the same
   - pip install dotenv
   - from dotenv import load_dotenv
   - import os

# How to use the project
Currently the project is set up to take a subreddit by name and a method of searching
- methods of searching include best|hot|new|top|rising

