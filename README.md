# bloomberg-datasets

## An independent repository containing my Thesis data for the completion of MSc Computational Finance @ UCL

### Description

While I often find myself changing code thorughout a project, I rarely do so with datasets. The intended purpose of isolating the data in a different repository is to avoid permanently modifying it, or such that any modifications are tractable. It is also a warranty to ensure subsequent work may be replicated, and, perhaps less importantly, to decluter a bit the main repository. 

### Structure

This intended submodule is hence structured as follows:
> #### Raw
>> Datasets as downloaded from source (in this case bbg), save some modifications to file names to make our lifes a bit easier.

> #### Clean 
>> Preprocessed data intended to be used in the task at hand, in this case, calibration of stochastic local volatility models.

Wihtin either of the subfolders, you may find data pertaining to over-the-counter (OTC) foreign-exchange (FX) quotations of implied volatilities, currency yield curves (EUR €, $USD), and spot-rate for the notional pair EUR-USD for the year 2023.