Abstract: 
The goal of this project was to identify any specific topics being discussed on Twitter about Bitcoin. This project could be useful for someone trying to analyze if current events and peoples current sentiments on Bitcoin have an impact on the price of Bitcoin.

Data + Design:
The data is a Kaggle dataset. It contained over a million tweets that was filtered down to ~8000 by showing tweets only by users with over 128,000 followers and tweets related to Bitcoin from June, July and August 2021. Some key features are tweet date, user name, tweet text, and hashtags utilized. No feature engineering other than Topic Modeling was created for this project.

Tools:
Pandas and Numpy for data manipulation and EDA.
SkLearn and NLTK for Topic Modeling.
Matplotlib for Plotting.

Algorithm: 
I started by preprocessing the data and removing any special characters, punctuation, emojis, numbers among other things. Then I grouped all the tweets by day and had 37 lists of tweets. I compared the documents and terms via TF-IDF as it places a higher importance/frequency on rare words. I topic modeled with NMF as it interpretable and best for short documents like tweets. Then I analyzed my results with document-term matrices and word-topic lists.
