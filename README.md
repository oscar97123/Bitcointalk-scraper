# Bitcointalk scraper
---
A web scraper which capture the Title, Authors, Membership Lv, Num of merited, Text, Date-time, and Original poster from the "Bitcoin Discussion" sub-category discussions on 
bitcointalk.org.

## Features
---
- Collect the discussion's title, authors, membership level, num of merited, content, date-time, and original poster information
- Identify total num of "merited by" received
- Remove quote in replies for preventing duplicated text which will affect NLP performance (if undergoes) 

## How to use
---
1. Install required packages (BeautifulSoup == 4.9.3  &  pandas == 1.4.1)
2. Change line 10 to specify how many pages to be crawled
3. Specify the path for the output files
4. Start running~

