# Data Scientist Task

## Description of the Task

The crypto market has been plagued with cases of fraud, or cases where the project never comes to fruition. Without regulatory oversight and mandated disclosures, investors often have minimal information about a crypto asset. Most crypto asset investors are retail investors who lack both the expertise and resources to adequately evaluate the crypto assets they invest in. Additionally, the volume of the market makes it nearly impossible for an investor to analyze each token properly.

In this research task, we want to develop a risk rating model for analyzing crypto assets as an investment, i.e. to explore how risky an asset is based on its past performance. We have the dataset which offers the attributes for evaluating market risk that corresponds to each token. Column cs_rating is our target variable, which should contain information regarding the rating of an asset.
The main goals of this task would be:
To conduct the research regarding the predictive power of price data for asset rating
To predict rating for the assets whose rating is not given

## Structure and Content of Data

Data is collected through APIs from CoinMarketCap (https://coinmarketcap.com/) - CS_Crypto_Asset_Dataset

### Parameters

| COLUMN NAME | TYPE | DESCRIPTION |
|--|--|--|
|id|integer|Unique ID of the asset|
|cs_rating|string|Rating provided by ChainScore - A3 to D1 (A3, A2, A1, B3, B2…)|
|name|string|Asset Name|
|symbol|string|Asset Ticker Symbol|
|slug|string|Alternative Asset Name|
|num_market_pairs|integer|Number of Market Pairs in existence. For example, market pairs for BTC could be BTC/INR, BTC/USD, BTC/ETH, and many more|
|date_added|datetime|Date the asset was  added to market|
|tags|string|Identifiable tags, asset category, more|
|circulating_supply|decimal|Current circulating supply in the market|
|total_supply|decimal|Total supply the asset have|
|cmc_rank|integer|Rank from CoinMarketCap|
|last_updated|datetime|DateTime the information was last updated on|
|quote_eur_price|decimal|Last Updated Price of Asset|
|quote_eur_volume_24h|decimal|24hr Trading Volume|
|quote_eur_volume_change_24h|decimal|24hr Trading Volume Change|
|quote_eur_percent_change_1h|decimal|1hr % change of price|
|quote_eur_percent_change_24h|decimal|24hr % change of price|
|quote_eur_percent_change_7d|decimal|7 Days % change of price|
|quote_eur_percent_change_30d|decimal|30 Days % change of price|
|quote_eur_percent_change_60d|decimal|60 Days % change of price|
|quote_eur_percent_change_90d|decimal|90 Days % change of price|
|quote_eur_market_cap|decimal|Circulating Market Cap|
|quote_eur_market_cap_dominance|decimal|% of total crypto market cap|
|quote_eur_fully_diluted_market_cap|decimal|Fully Diluted Market Cap|
|quote_eur_last_updated|datetime|Last DateTime stamp the price was updated|

The research can be performed/done in a candidate’s preferred tool (R, Python, Excel,. . . ).
All the results, description/explanation of the results, applied techniques and methods as well as the descriptions of the intermediate steps, ideas and proposals for further research should be provided in the solution to be send to prasad@chainscore.finance
