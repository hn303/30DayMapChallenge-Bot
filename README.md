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
| **9** <br/>**[Monochrome](day09_Monochrome.md)** | **10** <br/>**[Grid](day10_Grid.md)**  | **11** <br/>**[3D](day11_3D.md)**  | **12** <br/>**[No GIS](day12_Map%20not%20made%20with%20GIS%20software.md)**  | **13** <br/>**[Raster](day13_Raster.md)**  | **14** <br/>**[Climate change](day14_Climate%20chang.md)**  |  **15** <br/>**[Connections](day15_Connections.md)**  |
|  **16** <br/>**[Island(s)](day16_Island(s).md)**  |   **17** <br/>**[Historical map](day17_Historical map.md)**   |  **18** <br/>    |   **19** <br/>   |   **20** <br/>   |   **21** <br/>   |  **22** <br/>    |
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

#### Top favorited post for day 17 `#30DayMapChallenge (Historical map)`
| media                                                                                        | user                                           |   retweet |   favorite |
|----------------------------------------------------------------------------------------------|------------------------------------------------|-----------|------------|
| ![](http://pbs.twimg.com/media/EnAfFQbXMAMCqUQ.jpg)                                          | **[@neocartocnrs](https://t.co/FvAIySYuJV)**   |        52 |        208 |
| ![](http://pbs.twimg.com/media/EnAT2alW8AExQhA.jpg)                                          | **[@evelynuuemaa](https://t.co/I4CJnpcS3H)**   |        12 |        151 |
| ![](http://pbs.twimg.com/media/EnCK1q1VkAELKR6.jpg)                                          | **[@rajbhagatt](https://t.co/eoIm29errg)**     |        24 |        136 |
| ![](http://pbs.twimg.com/media/EnBRSc4XUAEalPa.jpg)                                          | **[@Tabularthur](https://t.co/1L6rfHrP7G)**    |        23 |        114 |
| ![](http://pbs.twimg.com/media/EnA7LyBWEAES6fh.jpg)                                          | **[@Junevgt](https://t.co/TnQZOeB9D7)**        |        22 |         98 |
| ![](http://pbs.twimg.com/media/EnAfnWEW4AIM3GC.jpg)                                          | **[@geomigr](https://t.co/qki76sRHEW)**        |        32 |         92 |
| ![](http://pbs.twimg.com/media/EnCddnLXYAE16_1.jpg)                                          | **[@undertheraedar](https://t.co/IhBZpQ6rqA)** |        11 |         75 |
| ![](http://pbs.twimg.com/media/Em_rtITW8AAPSJR.jpg)                                          | **[@pokateo_](https://t.co/bhkCPFn0a7)**       |         8 |         69 |
| ![](http://pbs.twimg.com/tweet_video_thumb/EnDAVajVEAAU04a.jpg)                              | **[@helenmakesmaps](https://t.co/eJP9YfJt9U)** |         6 |         58 |
| ![](http://pbs.twimg.com/media/EnDqKEYXYAE2u6h.jpg)                                          | **[@gontsa](https://t.co/WlBlI8ZpMC)**         |        13 |         53 |
| ![](http://pbs.twimg.com/media/EnB8sUlVcAAtAp9.jpg)                                          | **[@jstnbraaten](https://t.co/r599fP7PY5)**    |        12 |         46 |
| ![](http://pbs.twimg.com/ext_tw_video_thumb/1328594976800985094/pu/img/99MysrKGgOeAIVgF.jpg) | **[@vaylafi](https://t.co/2RMVwE1Hpw)**        |         7 |         44 |
| ![](http://pbs.twimg.com/media/EnBhyTuXcAIcJiI.jpg)                                          | **[@VictimOfMaths](https://t.co/lh7AxqtPfa)**  |         8 |         44 |
 


Inspiration for the repo came from [Kalle Hallden](https://www.youtube.com/channel/UCWr0mx597DnSGLFk1WfvSkQ).