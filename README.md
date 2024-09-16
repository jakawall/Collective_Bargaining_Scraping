# Overview

This projects scrapes and (very primitively) analysis collective bargaining agreements in Austria. Unfortunately, since the amount scraped is very larger (54.000 websites resulting in about 4gb of text data), and we want to avoid causing any more traffic to the ÖGBVerlag who kindly gave us access to their database of collective bargaining agreements, the code here is written in a way as to exemplify how the entire scraping process works.

We also had a problem fully automating the scraping process due to the cookie-policy popup that comes up when you first load the site, and throws up a "NoSuchElementException" no matter what we tried. As such, also the Snakemake file does not work, and there will be an error at that point in the script. To run the script manually, one simply needs to click "alles ablehnen"/"alles akzeptieren" the first time when opening the website, everything else should proceed without any problem.  

# Packages
Necessary packages can be found in and installed using cb_scraping.yaml


