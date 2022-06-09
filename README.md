# Profanity analysis of Twitter tweets using Python

A. Short Description:
Given a file of tweets and a list of abuses/racial slurs, identify the degree of profanity of Twitter tweets.

B. Long Description:
Suppose two files are provided such that one file contains Twitter tweets by various users and the other consists of a list of "profanity words" (abuses and/or racial slurs). The file containg tweets will be called as the "tweet file". It can have any one of the extensions - "txt/text/xls/xlsx/xlsm" and a following format: A single column containing the tweets preceeded by the users' Twitter handle. Can be with/without a header. The other file, called "search_words" file, contains a list of abusive words and/or racial slurs such that each "profinity word" is on a new line. This file must be a text file with extensions "txt/text".  

C. Inputs Description:
A file containing Twitter handles and their tweets such that each line contains one Twitter handle and tweets. Check any of the example files called "tweets" with extensions "txt/text/csv/xls/xlsx" for the correct format. A "txt/text" file with one "profanity word" per line. Check the file called "search_words.txt" or "search_words.text" for the correct format.

D. Output Description:
A CSV file with 4 columns: User handles, original tweets, "profinity words", and degree of profanity - Check "tweets_analysis.csv".
