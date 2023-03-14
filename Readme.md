one of my goals is implementing a crawl dashbard with some action and scheduler. When I started to find anybody else who thinks of it I found some good repos:

https://github.com/DmitryKey/url-crawler
https://github.com/gurtejrehal/FALCON---AI-Data-Crawler
https://github.com/Lifeni/crawler-test

Exactly what I need as web app is [Web Alert link:https://webalert.me] android apk.


Although It can be something like [Airbyte link:airbyte.io ??] as [ETL links:wiki ?? ] but I've never seen ETL with crawller. Also like [processmaker link:processmaker.com ??] it can be a BPMN, but in this case you can't design yourself and it's single responsible for crawlling and schedulling a crawl with approach of extending in feauture as global scheduller.

so I preffer name it scheduller-crawl-action-dashbaoard

# Proposal

At first I beleive that it can do with laravel shcedule and basic [Gazzel link: ??] curl to gather data from any url. After that it may concern what will happen if the IP banned or return some error. So it's better to start with a simple idea that I need just a dashboard to list some schdeduled job as curl and then improve it in [Roadmap link:#roadmap ??] section.

# Roadmap

* dashboard to view crawlled urls
* changing intervall in dashboard
* show response of crawlled urls in dashbard
* add static action to save crawlled urls in database as a Model
* try to make action dynamic in help of [processmake link: processmaker.com ??]
* try to make specific action based on older crawls and responses
* work on DOM responses
* implement API to expose gathered and structured data 
* try to demo the repo gllobally and get feedback
* debug 
* design new roadmap