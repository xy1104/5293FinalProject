# Description

we will retrieve data from websites IMDb (America)and douban (China). The data for this report comes from the film data resources.
Grab and visual analysis of any movie short reviews (hits) as well as their scores from the websites IMDb (America)and douban (China). The data will contain movie IDs, budget, popularity, revenue, runtime,vote and other informations. We will do the Data Cleaning first.
For Douban, it is a non-dynamically rendered page, which is the traditional way of rendering, and simply requests the URL to get the data. We find that unlogged users can only access the priority interface, and logged in users can only have access to the following page. We have checked the parameters of the request and find that it is a normal request without encryption, so can use some packages to capture packets.
For IMDb, We tried several different advanced searching and view the returns, we find that the subsequent page URL is even more unpredictable. Since there are almost no comments on movies after 10,000 movies, the review crawl is conducted for the first 10,000 movies. After that, we can get the contain movie IDs, budget, popularity, and also the review page for the movie and get all non-Spoiler user reviews for the movie along with the user ID.

## Link to the book URL
https://xy1104.github.io/5293FinalProject/

*This repo was initially generated from a bookdown template available here: https://github.com/jtr13/EDAVtemplate.*	




