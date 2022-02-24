---
layout: default
---

My name is Merlin Heidemanns and I am currently a Ph.D candidate in Political Science at Columbia University. My research focuses on applied Bayesian modeling especially in the context of election forecasting, public opinion, and survey research. I am specifically interested in applications in which available data is limited and which necessitate creative solutions that combines auxiliary knowledge about the data with iterative model development and testing to get the most out of the available data. I mainly work in Stan through R.

When I am not looking at parameter output I enjoy visiting art galleries -- trying to see as many Feiningers in person as possible -- as well as backpacking.

This page contains will eventually contain a series of links to related case studies.

### Election Forecasting

**Forecasting US Presidential elections

* [This]() is an extension from earlier work with G. Elliott Morris and Andrew Gelman. I provide a sensible approach to prior choices by estimating the distributions simultaneously from pre-election polls from previous elections. I further model both unemployment and approval rather than treating them directly as data and estimate the covariance matrix of the random walk with MRP from survey data to directly access how vote intentions change over time.

**Forecasting Presidential Elections in France**

* [This](https://github.com/MerlinHeidemanns/election_forecast_france) project builds on earlier work on U.S. elections. It extends that work by combining three separate forecasts based on polling, fundamentals, and historical trends. It improves the model's ability to estimate trends in polling numbers through Gaussian processes learning from dynamics during previous election cycles. It further considers a case in which the number of candidates is larger than one and methods to improve sampling speed.

**Poll Aggregation during French Primaries**

* [Here](https://github.com/MerlinHeidemanns/french_primaries), I consider the problem when we want to aggregate surveys that cover subsets of the potential answer options. During French primaries, pollsters will test hypotheses, i.e. whom would voters vote for if candidate X were to run. This model uses transition probabilities, i.e. how voters change between candidates when given different sets to choose from to allow us to compare two candidates whom no survey ever include at the same time. 

### Bayesian Survey Research Methods




