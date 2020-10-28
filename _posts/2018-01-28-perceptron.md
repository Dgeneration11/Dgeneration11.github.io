---
title: "Covid-19 Live Tracking Project"
date: 2020-05-02
tags: [Data Wrangling, Data Science, COVID-19, Data vizualization]
header:
  image: "/images/perceptron/COVID.png"
excerpt: "Data Wrangling, Data Science, COVID-19, Data vizualization"
mathjax: "true"
---

# H1 Heading

## H2 Heading

### H3 Heading

**Coronavirus** or **COVID-19** doesn't need any introduction. WHO has already declared it as pandemic because of it's last couple of weeks impact.

As of now, most of people are working from home. I decided to utilize my time to build a Python Script that takes the data as input from the official website of Ministry of Health and Family Welfare, Government of India and turn that information to use to plot graphs in Python. I know so many scripts are already available on the Internet, but building yours is a good practice.

Here's the [link](https://github.com/Dgeneration11/COVID-19-Live-Tracking-Cases-in-INDIA) to the github file.

### Packages used-
* Pandas
* Seaborn
* Matplotlib
* Requests
* BeautifulSoup
* Prettytable

### How is it working?
1. So basically, we are sending<b> GET HTTP</b> request to the url where you want the data from, and respond will be in HTML content itself. To do this we are using Requests library.<br>
2. Then we will use BeautifulSoup library to get the data from HTML content and store it in a form of List.<br>
3. Output the data in formats such as .csv .xlsx .json,etc. and we can use this data to plot graphs, tables, charts,etc using matplotlib, searborn, geopandas,etc libraries.

### Extras-
If you want to learn more about scraping data from websites, there is a great blog. So check that out.
Here's the external [link](https://www.pluralsight.com/guides/extracting-data-html-beautifulsoup).

