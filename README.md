# Twitter-Data-Collection
This code is to help collect data from Twitter API using Python programming language

![image](https://dsim.in/blog/wp-content/uploads/2016/10/twitter-1.png)

- In order to run this code, it has been assumed that you have one or multiple Twitter developer accounts from which you have the required tokens to connect to the Twitter API

- The main target of this code is to collect data using one or multiple accounts while synchronizing between these accounts and waiting when the rate limit is exceeded for all the available accounts without getting rate errors

- This code supports tweets collection where the pagination has been considered and the code  automatically moves to a new page.

- Also, this code supports other data entities collection that do not require pagination like getting trends or users profiles information

- There are three main files:
1. twitter_tokens.json: where you have to add the list of available tokens
2. twitter_api_preparation.ipynb: where the connection to the APIs is set up. Also, there is a function to show the current status of the   
   required Twitter API for some of chosen end-points
3. twitter_data_collection.ipynb: where the data collector classes are defined with some examples about how to run the code

- Also there is a requirements.txt file including the main modules that you have to install before you run the code
