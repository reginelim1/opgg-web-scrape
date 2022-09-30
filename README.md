# opgg-web-scrape
Scrape opgg page <br>
\-trying to scrape opgg as part of my interest\- 

Google colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/reginelim1/opgg-web-scrape/blob/main/webscrapingusingpython.ipynb)

**Firstly,** <br>
**Input for url**
1. Enter the region of the summoner
- South Korea: kr
- North America: na
- EU West: euw
- EU Nordic & East: eune
- Oceania: oce
- Japan: jp
- Brazil: br
- LAS: las
- LAN: lan
- Russia: ru
- Turkey: tr
2. Enter summoner's name

<br>
<b> The maximum number of games that could be scraped from opgg using while-true: 500 ±10 </b>
<br>
<br>

The ipynb file contains three parts: <br>
a. Scrape details of specific player (that has an opgg page) from opgg website and store the details in dataframe <br>
b. Some simple analysis and simple plots <br>
c. One simple machine learning method (decision tree) for predicting the status (victory or defeat) of the game, in this case, only "Ranked Solo" queue type were used. <br>

<h5>a. Web scraping </h5>
For web scraping, <b>Selenium</b> and <b>Beautiful Soup</b> were used. The data were store in form of dataframe with the help of <b>pandas</b>.

<h5>b. Simple analysis </h5>
Different plots were created, eg. <br>
- Pie Chart
- Bar chart (horizontal and vertical)
- Scatter matrix
- Scatter plot
- KDE plot
- Heatmap
- Boxplot
- Line graph
<br>
Different tables were generated using different conditions, eg. average victory and defeat time for each champion. <b>groupby</b> and <b>apply</b> were mainly involved.

<h5>c. Machine Learning</h5>
Play with simple machine learning. In this project, decision tree was involved. Two different model evaluation methods were involved: <b>train test split</b> and <b>cross validation</b>. Both generate different results.
