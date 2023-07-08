---
title: WeChat spider
summary: A Python package to collect WeChat official account posts.
tags:
  - wechat_spider
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

The WeChat Spider is a Python package designed for automatically downloading WeChat official account posts. Unlike relying on specific APIs, this package emulates human interaction with the WeChat desktop client and monitors the communication between the user's client and the WeChat server. The downloaded posts are then automatically saved in a local SQL database. The package encompasses three main functions.

The first function is the "Post ID Spider," which retrieves the unique IDs of the posts. These IDs can subsequently be used to access the content and additional information of each post. However, it is important to note that the WeChat server imposes limitations on the number of posts an account can view in a day. Currently, each account is permitted to send 300 requests to the WeChat server. Each request can retrieve 10 blocks of posts, with each block containing 2-10 posts.

The second function is the "Like, Viewer, and Comment Spider." This function utilizes the post IDs obtained to gather information about the posts, including the number of likes, the number of readers, and the comments associated with each post. It is capable of retrieving information for approximately 2400 posts per hour.

The third function is the "Content Spider," which retrieves the detailed content of each post using the respective post ID.

The package is scheduled to be released to the public following the publication of "Signaling to Leaders, not People: Understanding the Mechanics of Chinese Local Government Propaganda." However, if you are interested in using the package immediately, please feel free to contact me. I would be more than happy to assist you!
