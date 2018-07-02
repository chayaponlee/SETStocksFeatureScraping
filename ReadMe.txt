This code is designed to scrape company perfomances/metrics from SET Thailand
such as stock price, ROE, dividends and so on. This is done because SET data
is rare to find and if there is they will come with a significant cost. This data
will be used future analysis.

Folder ListsofCompanies contains csv files of company names. Each csv file 
corresponds to one of the 28 sectors in SET stocks

Folder CompletedScrape contains csv files of the scraped data and each csv file
corresponds to one of the sectors

The input to the code is the list of companies csv. The output will be the scraped
csv of that particular input. This code accepts one csv (one sector data) at a time.