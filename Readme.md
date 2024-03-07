# Instructions
-----

## For training:
Step-1: You need to collect the tweets for tweet ids mentioned in the data file, `CRED_without_tweets.xlsx`, and put them in the corresponding columns (i.e.  'cleaned_tweet_text_x' and 'cleaned_tweet_text_y'). Following Twitter's policy, we couldn't share the individual tweets. However, this process is simple and straight forward (Reference: https://stackoverflow.com/questions/28384588/twitter-api-get-tweets-with-specific-id). You need to clean the tweets (remove URLs) using the [tweet-preprocessor](https://pypi.org/project/tweet-preprocessor/) library. Save the final file as `CRED_with_tweets.xlsx`.<br>
Step-2: Install the packages mentioned in the `requirements.txt` file.<br>
Step-3: Execute the notebook `GGEA_Training_Script.ipynb` following the instructions present in it. This notebook will create the relevant model artefacts.<br>

## For scoring pre-trained GGEA
Step-1: Install the packages mentioned in the `requirements.txt` file.<br>
Step-2: Execute the notebook `Scoring_GGEA.ipynb` following the instructions present in it. This notebook will automatically download the model artefacts. It has been developed & tested using Google Colab.<br>
