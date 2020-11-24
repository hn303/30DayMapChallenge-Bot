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
|   **23** <br/>**[Boundaries](day23_Boundaries.md)**   |   **24** <br/>   |   **25** <br/>   |   **26** <br/>   |   **27** <br/>   |   **28** <br/>   |  **29** <br/>    |
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

#### Top favorited post for day 23 `#30DayMapChallenge (Boundaries)`
| media                                                                                        | user                                                                            |   retweet |   favorite |
|----------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|-----------|------------|
| ![](http://pbs.twimg.com/media/EnhmoCPXYAA-XIb.jpg)                                          | **[@helenmakesmaps](https://twitter.com/twitter/statuses/1330926890375393289)** |        32 |        196 |
| ![](http://pbs.twimg.com/tweet_video_thumb/EngXQ9XW4AAvMOX.jpg)                              | **[@geodatascience](https://twitter.com/twitter/statuses/1330839850463924225)** |        32 |        154 |
| ![](http://pbs.twimg.com/media/Eng4iuhVoAEKNAM.jpg)                                          | **[@rajbhagatt](https://twitter.com/twitter/statuses/1330876003002900483)**     |        23 |        128 |
| ![](http://pbs.twimg.com/media/EnhNfguW4AEsdIn.jpg)                                          | **[@tkardi](https://twitter.com/twitter/statuses/1330902173442519041)**         |        18 |         83 |
| ![](http://pbs.twimg.com/media/Enim0NYXMAQpuVl.jpg)                                          | **[@cstats1](https://twitter.com/twitter/statuses/1330997182116327425)**        |        15 |         74 |
| ![](http://pbs.twimg.com/ext_tw_video_thumb/1330797827275034624/pu/img/PSM_blhtkMdzafXo.jpg) | **[@owenjpowell](https://twitter.com/twitter/statuses/1330797904236326912)**    |         2 |         60 |
| ![](http://pbs.twimg.com/media/Eni0AWsXUAEttyJ.jpg)                                          | **[@pokateo_](https://twitter.com/twitter/statuses/1331012288371978241)**       |         5 |         48 |
| ![](http://pbs.twimg.com/tweet_video_thumb/Eng95CIXYAA7khR.jpg)                              | **[@undertheraedar](https://twitter.com/twitter/statuses/1330882300599541762)** |         5 |         47 |
| ![](http://pbs.twimg.com/media/EnebGLHXIAALF4j.jpg)                                          | **[@pokateo_](https://twitter.com/twitter/statuses/1330704333747445773)**       |         2 |         43 |
| ![](http://pbs.twimg.com/media/Enho9QpXcAkFzYu.jpg)                                          | **[@dr_xeo](https://twitter.com/twitter/statuses/1330929543746625540)**         |         8 |         36 |
 




Inspiration for the repo came from [Kalle Hallden](https://www.youtube.com/channel/UCWr0mx597DnSGLFk1WfvSkQ).