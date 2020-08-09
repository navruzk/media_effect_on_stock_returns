# Media effect on stock returns

What are the main drivers of stock price movement? This is one of the questions of investors and researchers. Fundamental analysis tells us to focus on the market index in order to investigate the stock price movement. Since the efficient market hypothesis assumes that prices had already incorporated every accessible public news and information. Fortunately, in this data abundant time we can actually gather and analyze news articles quite easily and efficiently.

This tutorial is about the exploration of the imminent effect of news on stock price movements. First, I scraped news articles to gather information about the specific stock. I focused only on Nasdaq.com news section to save time, however, the same analysis could be extended in a larger scale to cover other news sources.

Following the scraping process, text is cleaned thoroughly and analyzed through sentiment analysis (VADER) to investigate if the text contains negative or positive sentiment about the stock. Lastly, I used newly constructed variable to explain stock returns together with market return (empirical CAPM).

Notebook is given [here](https://navruzbek1992.github.io/data_science_challenges/projects/news_and_boeing_stocks.html).

### Prerequisites

Python is required.

### Installing

Install required libraries.

```bash
pip install -r requirements.txt
```
