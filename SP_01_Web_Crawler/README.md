# DAND Web Crawler

Go to a Wikipedia page you find interesting, or just a random one and click the first link. Then on that page click the first link in the main body of the article text and just keep going. You could try it multiple times for different pages and see that you observe recurrent behaviours, such as ending up on the Wikipedia page about philosophy, ending up in a repetitive cycle, or ending up in a Wikipedia page without links.

This web crawler intends to show these patterns : it starts from a random page from Wikipedia, then clicks the first link in the main body of the article text and just keeps going, until it either find the Wikipedia page about philosophy, a cycle, a Wikipedia page without links or the process become too long.

Here is an example of how it works. The Web Crawler started from the randomly selected page about France, and after clicking again and again the first link in the main body of the article text it found the Wikipedia page about philosophy!

![example](https://github.com/maphdev/DAND_Web_Crawler/blob/master/target_article_found_web_crawler.png)

### Requirements

In order to use this web crawler you need to install the *requests* and *BeautifulSoup* libraries:

With Conda :
```bash
  conda env create -f environment.yaml
```

With pip :

```bash
  pip3 install requests
  pip3 install beautifulsoup4
```
