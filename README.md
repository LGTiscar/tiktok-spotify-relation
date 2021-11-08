# TikTok - Spotify top songs relationship analysis

Since TikTok trending videos get millions of visualizations and they often use songs for dancing trends, background music, etc, I wonder if there could be a relationship between
the songs used in the top50 trending videos of tiktok and the top50 viral and top200 global songs of Spotify.

I encountered some problems when approaching this analysis:

1. Today's most usefull way to scrap TikTok is this github tool, many thanks to @drawrofly (https://github.com/drawrowfly/tiktok-scraper). Even thought it is quite useful, it is not an 
official TikTok API, so the data could be biased by my tiktok account preferences and recommendations.

2. I could only get day to day tiktok data, so the top50 trending tiktoks have only 1 day data.

3. Even thought Spotify has an official API, I couldnt find an official source for the trending data playlists. I had to use Spotifycharts (https://spotifycharts.com/regional) to get that day
top50 viral and top200 global songs

---

These are the results:

**top50 viral Spotify:**

<img src="https://github.com/LGTiscar/tiktok-spotify-relation/blob/master/Results/top50.png" alt="Image1"/> 

Because of the 3 problems with mentioned before and the quickly changing behaviour of top50 viral songs, it is not a good measure to clarify if there is a relationship between Spotify and TikTok trends. The next result, on the other hand seems more clarifying:


**top200 global Spotify:**

<img src="https://github.com/LGTiscar/tiktok-spotify-relation/blob/master/Results/top200.png" alt="Image1"/>

Many of the most trending songs in tiktok appear in spotify top200 global songs trend. Due to the customization of my tiktok feed, I cannot assure that there is a relationship based on these evidences, but it seems very probably. If any TikTok trend analysis tool would be developed in the future, without having to rely on tiktok API user-focused tools, further investigation should be carried on to prove this relationship.
