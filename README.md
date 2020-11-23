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
|   **23** <br/>   |   **24** <br/>   |   **25** <br/>   |   **26** <br/>   |   **27** <br/>   |   **28** <br/>   |  **29** <br/>    |
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

#### Top favorited post for day 22 `#30DayMapChallenge (Movement)`
| media                                                                                        | user                                                                             |   retweet |   favorite |
|----------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------|------------|
| ![](http://pbs.twimg.com/ext_tw_video_thumb/1330414077445812228/pu/img/LaiGhdSp7MTbdhMJ.jpg) | **[@JonasNelson19](https://twitter.com/twitter/statuses/1330414822131982342)**   |        42 |        245 |
| ![](http://pbs.twimg.com/media/Em7lGtqWMAYsITk.jpg)                                          | **[@JulesGrandin](https://twitter.com/twitter/statuses/1330430316083875842)**    |        51 |        221 |
| ![](http://pbs.twimg.com/media/Enb7JffW4AY_ffI.jpg)                                          | **[@rajbhagatt](https://twitter.com/twitter/statuses/1330528537795719168)**      |        38 |        219 |
| ![](http://pbs.twimg.com/tweet_video_thumb/Encdo_xXEAM3gXv.jpg)                              | **[@JoeWDavies](https://twitter.com/twitter/statuses/1330566326071549955)**      |        18 |        107 |
| ![](http://pbs.twimg.com/tweet_video_thumb/EnaqXnfWMAA-WXW.jpg)                              | **[@dr_xeo](https://twitter.com/twitter/statuses/1330439584463921152)**          |        23 |        107 |
| ![](http://pbs.twimg.com/media/EnaaKJ_W4AMVkc-.png)                                          | **[@neocartocnrs](https://twitter.com/twitter/statuses/1330420307497193473)**    |        13 |         77 |
| ![](http://pbs.twimg.com/ext_tw_video_thumb/1330596441929248768/pu/img/BQ-CCWhq0gbf8jsl.jpg) | **[@sdbernard](https://twitter.com/twitter/statuses/1330596642731552773)**       |         6 |         71 |
| ![](http://pbs.twimg.com/tweet_video_thumb/EncygqWXEAAEug5.jpg)                              | **[@Artisans_Cartos](https://twitter.com/twitter/statuses/1330587801100972042)** |        12 |         65 |
| ![](http://pbs.twimg.com/media/Ena2_6PXcAMbt6L.jpg)                                          | **[@Koen_VdE](https://twitter.com/twitter/statuses/1330452195788132357)**        |         3 |         58 |
| ![](http://pbs.twimg.com/tweet_video_thumb/EnbVSNSXYAENDTr.jpg)                              | **[@geodatascience](https://twitter.com/twitter/statuses/1330485364377722880)**  |        10 |         53 |
| ![](http://pbs.twimg.com/ext_tw_video_thumb/1330420099816316930/pu/img/vKppWckQi7BtvyOx.jpg) | **[@owenjpowell](https://twitter.com/twitter/statuses/1330420188035080192)**     |         4 |         52 |
| ![](http://pbs.twimg.com/ext_tw_video_thumb/1330585172182523909/pu/img/JxK6aVktTL25r29O.jpg) | **[@stevefaeembra](https://twitter.com/twitter/statuses/1330585361165193218)**   |         8 |         51 |
 




Inspiration for the repo came from [Kalle Hallden](https://www.youtube.com/channel/UCWr0mx597DnSGLFk1WfvSkQ).