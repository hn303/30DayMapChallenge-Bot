## 30DayMapChallenge-Bot
Monitoring [#30DayMapChallenge 2020](https://github.com/tjukanovt/30DayMapChallenge) launched by [Topi Tjukanov](https://twitter.com/tjukanov) on Twitter. Trying to engage this wonderful event in a special way. 

![images](./static/logo-2021.png)

### Twitter Data
#30DayMapChallenge related tweets are collected via Twitter REST API with the hashtag `#30DayMapChallenge`. The example of raw .json data returned via Twitter REST API can be found in `.\example` folder. This repo only select serveral attributes from tweet metadata including: `tweet_id`, `tweet_text`, `language`, `tweet_created_at`, `retweet`, `favorite`, `hashtags`, `user_id`, `user_name`, `user`, `user_loc`, `user_follower`, `friends_count`, `media` and save as .csv file in `.\data` folder.

Note:
-  `#30DayMapChallenge` with image attached
- search tweets by date since everyday has diffferent map theme
- cleanning process for late entry tweets is only conducted in first two days
- some tweets in certain time zones (such as Pacific Time) might be searched and archived in file next day



### Daily Tweets Statistics
![images](./static/maps_count.png)


### Top Favourited/:heart: Maps

As [Topi Tjukanov](https://twitter.com/tjukanov) mentioned in [30DayMapChallenge](https://github.com/tjukanovt/30DayMapChallenge) page, this map challenge is NOT a competation. Although this repo sorts maps by their favorite count and retweet count, this repo never intend to compare all the wonderful maps but create a altas of inspiring maps for a reference. I am also interested in exploring topis in replies in those maps with more attention (if i have time).

Top favorited tweets refers to the tweets get many `liked`/:heart:. The faviorite count is extracted from `favorite_count` value in tweet metadata. 

| |||December 2021||| |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Mon** | **Tue** | **Wed** | **Thu** | **Fri** | **Sat** | **Sun** |
| **1** <br/>**[Points](daily_md/day1.md)**| **2** <br/>**[Lines](daily_md/day2.md)**   |**3** <br/>**[Polygons](daily_md/day3.md)**   |**4** <br/>**[Hexagons](daily_md/day4.md)**    | **5** <br/>**[Data challenge 1: OpenStreetMap](daily_md/day05_Blue.md)**   | **6** <br/>**[Red](daily_md/day06_Red.md)**   | **7** <br/>**[Green](daily_md/day07_Green.md)**  |
| **8** <br/>**[Blue](daily_md/day08_Yellow.md)**  | **9** <br/>**[Monochrome](daily_md/day09_Monochrome.md)** | **10** <br/>**[Raster](daily_md/day10_Grid.md)**  | **11** <br/>**[3D](daily_md/day11_3D.md)**  | **12** <br/>**[Population](daily_md/day12_Map%20not%20made%20with%20GIS%20software.md)**  | **13** <br/>**[Data challenge 2: Natural Earth](daily_md/day13_Raster.md)**  | **14** <br/>**[Map with a new tool](daily_md/day14_Climate%20change.md)**  |
|  **15** <br/>**[Map made without using a computer](daily_md/day15_Connections.md)**  |  **16** <br/>**[Urban/rural](daily_md/day16_Island(s).md)**  |   **17** <br/>**[Land](daily_md/day17_Historical%20map.md)**   |  **18** <br/>**[Water](daily_md/day18_Landuse.md)**    |   **19** <br/>**[Island(s)](daily_md/day19_NULL.md)**   |   **20** <br/> **[Movement](daily_md/day20_Population.md)**  |   **21** <br/> **[Elevation](daily_md/day21_Water.md)**  |  **22** <br/>**[Boundaries](daily_md/day22_Movement.md)**    |
|   **23** <br/>**[Data challenge 3: GHSL Global Human Settlement Layer](daily_md/day23_Boundaries.md)**   |   **24** <br/>**[Historical map](daily_md/day24_Elevation.md)**   |   **25** <br/>**[Interactive map	](daily_md/day25_COVID-19.md)**   |   **26** <br/>**[Choropleth map](daily_md/day26_Map%20with%20a%20new%20tool.md)**   |   **27** <br/>**[Heatmap](daily_md/day27_Big%20or%20small%20data.md)**   |   **28** <br/>**[The Earth is not flat](daily_md/day28_Non-geographic%20map.md)**   |  
| **29** <br/>**[NULL](daily_md/day29_Globe.md)**    |  **30** <br/> **[Metamapping day](daily_md/day30_A%20map.md)**   |     |     |     |     |     | 


<!-- ### Users Langauge

Tweets with `#30DayMapChallenge` hashtag from 2020-11-01 to 2020-12-02 are in **32** languages (Twitter account setting) including `es`, `en`, `fr`, `und`, `de`, `ru`, `lt`, `lv`, `no`, `tr`, `in`, `nl`, `pt`, `ja`, `et`, `ro`, `ca`, `ht`, `tl`, `pl`, `sv`, `da`, `it`, `bg`, `fi`, `eu`, `ar`, `vi`, `cy`, `ko`, `is`, `uk`.

### Users Location
By geocoding users location in their profile, I plot the map of distribution of users who involvs in this event. Geocoding process is conducted via https://geocode.localfocus.nl/

![images](./user_loc.png) -->

<!-- ### Map Wall

The grid graph (87*87) includes 7569 maps. The seperated maps(resized) can be found in `.\mapwall` folder. Since the maps were automatically collected from media url in tweets' metadata, you may find a few 'noise' or duplicate images.

![images](mapwall/mapwall_white_64.jpg)


Inspiration for the repo came from [Kalle Hallden](https://www.youtube.com/channel/UCWr0mx597DnSGLFk1WfvSkQ). -->