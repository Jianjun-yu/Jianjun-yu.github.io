---
title: WeChat data
summary: More than 3 million posts made by Chinese prefecture-level city government official WeChat propaganda accounts.
tags:
  - wechat_data
date: '2022-02-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: WeChat official account,Qingdao fabu(release)
  focal_point: Smart

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

---

I have collected all the posts published by official WeChat propaganda accounts of Chinese prefecture-level city governments, starting from the day each account was opened until December 2020. By that time, a total of 282 Chinese city-level governments had opened their WeChat propaganda accounts, accounting for approximately 85 percent of all cities. Generally, each city has only one propaganda account, and if multiple accounts exist, I focused on the most active one. These propaganda accounts typically have names similar to the corresponding city names, with the addition of "fabu" (release) in most cases. In total, over 3 million posts have been collected.

The data is stored in two SQL tables. The first table contains 10 columns: city name, account name, city code, time of post release, post title, post URL (including the unique identifier of each post), cover image, number of posts in a block (as posts are released together in one block), and whether it is the headline of a block. The second table consists of 11 columns: city name, city code, post URL, time, headline status, number of posts in a block, number of readers, whether the post includes comments, number of likes, and number of shares.

The data is scheduled to be released to the public following the publication of "Signaling to Leaders, not People: Understanding the Mechanics of Chinese Local Government Propaganda." However, if you are interested in using the data immediately, please feel free to contact me. I would be more than happy to assist you!
