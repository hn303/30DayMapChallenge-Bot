## 30DayMapChallenge-Bot
Monitoring [#30DayMapChallenge 2020](https://github.com/tjukanovt/30DayMapChallenge) launched by [Topi Tjukanov](https://twitter.com/tjukanov) on Twitter. Trying to engage this wonderful event in a special way. 

![images](./graphs/map_challenge_2020_bot.jpg)

### Twitter Data
#30DayMapChallenge related tweets are collected via Twitter REST API with the hashtag `#30DayMapChallenge`. The example of raw .json data returned via Twitter REST API can be found in `.\example` folder. This repo only select serveral attributes from tweet metadata including: `tweet_id`, `tweet_text`, `language`, `tweet_created_at`, `retweet`, `favorite`, `hashtags`, `user_id`, `user_name`, `user`, `user_loc`, `user_follower`, `friends_count`, `media` and save as .csv file in `.\data` folder.

Note:
-  `#30DayMapChallenge` with image attached
- search tweets by date since everyday has diffferent map theme
- cleanning process for late entry tweets is only conducted in first two days
- some tweets in certain time zones (such as Pacific Time) might be searched and archived in file next day

### Daily Tweets Statistics
(Bar plot of daily tweets count for `#30DayMapChallenge 2020` now has been updated. Previous version wrongly count duplicate files in data folder.)

![images](./graphs/maps_count.png)

### Top Favourited/:heart: Maps

As [Topi Tjukanov](https://twitter.com/tjukanov) mentioned in [30DayMapChallenge](https://github.com/tjukanovt/30DayMapChallenge) page, this map challenge is NOT a competation. Although this repo sorts maps by their favorite count and retweet count, this repo never intend to compare all the wonderful maps but create a altas of inspiring maps for a reference. I am also interested in exploring topis in replies in those maps with more attention (if i have time).

Top favorited tweets refers to the tweets get many `liked`/:heart:. The faviorite count is extracted from `favorite_count` value in tweet metadata.

| |||December 2020||| |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Mon** | **Tue** | **Wed** | **Thu** | **Fri** | **Sat** | **Sun** |
|     |     |     |     |     |     | **1** <br/>**[Points](day1.md)**|
| **2** <br/>**[Lines](day2.md)**   |**3** <br/>**[Polygons](day3.md)**   |**4** <br/>**[Hexagons](day4.md)**    | **5** <br/>**[Blue](day05_Blue.md)**   | **6** <br/>**[Red](day06_Red.md)**   | **7** <br/>**[Green](day07_Green.md)**  | **8** <br/>**[Yellow](day08_Yellow.md)**  |
| **9** <br/>**[Monochrome](day09_Monochrome.md)** | **10** <br/>**[Grid](day10_Grid.md)**  | **11** <br/>**[3D](day11_3D.md)**  | **12** <br/>**[No GIS](day12_Map%20not%20made%20with%20GIS%20software.md)**  | **13** <br/>**[Raster](day13_Raster.md)**  | **14** <br/>**[Climate change](day14_Climate%20change.md)**  |  **15** <br/>**[Connections](day15_Connections.md)**  |
|  **16** <br/>**[Island(s)](day16_Island(s).md)**  |   **17** <br/>**[Historical map](day17_Historical%20map.md)**   |  **18** <br/>**[Landuse](day18_Landuse.md)**    |   **19** <br/>**[NULL](day19_NULL.md)**   |   **20** <br/> **[Population](day20_Population.md)**  |   **21** <br/> **[Water](day21_Water.md)**  |  **22** <br/>**[Movement](day22_Movement.md)**    |
|   **23** <br/>**[Boundaries](day23_Boundaries.md)**   |   **24** <br/>**[Elevation](day24_Elevation.md)**   |   **25** <br/>**[COVID-19](day25_COVID-19.md)**   |   **26** <br/>**[Map with a new tool](day26_Map%20with%20a%20new%20tool.md)**   |   **27** <br/>**[Big or small data](day27_Big%20or%20small%20data.md)**   |   **28** <br/>   |  **29** <br/>    |
|  **30** <br/>    |     |     |     |     |     |     |

<!-- - **[Maps for Day 1 `#30DayMapChallenge (Points)`](day1.md)** (include late entry)

- **[Maps for Day 2 `#30DayMapChallenge (Lines)`](day2.md)** (exclude late entry)

- **[Maps for Day 3 `#30DayMapChallenge (Polygons)`](day3.md)**

- **[Maps for Day 4 `#30DayMapChallenge (Hexagons)`](day4.md)**

- **[Maps for Day 5 `#30DayMapChallenge (Blue)`](day05_Blue.md)**

- **[Maps for Day 6 `#30DayMapChallenge (Red)`](day06_Red.md)**

- **[Maps for Day 7 `#30DayMapChallenge (Green)`](day07_Green.md)**

- **[Maps for Day 8 `#30DayMapChallenge (Yellow)`](day08_Yellow.md)**

- **[Maps for Day 9 `#30DayMapChallenge (Monochrome)`](day09_Monochrome.md)**

- **[Maps for Day 10 `#30DayMapChallenge (Grid)`](day10_Grid.md)**

- **[Maps for Day 11 `#30DayMapChallenge (3D)`](day11_3D.md)**

- **[Maps for Day 12 `#30DayMapChallenge (Map not made with GIS software)`](day12_Map%20not%20made%20with%20GIS%20software.md)**

- **[Maps for Day 13 `#30DayMapChallenge (Raster)`](day13_Raster.md)**

- **[Maps for Day 14 `#30DayMapChallenge (Climate change)`](day14_Climate%20change.md)**

- **[Maps for Day 15 `#30DayMapChallenge (Connections)`](day15_Connections.md)**
 -->

#### Top favorited post for day 27 `#30DayMapChallenge (Big or small data)`
| media                                                                                        | user                                                                            |   retweet |   favorite |
|----------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|-----------|------------|
| ![](http://pbs.twimg.com/ext_tw_video_thumb/1332254853062647809/pu/img/QZr-OMqyha4HIa3p.jpg) | **[@owenjpowell](https://twitter.com/twitter/statuses/1332254965197369344)**    |        26 |        163 |
| ![](http://pbs.twimg.com/media/En2IVDqUwAAKKqx.jpg)                                          | **[@rajbhagatt](https://twitter.com/twitter/statuses/1332371852333760512)**     |        23 |        113 |
| ![](http://pbs.twimg.com/media/En04Yz6WMAEq3oK.png)                                          | **[@afrimapr](https://twitter.com/twitter/statuses/1332284210430750721)**       |        31 |        100 |
| ![](http://pbs.twimg.com/media/En0CtKzXEAIGmIS.jpg)                                          | **[@evelynuuemaa](https://twitter.com/twitter/statuses/1332224459223298048)**   |        11 |         92 |
| ![](http://pbs.twimg.com/media/En0kkRNVgAI6WGK.jpg)                                          | **[@SouthArrowMaps](https://twitter.com/twitter/statuses/1332261283530371072)** |         8 |         85 |
| ![](http://pbs.twimg.com/media/En1wilfW4AIzMef.jpg)                                          | **[@MapsByAntonia](https://twitter.com/twitter/statuses/1332344807998500864)**  |        11 |         60 |
| ![](http://pbs.twimg.com/media/En1gQCMXIAUUaw9.jpg)                                          | **[@tjukanov](https://twitter.com/twitter/statuses/1332327637470113794)**       |         5 |         47 |
| ![](http://pbs.twimg.com/media/En3Yv6UW4AEzxVF.jpg)                                          | **[@hurricanevicky](https://twitter.com/twitter/statuses/1332459394341228545)** |         3 |         44 |
| ![](http://pbs.twimg.com/media/En3XjLWWMAI6ddK.png)                                          | **[@gontsa](https://twitter.com/twitter/statuses/1332459258496102406)**         |         8 |         39 |
| ![](http://pbs.twimg.com/media/Enz8Sy-XMAAJY6D.jpg)                                          | **[@lacxrx](https://twitter.com/twitter/statuses/1332217342990946304)**         |         8 |         35 |
| ![](http://pbs.twimg.com/media/En2lp2-XYAMn0dv.jpg)                                          | **[@helenmakesmaps](https://twitter.com/twitter/statuses/1332404051590459393)** |         3 |         34 |
| ![](http://pbs.twimg.com/media/EnxmDrpW4AMXKdF.jpg)                                          | **[@robradburn](https://twitter.com/twitter/statuses/1332218348264849408)**     |         2 |         28 |
 



Inspiration for the repo came from [Kalle Hallden](https://www.youtube.com/channel/UCWr0mx597DnSGLFk1WfvSkQ).