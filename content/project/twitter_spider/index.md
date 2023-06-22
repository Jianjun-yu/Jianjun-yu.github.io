---
title: Twitter spider
summary: A python package to collect public personal information of Twitter users
tags:
  - twitter_spider
date: '2022-02-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Chunying Hua's Twitter page
  focal_point: Smart

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

---

The Twitter Spider is a Python package developed as an enhancement of Scweet, a simple and unlimited Twitter scraper. While Scweet serves its purpose well, it falls short when it comes to downloading a large volume of Twitter account information. Additionally, it encounters bugs when attempting to download information from users who have protected their personal data. In response, I have modified the package to address these limitations, ensuring its efficient performance in downloading extensive Twitter account information. Moreover, I have updated the code to enable the retrieval of all publicly available personal information from a user, while ensuring that users who protect their information do not impede the scraper's functionality.

The Twitter Spider consists of two primary functions. The first function is the "Follower Spider," which retrieves the usernames of all followers associated with a particular user. This function can obtain approximately 4000-5000 followers per hour.

The second function is the "User Information Spider," which retrieves public personal information from Twitter users. Unlike the follower spider, this function does not have a specific speed limit. The download speed is contingent upon the internet speed and the memory size of the computer running the package.

By employing the Twitter Spider, users can efficiently gather substantial amounts of Twitter account information, overcoming the limitations present in the original Scweet package.

The package is scheduled to be released to the public following the publication of the research paper titled "Who are the Followers of Chinese Public Diplomacy on Twitter." However, if you are interested in using the package immediately, please feel free to contact me. I would be more than happy to assist you!