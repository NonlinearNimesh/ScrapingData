# Scrap Data
In this repository i have list down python file to scrap data from twitter and Reddit (For now) which will help in Creating the dataset for various deep learning and machine learning model.

# FetchTweets
This file will fetch the tweets or the media/memes associated with it.
TO get Started you need a twitter developer account ```https://developer.twitter.com/en/apply-for-access``` which will provide the needed API credentials i.e. consumer_key, consumer_secret, access_token, access_token_secret.

Other than those API credentials it also required tweepy, it can be easily installed using ```pip install tweepy```


# ScrapRedditMemes
This file will scrap the memes associated with a Give Subreddits and the number of pages of that provided subreddit. <br/>
Scrapping data from reddit is on the go i.e. any API credentials is not required. <br/>

Later in this i have used pyteseract to fetch the text present on the memes (not consistent but will do the job) which can help in creating a multimodal dataset. <br/>

