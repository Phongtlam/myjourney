+++
date = "2016-11-05T19:41:01+05:30"
title = "r-short"
draft = false
image = "portfolio/r-short/thumb.png"
showonlyimage = false
weight = 3
+++

<p>
<a href="https://r-short.herokuapp.com/" target="_blank"><strong>r-short</strong></a> is a service used to shorten URLs. Built on the idea of bit.ly, this basic application is light weight, can easily be deployed on a shorter domain name to achieve better usage.
</p>

<!--more-->

<div><a href="https://r-short.herokuapp.com/" target="_blank"><strong>Link to website</strong></a></div>
<div><a href="https://github.com/Phongtlam/URL_shortener" target="_blank"><strong>GitHub source code</strong></a></div>
<div class="work"><a href="https://r-short.herokuapp.com/" target="_blank"><img src="/myjourney/portfolio/r-short/screen.png"></a></div>

<br>

## Project overview

- Created using React.JS to achieve a basic and intuitive front end system
- Custom CSS and basic layout with Bootstrap for UI design
- Engineered back end server with Node.JS/Express
- Utilized Redis as a blazing fast, in-memory data storage solution

<div class="reactchess"><img src="/myjourney/portfolio/r-short/techstack.png"></div>

<br>

## Redis
This is an amazing open-source database solution. Utilized in-memory key-value storage, the software has a number of features that are available in other database systems, such as replication, tunable levels of durability, cluster, high availability. The most notable aspect of Redis is that even though it is stored on disk, it is served and modified into the server memory. Redis is **FAST**, yet non-volatile at the same time.

The reason that I picked Redis for this project is mainly due to users' experience. A URL shortener service needs to be fast, since a user would already need to go through an extra link to get where he/she wants. A fast database is needed and nothing does the job better than Redis.
