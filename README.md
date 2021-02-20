# Web-Scrapers
A repository that includes all web scrapers built.

---
###  Sephora_scraper
This web crawler utilized the beautiful Soup module and Selenium to scrape the 
sephora women's fragrance website using Python. Selenium was used to overcome
LazyLoading of js in the website, as to auto scroll the page to the middle and
the end in order to crawl the whole website. 
To get all the urls for a given product in the webpage, use:
```
getPageUrls()
```
To get the product information in a product url, use:
```
getPageDate()
```

### TutorWebsite_scraper
This is a simple website scraper used to scrape a tutor webiste written in R.
I wanted to look for tutor jobs, but didn't want to waste time looking for
a match based on my criterias. This script allows you to specify the 
restrictions to do selection.
This script only handles the <[Tutor Website](http://tutors.tw/case2.htm).
Specify the restrictions in the function filter_tutor(). 
```
filter_tutor() 
```

### Xvideos_scraper
This is a scraper just for fun, as I was curious in using Machine Learning 
to make the recommendations more accurate. I tried using K means to group the 
videos and found out it resulted in 4 categories (scree plot). Additional
modeling such as Random Forest didn't yield good results, the accuracy was 
a little over 50%.

