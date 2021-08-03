# Reddit Data Scrape

Scraping Reddit data to form a plot of countries people will likely not revisit.

## Prerequisites


- .ipynb reader such as Jupyter Notebook
- PRAW
- GeoPandas
- Numpy
- Pandas


## Installation


GeoPandas:

`conda install geopandas`

or 

`pip install geopandas`


PRAW:

`pip install praw`


## Usage


This file is intended to graph the countries that Reddit users are least likely to revisit, according to an [AMA](https://www.reddit.com/r/AskReddit/comments/om38bx/what_is_one_country_that_you_will_never_visit/) from 18 July 2021.
Using PRAW, the file reads through the top level comments in the post, searches for a country name, and appends  results to a dataframe. The dataframe is then used in accordance with a shape file to plot a graph of the earth and colour countries according to their amount of hits.


## Results

![data2](https://user-images.githubusercontent.com/38352176/128013004-b269964f-df10-4dec-9d82-6ee6627b4acb.PNG)
