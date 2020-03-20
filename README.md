# stock-analysis
Module 2 Stock Analysis
# Challenge
I refactored the code to make it more efficient.  The main question from the beginning of the exercise was whether higher trading volumes are associated with better performing stocks.  It appears there is a loose relationship with two of the three stocks that has positive returns being in the top 3 for trading volume.  


There are several problems with this analysis: correlation is not causation, there are more factors to a stock's return than trading volume, and often stocks will have big trading volume when traders are looking to exit after bad news.  For instance, JKS was down a similar amount as DQ, but it has 50% more trading volume, and the next two worst returns were the second and fourth highest trading volume.  This tells us that other things drive returns, and indeed trading volume may be caused by these other factors.  


I would add data to this analysis such as float (tradable shares) vs total shares outstanding, and percentage of earnings and revenue beats vs consensus (how many quarters did they beat and by what margin did they beat).  

Finally, some things may not be able to be captured by this data.  For instance the #2 and #4 highest volume traders are in solar panels and the Chinese were very aggressive with pricing in 2018 and many other years, so they had to match price but could not get costs down fast enough so margins suffered.  This can be captured by earnings trends, and potentially misses if analysts do not lower their estimates in time, but earnings and revenues are a result of what is really going on which is a price war with Chinese solar companies.  

For the tools we are given, we cannot web scrape for sentiment and use natural language processing which would then capture the cause of the stock decline, not the result (which is higher volumes and volatility).
