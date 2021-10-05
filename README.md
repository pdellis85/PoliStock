# PoliStock

### Project Summary

We set out to observe correlations between presidential elections and the stock market over the past 20 years. We'll examine the relationship between elections and the market from two perspectives: how market performance correlates to election outcomes and how one party's win correlates to the market. Our market analysis will focus on four S&P500 sectors along with the S&P 500 index.  

We used the Yahoo_fin Library to pull closing data for the S&P 500 index and four S&P 500 sectors:

1. Energy Sector (XLE)
2. Finance Sector (XLF)
3. Technology Sector (XLK)
4. Healthcare Sector (XLV)

We sliced the closing data for three months prior to and three months after each 21st century presidential election.  Then we ran some calculations to obtain the daily returns, mean returns, and standard deviation of the daily returns.

### Does a correlation exist between market performance and the outcome of presidential election results?

An article on Kiplinger posits that "...the stock market has an uncanny ability to predict who will call the White House home for the next four years. If the stock market is up in the three months leading up to the election, put your money on the incumbent party. Losses over those three months tend to usher in a new party" (Smith and Woodley, 2020). Has this held true in the 21st century?

### Does a correlation exist between presidential election results and market performance?

When we first began this project, this was the primary question we set out to answer.  Conventional wisdom holds that the occupant of the White House affects the market.  Is this true, at least right after an election?

### Analysis

Our data show the following:  

1. Bush’s first win (2000) - before and after the election, the market was down.  Energy and Finance were both up; Technology and Healthcare were both down.
2. Bush’s second win (2004) - before and after the election, the market was up.  All sectors were up as well, expect for Healthcare, which was down before the election.
3. Obama’s first win (2008) - before and after the election, the market and all sectors were down.
4. Obama’s second win (2012) - before and after the election, the market and all sectors were up, except for Technology, which was down before the election.
5. Trump’s win (2016) - before the election, the market was down; after the election, the market was up.  All sectors were up, except for Healthcare, which was down before the election.
6. Biden’s win (2020) - before and after the election, the market was up.  All sectors were up, except for Energy, which was down before the election.

For Bush's and Obama's first wins and Trump's win, the market was down in the three months prior to election, and a president was elected from a different party than the incumbent president. For the second Bush and Obama elections, the market was up prior to the election, and the incumbent was re-elected. For Biden's win, the market was up, and the incumbent was not re-elected.

In our data set, there are three Republican wins.  After two of them, the market went up after the wins.  It went down after one Republican win.  There are also three Democratic wins, and the same is true - the market went up after two wins and down after one win.

We remember that in 2008 there was an economic recession, which depressed the market.  We also remember that in 2020, there was a pandemic, which affected global markets.

We did not find a clear correlation between who occupied the White House and market performance.  Further analysis and an expanded dataset might show a correlation, but our research suggested that this would not be the case.  We did see a correlation between market performance prior to elections and whehter or not the incumbent party retained control of the White House, as suggested by Smith and Woodley.

Further analysis of market performance and Presidential elections in the 21st century will be interesting as the century unfolds.  

### Data Sources and Works Consulted

AlgoTrading101. *Yahoo Finance API - A Complete Guide.* Retrieved October 2, 2021, https://algotrading101.com/learn/yahoo-finance-api-guide/.

Brookings. (February 2021). *Vital Statistics* on Congress. http.s://www.brookings.edu/multi-chapter-report/vital-statistics-on-congress/.

Klebnikov, Sergei and Halah Tourylai. (2020 July 23). "We Looked At How The Stock Market Performed Under Every U.S. President Since Truman — And The Results Will Surprise You." *Forbes*. https://www.forbes.com/sites/sergeiklebnikov/2020/07/23/historical-stock-market-returns-under-every-us-president/?sh=63881d81faaf.

Patton, Mike. (2020 August 25). "How Stocks Performed Based On Political Party Of President And Congress: 1977 Through 2019." *Forbes*. https://www.forbes.com/sites/mikepatton/2020/08/25/how-stocks-performed-based-on-political-party-of-president-and-congress-1977-through-2019/?sh=31592b575f88.

Smith, Anne Kates and Kyle Woodley. (26 October 2020). "How Presidential Elections Affect the Stock Market." *Kiplinger*. https://www.kiplinger.com/investing/stocks/601629/how-presidential-elections-affect-the-stock-market. A

StockCharts. *Sector Summary for S&P Sectors*. Retrieved October 1, 2021, https://stockcharts.com/freecharts/sectorsummary.html. 
