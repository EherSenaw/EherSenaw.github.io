---
layout: post
title: "Post: Scrapy+Selenium Web Crawler-1"
categories:
  - post
tags:
  - post
  - scrapy
  - selenium
  - crawler
---
**About this section**: 

Follow these simple steps to start web crawling with Scrapy & Selenium.

Since this is first post of *Scrapy+Selenium Web Crawler* series, this post would cover initial settings.


## **Environment**
* Ubuntu 18.04
  > Doesn't **NEED** to be **18.04**. Other versions would fit well because docker will be used.
* Docker
  > Install latest version.

## **Steps**
1. Clone the repo from **[link](https://github.com/Jamesway/docker-scrapy-selenium-chrome)**
    > Note: linked repository is not mine. So if you think this repo was helpful, please star this repo to show appreciation for the repo's owner.
2. Go to your project's folder and open terminal
    > ``` docker run --rm -v $(path to current project folder):/code jamesway/scrapy startproject (project_name) .```

    ![image-1-1](http://ehersenaw.github.io/images/2020-12-29-post-scrapy+selenium-1/1-1.png)

3. Done!

    ![image-1-2](http://ehersenaw.github.io/images/2020-12-29-post-scrapy+selenium-1/1-2.png)


### Dockerfile repo source: [Jamesway](github.com/jamesway)
