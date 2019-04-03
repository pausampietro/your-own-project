
![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Welcome to 'The Journalist'!

## Repository content:

1. Get&Export_RSS -> Gets the news of each RSS source separately and exports the content to a GoogleCloud Database
2. Get&Export_Tweets -> Gets the 20 last tweets of each media and exports the content to a GoogleCloud Database
3. Analysis_Twitter -> Imports all the stored tweets and performs analysis of polarity, subjectivity, number of likes, etc
4. Analysis_RSS_vs_Twitter -> Gets matches between same news in RSS & Twitter and compare differences in terms of polarity, subjectivity...
5. Analysis_Words -> Gets a dictionary with all the words used in news tweets and extract the best/worst words based on likes/retweets received

________________________________________________________________________________________________________________________________


## Project Goals
* Compare Twitter versus Traditional News Media
* Try to get insights about "how a New should be written" to get more audience/impact.

## Sources
* Twitter API
* RSS of most relevant Traditional News Media 

## Resources
* Sentiment Analysis with python TextBlob / Vader
* Jupyter notebook
* Database

## Some questions to answer...
* How news on both media are written? (positive/negative/neutral language used)
* How related are news on twitter (most popular info tweets) with news on TM? 


## Analysis process
* Obtain data from sources
* Clean data if needed / translate tweets
* Store data in a DB (Twitter free API just let you obtain the 20 last tweets from each user)
* Analize data in terms of: sentiment, polarity, subjectivity, lenght, audience.
* Compare audience with popularity
* Try to establish some relations, regressions between variables, etc.
* Plot results

## Conventions
* snake_case
* clean code / version control with gitKraken
* libraries if needed





 
