# python-crawl

Demo of collecting data code.

## Document :notebook:

|No |File Name       |Description                                                                    |freq     |Input                         |Output                                                                              |
|---|----------------|-------------------------------------------------------------------------------|---------|------------------------------|------------------------------------------------------------------------------------|
|1  |tw_index_price  |Taiwan's indices intraday quote information.                                   |intraday |date(str)                     |df(dataframe)                                                                       |
|2  |tw_stock_price  |Taiwan listed stock's price.                                                   |daily    |date(str)                     |df(dataframe)                                                                       |
|3  |tw_stock_frp    |Taiwan listed and otc firm's income statement.                                 |quarterly|sym(int) year(int) season(int)|df(dataframe)                                                                       |
|4  |tw_stock_margin |Taiwan listed firm's margin purhcase and short sales information(including ETF)|daily    |date(str)                     |df(dataframe)                                                                       |
|5  |tw_stock_price_2|Taiwan listed stock's price(exclude corp bonds)                                |daily    |date(str)                     |df(dataframe)                                                                       |
|6  |ptt_crawler     |Post's information of Ptt(e.g. title, author, comments, etc.)                  |-        |-                             |url(str) board(str) author(str) title(str) post_time(str) content(str) comment(dict)|
