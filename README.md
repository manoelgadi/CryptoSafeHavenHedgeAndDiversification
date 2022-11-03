# Repository of the analsys for the paper "Analyzing safe haven, hedging and diversifier characteristics of heterogeneous cryptocurrencies against G7 and BRICS market indexes"

Cryptocurrency markets have experienced a large growth in recent years, together with an increase in the number and diversity of assets being traded. 
Previous work has addressed the economic properties of Bitcoin with regards to their hedging or diversification properties. 
However, the surge of many alternatives, applications, and decentralized finance services on a variety of blockchain networks requires a re-examination of 
those properties including indexes from outside the big economies and the inclusion of a variety of cryptocurrencies and a look into the period 
Pre-COVID and During-COVID.

This is the repository supporting the Paper: Analyzing safe haven, hedging and diversifier characteristics of heterogeneous cryptocurrencies against G7 and BRICS market indexes
by Manoel Fernando Alonso Gadi and Miguel Angel Sicilia. 

# Results:

The 3 results table can be found at:
* ./results/WholePeriod_BaurAndMcDermottModel_SummaryResults_20180101_20220930.xlsx containing the results for the whole period between 
the 1st of January 2018 and th 30th of September 2022.
* ./results/PreCovid_BaurAndMcDermottModel_SummaryResults_20180101_20200229.xlsx containing the results for the pre-Covid period which is between 
the 1st of January 2018 and the 29th of February 2022.
* ./results/DuringCovid_BaurAndMcDermottModel_SummaryResults_20220301_20220930.xlsx containing the results for the period after the Covid crisis started, period between 
the 1st of March 2020 and the 30th of September 2022.

# How to reproduce the creation of each of this files:

* Simply visit the Python Jupyter Notebook 2022_inPython_SafeHavenHedgeAndDiversification_REGRESSION_V7.ipynb change the days at "Reading data from Yahoo Finance!" 
to the desired period (currently working only for period between 01/Jan/2018 and 30/Sept/2022 due to manual download of both FTSE indexes for the UK and Italy) and __run all__:

Change the following lines:

* start = datetime.datetime(2018, 1, 1)
* end = datetime.datetime(2022, 9, 30)
