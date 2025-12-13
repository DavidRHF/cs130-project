# The most popular and least popular aspects of music according to Spotify listeners (2015 - 2025)

## Methodology

#### Data Source

https://www.kaggle.com/datasets/rohiteng/spotify-music-analytics-dataset-20152025

#### Data Preparation

This dataset wasn't very difficult to 

#### Assumptions

One of the major assumptions I had to make was for the popularity scores. On the dataset the popularity scores varied widely, yet many stay within the same 40-60 range. Due to this, my visualizations got a little clunky with the popularity numbers. My first visualization chart reflects this, having the numbers range from 47.25 to 49.00 even when I coded it to be from 0 to 100. It's a little confusing, but I suggest to just view it as if it were from 0 to 100.

The Y-axis for the BPM chart also needs to be viewed in the same light as the popularity visualization. The BPMs are supposed to range from 60 to 200, yet they show as 129.2 to 130.8. In this case, see the range as 60 to 200 for it to make more sense.

The energy dataset was a bit confusing as to what it actually means. There is already a loudness set, a danceability set, and a key set. With these already being there, the energy set seems like it doesn't need to be included. Due to this, I viewed the energy set as a mood set. This way, it brings more meaning to the data set, rather than it just being a throw in.



#### Limitations

The limitation I was faced with was how even the statistics were. For example, the loudness score for songs had very similar number entries for each score. This means that most averages and comparisons are around the same. 
The visualiations therefore looked very even, almost to the point where there was no need for them. I tried choosing data comparisons that actually made sense and looked appealing.  

## Article Section

The recently released spotify wrapped has inspired me to look into datasets surrounding music. For those unaware, spotify wrapped is an end of the year data dump that spotify comes out with every year. It summarizes time listened, favorite artists, favorite songs, and much more. This year I listened to around 230,000 minutes worth of music so I wanted to see other peoples listening habits. Going into this, I was curious about the least popular and the most popular statistics amoung listeners. 

The data set I found includes some very interesting points. It summarizes data from around 85,000 different tracks, with interesting statistics such as popularity scores for songs, song duration, and danceability scores. This data set includes songs and artists from 2015-2025, so the list may not be very popular by todays metrics. Either way, I wanted to find some data comparisons that are interesting.



The first visualization I was curious about was the comparison between popularity and song length. Would songs be less popular or more popular the longer they are? Before looking at the data, I imagined that the 2 to 4 minute range would be the most popular length for music, with the extremes of the data being less popular. It turns out that it varies a lot. The 2 to 3 minute mark holds the highest and the lowest popularity score, making it the best and the worst. Suprisingly, some longer songs are also very popular.


The second visualization features the top 10 most listened to genres on spotify. With so many different types of music, I was curious as to which one was the favorite. My original guess was Pop or Hip-hop but the results were much different than I was expecting. It turns out that the top 3 were Metal, Jazz, and Hip-Hop. The results were very close for the top 10, with most being over 7000 listeners.


The last and coolest visualization features genres being compared to most used BPM (Beats per minute) and the count of the song. This essentially tracks how fast each genres music is. Music typically sits around 60 to 180 BPM. I a\had no expectations going into this visualization, so the results were very interesting. It turns out that EDM and classical music showed the slowest BPM out of all genres. Suprisingly, Pop and Country sat at the highest BPM. 




