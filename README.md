# WeRateDogs Data Wrangling

by Adaobi Onyeakagbu

This project involves wrangling, analyzing and visualizing the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10.

Gathering Data ¶
- The WeRateDogs Twitter archive file (twitter_archive_enhanced.csv) was provided by the account handler to Udacity
- Tweet image predictions file (image_predictions.tsv) which was hosted on Udacity servers
- JSON data file which was gotten by querying the Twitter API for each tweet's JSON data using Python's Tweepy library and storing them in the tweet_json.txt file.

Assessing and Cleaning Data
The data was visually and programmatically assessed for further information and to see if there were any cleanliness and tidiness issues. 10 cleanliness issues and 2 tidiness issues were observed and corrected.
Cleaned data is stored as a csv file twitter_archive_master.csv as well as a database file bestofrt.db

This repository contains the ipnyb file for the full wrangling efforts as well as an insight report act_report.pdf



