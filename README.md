# econTwitterAnalysis
Ascertaining whether tweeting is worthwhile as a way to boost citation metrics for economists

# Overview
This project started because I had several people tell me that having a presence on twitter was important for marketing myself and my research. I decided I needed to be convinced of this fact with some empirical evidence before investing my limited time and brain power coming up with witty tweets. This notebook queries the twitter API to find a sample of academics who tweet about economics and then scrapes (using selenium) citation metrics from google scholar for those same academics (final sample size of 764). The empirical relationship between twitter metrics and citation metrics is examined. OLS results suggest academics who tweet at a higher frequency (tweets_per_day) have fewer citations per year on average (1 extra tweet per day on average is associated with 1.85 fewer citations per year) after controlling for follower, friends, number of coauthors, number of publications, number of top publications, and years of research experience. My take on this is that if you are stopping to tweet many times throughout the day, then your attention is constantly fragmented which limits your ability to perform the deep focus required for quality publications that go on to get cited heavily. 

Based on these results, I don't think I'll start tweeting.
