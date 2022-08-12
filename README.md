# WeRateDogs Twitter Archive
## by Nwangene Sobe-Olisa
### a Udacity-ALX Data Wrangling Project

## Dataset
This project consists of 3 datasets:
**1. Enhanced Twitter Archive (twitter-archive-enhanced.csv):** This was gottend from the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates) also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because ["they're good dogs Brent."](The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent.")

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which Udacity used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, Udacity have filtered for tweets with ratings only (there are 2356).

**2. Additional Data via Twitter API:** 
This was gotten by querrying Twitter's API. Twitter API requires authorization, so you need to set up your own Twitter application using the folloing steps:

* [sign up for a Twitter account](https://help.twitter.com/en/using-twitter/create-twitter-account) if you don't have one already.
* Set up a developer account, following the directions on [Twitter's Developer Portal, in the "How to Apply" section](https://developer.twitter.com/en/docs/developer-portal/overview).
* Once you submit your application, you should soon receive an email from Twitter letting you know they have approved your new Twitter developer account. Follow the link in the email from Twitter to a page of directions to get started creating your app.
* If you are asked for an app name, it can be anything appropriate, and if you’re asked for a Website URL, it can be anything in a standard URL format. You can do the same with other requested URLs, or perhaps leave them blank.
* You should then be given a Success message, and a new developer page displayed to you where you can manage your app.
* You can then go to the Keys and Tokens tab on this page to find or generate the Consumer API keys, and the Access Token and Access Token Secret that you will need.

This twitter API files is stored as tweet_json.txt. In case you dont get Twitter permission or don't want to have an account with them.

**3. The Tweet image predictions (image_predictions.tsv):**
This file is present in each tweet according to a neural network. It is hosted on Udacity's servers and was downloaded programmatically using the [Requests](https://pypi.org/project/requests/) library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

## Environment 
This project was written in python using Anaconda's jupyter notebook. The following following packages needs to be installed in other to effectively run:
* pandas
* Numpy
* requests
* tweepy
* json 
* os
* datetime
* matplotlib.pyplot
* seaborn
* sklearn

## Context
The projects goal is wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations.

## Project Summary
See the wrangle report and act report for project summary