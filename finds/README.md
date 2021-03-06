# Financial Data Science python library

These modules support retrieving and manipulating structured and
unstructured financial data sets, and fitting and testing quant and
machine learning models.

[https://github.com/terence-lim/financial-data-science](https://github.com/terence-lim/financial-data-science)

by: [Terence Lim](https://www.linkedin.com/in/terencelim)

&nbsp;


### [taq.py](taq.py)

- Class and methods to preprocess and analyze TAQ trade and quotes tick data

  - NYSE Daily TAQ, bid-ask quotes, trade conditions, tick test


### [sectors.py](sectors.py)

- Implement industry sectoring, and convenience methods for BEA data

  - pandas, requests, sqlalchemy, json
  - SIC, NAICS, Fama-French industry crosswalks
  - Bureau of Economic Analysis, Input-Output Use Tables

### [graph.py](graph.py)

- Convenience methods for igraph and networkx modules

  - Network science, community detection, centrality, modularity
  - igraph, networkx


### [alfred.py](alfred.py)

- Convenience class and methods to access ALFRED/FRED apis and FRED-MD/FRED-QD

  - FRED, ALFRED, revisions vintages
  - PCA, approximate factor model, EM algorithm

### [edgar.py](edgar.py)

- Class and methods to retrieve and analyze EDGAR text data

  - SEC Edgar, 10K, 8K, MD&A, Business Descriptions
  - BeautifulSoup, requests, regular expressions

### [unstructured.py](unstructured.py)

- Implements interface for unstructured data sets

  - pymongo, S&P CapitalIQ key developments

### [readers.py](readers.py)

- Perform web requests and retrievals

  - pandas_datareader, Fama-French data library
  - Loughran McDonald financial word lists, FOMC minutes, Liu and Wu yield curve

### [structured.py](structured.py)

- Implements interface for structured data sets

  - CRSP, Compustat, IBES, delistings, distributions, shares outstanding

### [busday.py](busday.py)

- Implement custom daily and weekly trading day calendars and datetime methods

  - pandas custom business calendar


### [database.py](database.py)

- Convenience class and methods to interface with database engines

  - SQL, sqlalchemy
  - MongoDB, pymongo
  - redis

### [backtesting.py](backtesting.py)

- Class and methods to evaluate backtests, event studies and risk premiums

  - Event studies, cumulative abnormal returns
  - Risk premiums, Fama-MacBeth regressions
  - Sharpe ratio, appraisal ratio, walk-forward backtests


### [solve.py](solve.py)

- Quant, financial and econometrics helpers

  - linear algebra, stationarity, robust covariances
  - maturity, bootstrap, annuity, compounding, rate of discount and interest
  - value at risk, duration, half-life

### [learning.py](learning.py)

- Convenience methods for textual, statistical, machine and deep learning

  - relativized embeddings, word2idx, stratified train-test split, minibatch
  - sklearn, pytorch, nltk

### [pyR.py](pyR.py)

- Convenience class methods to use rpy2 package and R environment

  - rpy2

### [gdrive.py](gdrive.py)

- Convenience class methods to use google drive apis

  - google REST api's


### [display.py](display.py)

- Convenience methods for data visualization

  - matplotlib, seaborn, statsmodels, pandas


### [printing.py](printing.py)

- Convenience methods for pretty printing

  - pandas


