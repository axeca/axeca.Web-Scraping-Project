# Scraping Systembolaget

Scraped a website on information about red wines, cleaned the data and stored it in a csv-file.

As systembolaget is using react, only beautiful soup didn't cut it. So I used selenium to scroll through and collect all the links to each red wine on the site. Then, using a loop selenium went and scrolled every collected url.
