# Introduction
The dataset is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 9 million followers and has received international media coverage.

# Summary
Three approach steps were used in this project, which is _Gather_, _Assess_, and _Clean_.
**Gather**; The wrangling process consists of gathering three datasets from different sources
- The first dataset which was provided like a file at hand was in csv format named twitter_archive_enhanced.csv.
- The second dataset is hosted on Udacity servers. Using the Url link provided by Udacity, I use the Requests library to make a request from the server and write the response texts to a file name image_predictions.tsv.
-The third file was extracting the `retweet count` and `favorite count` from Twitter API by the use of **Tweepy** which is an open-source Python package that gives you a very convenient way to access the Twitter API with Python.

**Assess**: Visual and Programmatic assessment approach technique which is effective in spotting qualities and tidiness issues.

**Clean**: Before the data cleaning process, a copy of the original gathered dataset was made. This allows you the opportunity to compare your changes to the original data frame to check your work as you clean the data.

After all the qualities and tidiness issues were fixed, the dataset was saved as **twitter-archive-master.csv**. This cleaned data set can then be used for analysis or exploratory data analysis work without returning to the code to clean the data.