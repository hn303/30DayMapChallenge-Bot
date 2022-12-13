# 30DayMapChallenge-Bot

Monitoring [#30DayMapChallenge 2022](https://30daymapchallenge.com) launched by [Topi Tjukanov](https://twitter.com/tjukanov) on Twitter. Trying to engage this wonderful event in a special way.

![images](./static/logo-2022.jpg)
(image adapted from Topi Tjukanov's)

## Twitter Data

#30DayMapChallenge related tweets are collected via Twitter REST API with the hashtag `#30DayMapChallenge`. The example of raw .json data returned via Twitter REST API can be found in `.\example` folder. This repo only select serveral attributes from tweet metadata including: `tweet_id`, `tweet_text`, `language`, `tweet_created_at`, `retweet`, `favorite`, `hashtags`, `user_id`, `user_name`, `user`, `user_loc`, `user_follower`, `friends_count`, `media` and save as .csv file in `.\data` folder.

Note:

- `#30DayMapChallenge` with image attached
- search tweets by date since everyday has diffferent map theme
- cleanning process for late entry tweets is only conducted in first two days
- some tweets in certain time zones (such as Pacific Time) might be searched and archived in file next day

## Daily Tweets Statistics

![images](./static/maps_daily.png)

## Top Favourited/:heart: Maps (to do)

As [Topi Tjukanov](https://twitter.com/tjukanov) mentioned in [30DayMapChallenge](https://github.com/tjukanovt/30DayMapChallenge) page, this map challenge is NOT a competition. Although this repo sorts maps by their favorite count and retweet count, this repo never intend to compare all the wonderful maps but create a altas of inspiring maps.

Top favorited tweets refers to the tweets get many `liked`/:heart:. The faviorite count is extracted from `favorite_count` value in tweet metadata.

<!-- |                                                                                                                 |                                                                                                             |                                                                   |                            December 2021                            |                                                                                       |                                                                                        |                                                                                       |
| :-------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------: | :-----------------------------------------------------------------: | :-----------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------: |
|                                                     **Mon**                                                     |                                                   **Tue**                                                   |                              **Wed**                              |                               **Thu**                               |                                        **Fri**                                        |                                        **Sat**                                         |                                        **Sun**                                        |
|                                 **1** <br/>**[Points](daily/day01_Points.md)**                                  |                                **2** <br/>**[Lines](daily/day02_Lines.md)**                                 |        **3** <br/>**[Polygons](daily/day03_Polygons.md)**         |         **4** <br/>**[Hexagons](daily/day04_Hexagons.md)**          | **5** <br/>**[Data challenge 1: OpenStreetMap](daily/day05_Data%20challenge%201.md)** |                        **6** <br/>**[Red](daily/day06_Red.md)**                        |                     **7** <br/>**[Green](daily/day07_Green.md)**                      |
|                                   **8** <br/>**[Blue](daily/day08_Blue.md)**                                    |                           **9** <br/>**[Monochrome](daily/day09_Monochrome.md)**                            |          **10** <br/>**[Raster](daily/day10_Raster.md)**          |               **11** <br/>**[3D](daily/day11_3D.md)**               |                **12** <br/>**[Population](daily/day12_Population.md)**                | **13** <br/>**[Data challenge 2: Natural Earth](daily/day13_Data%20challenge%202.md)** |   **14** <br/>**[Map with a new tool](daily/day14_Map%20with%20a%20new%20tool.md)**   |
| **15** <br/>**[Map made without using a computer](daily/day15_Map%20made%20without%20using%20a%20computer.md)** |                          **16** <br/>**[Urban/rural](daily/day16_Urban&rural.md)**                          |            **17** <br/>**[Land](daily/day17_Land.md)**            |            **18** <br/>**[Water](daily/day18_Water.md)**            |                **19** <br/>**[Island(s)](<daily/day19_Island(s).md>)**                |                  **20** <br/> **[Movement](daily/day20_Movement.md)**                  |                **21** <br/> **[Elevation](daily/day21_Elevation.md)**                 |
|                             **22** <br/>**[Boundaries](daily/day22_Boundaries.md)**                             | **23** <br/>**[Data challenge 3: GHSL Global Human Settlement Layer](daily/day23_Data%20challenge%203.md)** | **24** <br/>**[Historical map](daily/day24_Historical%20map.md)** | **25** <br/>**[Interactive map](daily/day25_Interactive%20map.md)** |           **26** <br/>**[Choropleth map](daily/day26_Choropleth%20map.md)**           |                   **27** <br/>**[Heatmap](daily/day27_Heatmap.md)**                    | **28** <br/>**[The Earth is not flat](daily/day28_The%20Earth%20is%20not%20flat.md)** |
|                                   **29** <br/>**[NULL](daily/day29_NULL.md)**                                   |                    **30** <br/> **[Metamapping day](daily/day30_Metamapping%20day.md)**                     |                                                                   |                                                                     |                                                                                       |                                                                                        |                                                                                       | -->

## Users Langauge

Tweets with `#30DayMapChallenge` hashtag from 2022-11-01 to 2022-11-30 are in **33** languages (Twitter account setting) including `es`, `en`, `fr`, `ja`, `lv`, `it`, `nl`, `cy`, `in`, `und`, `ca`, `qme`, `de`, `fi`, `et`, `cs`, `lt`, `uk`, `da`, `ro`, `pt`, `ar`, `iw`, `tl`, `ht`, `pl`, `tr`, `eu`, `sl`, `zh`, `sv`, `ru`, `no`.

## Users Location (to do)

By geocoding users location in their profile, I plot the map of distribution of users who involves in this event. Geocoding process is conducted via https://geocode.localfocus.nl/

<!-- ![images](./user_loc.png) -->

## Map Wall (to do)

The map wall includes 95\*95 maps from the 9036 images attached in #30DayMapChallenge tweets. The map walls with different background can be found in `.\static` folder. Since the maps were automatically collected from media url in tweets' metadata, you may find a few 'noise' or duplicate images.

<!-- ![images](static/mapwall_white_64.jpg) -->

## #30DayMapChallenge stats in last year

**[#30DayMapChallenge 2020](archive/2020/)**
**[#30DayMapChallenge 2021](archive/2021/)**

<!-- Inspiration for the repo came from [Kalle Hallden](https://www.youtube.com/channel/UCWr0mx597DnSGLFk1WfvSkQ). -->
