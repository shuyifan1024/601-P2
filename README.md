# 601-P2 (A)

Individual project number two for EC 601

This project contains three separate files. The first (t.py) is the authorization file. This is where the user will put their personal authorization tokens for the twitter API. This authorization file is imported into both of the other files (get_tweets.py, and searchparty.py0. The get_tweets.py file contains a very basic script that enables a user to input a username and retrieve the last 25 tweets from the specified users' timeline. The number of tweets retrieved can be changed by changing the number parameter in line 14 contained in the .item() specification. The searchparty.py script does considerably more. 

The searchparty script at this time prints out to the console, altough all of this data can relatively easily be downloaded into a csv file if desired. This script prompts the user for a keyword to search for, a date from which to search from, and how many tweets to retrieve. The script will then print out in a nice format the following information about each retrieved tweet: which number tweet it is, the username of the twitter user, the users twitter bio, the location from which the tweet was posted, the number of other people the user follows, the number of followers the user has, how many tweets they have ever written, how many retweets they have ever retweeted, and finally the text of the actual tweet and all the hashtags from the tweet. While this currently searches by keword, using these other pieces of information, further filtering based on location, hashtags, or other criteria could be done in order to further refine the collection of tweets the script outputs. A screenshot of an example output from this script will be posted as proof that it works. All that should be required to make the script work is t.py with the users' personal keys.


See the Task_1B.MD file for homework 1(b)
