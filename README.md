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
|  **16** <br/>**[Island(s)](day16_Island(s).md)**  |   **17** <br/>**[Historical map](day17_Historical%20map.md)**   |  **18** <br/>**[Landuse](day18_Landuse.md)**    |   **19** <br/>**[NULL](day19_NULL.md)**   |   **20** <br/> **[Population](day20_Population.md)**  |   **21** <br/>   |  **22** <br/>    |
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

#### Top favorited post for day 20 `#30DayMapChallenge (Population)`
| media                                               | user                                           |   retweet |   favorite |
|-----------------------------------------------------|------------------------------------------------|-----------|------------|
| ![](http://pbs.twimg.com/media/EnQzzKKW4AE3nKv.jpg) | **[@DiasporaDan](https://t.co/yrRrjJ6U7k)**    |        62 |        313 |
| ![](http://pbs.twimg.com/media/EnRcFWqWMAIpqOg.jpg) | **[@LandEthics](https://t.co/rqhTtJmGDs)**     |        59 |        294 |
| ![](http://pbs.twimg.com/media/EnRuQ-GVQAY40hn.jpg) | **[@Kenneth_KHW](https://t.co/AWwboLGp7M)**    |        20 |        145 |
| ![](http://pbs.twimg.com/media/EnRswBNVEAEqBmu.jpg) | **[@rajbhagatt](https://t.co/exlUo0wIFm)**     |        14 |        101 |
| ![](http://pbs.twimg.com/media/EnP4SPoXEAAP3J4.jpg) | **[@lacxrx](https://t.co/psnswDbCnh)**         |        15 |         87 |
| ![](http://pbs.twimg.com/media/EnSAwb5XEAgOG2u.jpg) | **[@Cchurchili](https://t.co/uUpLrf468n)**     |        15 |         75 |
| ![](http://pbs.twimg.com/media/Em7m0Q0XcAEJky9.png) | **[@JulesGrandin](https://t.co/eAfdn5Hic0)**   |        10 |         70 |
| ![](http://pbs.twimg.com/media/EnQjfXGXYAEcCoM.jpg) | **[@mapsbyp](https://t.co/LN6Oqv8sqI)**        |         3 |         64 |
| ![](http://pbs.twimg.com/media/EnQIytqUcAEqCn9.jpg) | **[@ksituan](https://t.co/9CdnGHfSFH)**        |        11 |         62 |
| ![](http://pbs.twimg.com/media/EnRCk1cW8AAEetH.jpg) | **[@cj_maps](https://t.co/G1v8eivXVe)**        |        17 |         62 |
| ![](http://pbs.twimg.com/media/EnQd-PMW4AIoZkN.jpg) | **[@stevefaeembra](https://t.co/vQhDDZtfqB)**  |        10 |         60 |
| ![](http://pbs.twimg.com/media/EnQJewXW8AIBc7K.png) | **[@neocartocnrs](https://t.co/PDxp1iLuoJ)**   |        16 |         51 |
| ![](http://pbs.twimg.com/media/EnQKQJAXUAE0lIo.jpg) | **[@Junevgt](https://t.co/Zv8XL0EOi5)**        |        11 |         46 |
| ![](http://pbs.twimg.com/media/EnSoL4uXYAQdJGL.jpg) | **[@helenmakesmaps](https://t.co/x2fVA6okzQ)** |         7 |         45 |
 


Inspiration for the repo came from [Kalle Hallden](https://www.youtube.com/channel/UCWr0mx597DnSGLFk1WfvSkQ).