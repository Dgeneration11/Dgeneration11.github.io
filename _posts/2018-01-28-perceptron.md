---
title: "Covid-19 Live Tracking Project"
date: 2020-05-02
tags: [data wrangling, data science, messy data]
header:
  image: "/images/perceptron/percept.jpg"
excerpt: "Data Wrangling, Data Science, COVID-19, Data vizualization"
mathjax: "true"
---

# H1 Heading

## H2 Heading

### H3 Heading

Coronavirus or **COVID-19** doesn't need any introduction. WHO has already declared it as pandemic because of it's last couple of weeks impact.

As of now, most of people are working from home. I decided to utilize my time to build a Python Script that takes the data as input from the official website of Ministry of Health and Family Welfare, Government of India and turn that information to use to plot graphs in Python. I know so many scripts are already available on the Internet, but building yours is a good practice.

And here's some *italics*
What about a [link](https://github.com/Dgeneration11/COVID-19-Live-Tracking-Cases-in-INDIA)?

Here's a bulleted list:
* First item
+ Second item
- Third item

Here's a numbered list:
1. First
2. Second
3. Third

Python code block:
```python
    import numpy as np

    def test_function(x, y):
      z = np.sum(x,y)
      return z
```

R code block:
```r
library(tidyverse)
df <- read_csv("some_file.csv")
head(df)
```

Here's some inline code `x+y`.

Here's an image:
<img src="{{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg" alt="linearly separable data">

Here's another image using Kramdown:
![alt]({{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg)

Here's some math:

$$z=x+y$$

You can also put it inline $$z=x+y$$
