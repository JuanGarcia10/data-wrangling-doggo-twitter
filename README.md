# IMPORTANT NOTICE
this is the final project of the Data Wrangling module from the Udacity nanodegree "Data Analyst". This project will be reviewed by Udacity instructors but it is not intended to be further developed. The goal is to apply the newly learned methods for data wrangling in a structured manner: gathering, assessing, and cleaning.

## Introduction
Real-world data rarely comes clean. Using Python and its libraries, we will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it (data wrangling). All wrangling efforts will be documented in a Jupyter Notebook and a showcase through the analyses and visualizations using Python (and its libraries) and/or SQL.

The dataset that we will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for the use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.

## The Dataset
**The dataset will not be provided in this repository as it is property of twitter**. However, if you are interested on it, you can apply for a development account from Twitter and access it through the pandas library *Tweepy*

## Key Aspects of the Project
* We only want original ratings (no retweets) that have images. Though there are 5000+ tweets in the dataset, not all are dog ratings and some are retweets.
* Assessing and cleaning the entire dataset completely would require a lot of time, and is not necessary. Therefore, the requirements of this project are only to assess and clean at least 8 quality issues and at least 2 tidiness issues in this dataset.
* Cleaning includes merging individual pieces of data according to the rules of tidy data.
* The fact that the rating numerators are greater than the denominators does not need to be cleaned. This unique rating system is a big part of the popularity of WeRateDogs.
* We do not need to gather the tweets beyond August 1st, 2017. 
