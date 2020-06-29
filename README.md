# live-twitter-sentiment-dashboard

The Democratic Party presidential debates just kicked off. With so many candidates (enough for two nights of back-to-back debates), I wanted to build something to gauge widespread political perception in realtime. To do this, I decided applied VADER Sentiment Analysis to a live feed of tweets from the Twitter API. The results were fascinating.

I fed an average of the VADER compound polarity scores of all tweets associated with solely one candidate directly into the scoreboard. The compound score outputs a continuous value ranging from +1 (most positive) to -1 (most negative).

Read the full writeup: https://shomil.me/realtime-debate-scoreboard/
