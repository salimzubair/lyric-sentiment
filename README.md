# Sentiment Ananlysis of Billboard Hot 100 Songs over Time (1958-2019)

For this project, I scraped all song lyrics for all entries of the Billboard Hot 100 from 1958 to 2019 from the website [genius.com](https://genius.com/) using LyricsGenius, a python API client developed by [John W Miller](https://github.com/johnwmillr/LyricsGenius). After scraping all the song lyrics, I performed sentiment analysis of songs using TextBlob, a Python text processing library.

## Results

1. On average, the sentiment of lyrics on the BillbOard Hot 100 tend to be neutral.

2. Lyric Setiment in 2019 is about 4 times as negative as lyric sentiment in the 1960s.

![Lyric Sentiment over Time Plot](https://github.com/salimzubair/lyric-sentiment/blob/master/plot.png)

3. Lyric sentiment, on average, has gotten 1.2% more negative annually between 1958 and 2019.

4. Top keywords for lyrics in 1958 include:
    1. "like"
    2. "come"
    3. "littleness"
    4. "jump like"
    5. "good"
    
5. Top Keywords for lyrics in 2019 include:
    1. "like"
    2. "yeah"
    3. "niggas"
    4. "bitches"
    5. "lil bitch"
    6. "love"
    7. "need"
    8. "fuck"

## Data

The datasets containing the analysis results and scraped lyrics could not be uploaded to github due to size limits. It can be viewed and downloaded here: https://data.world/szubair/lyric-sentiment-ananlysis




