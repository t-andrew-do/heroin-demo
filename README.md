# An Exploration of Heroin Overdose and its Spread Across America [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/t-andrew-do/heroin-eda-demo/main?labpath=eda.ipynb)

This repository contains preliminary work on modeling spatialtemporal trends of opioid-related deaths in America.

## Main Github

https://github.com/t-andrew-do/heroin-overdose (Private)

## Main Question
What effect do economic phenomena have in driving opioid outcomes, controlling for spatial factors/relationships?

### Problem Question Ideas:

* Examining how changes in concentrations of different industries at the county (census tract?, MSA?) level relates to adverse outcomes associated with opioid use (overdoses/deaths), controlling for other economic/prescription/spatial factors.
* Control for the effects of opiate prescription rates (and other standard control variables) on the growth of the opioid epidemic and overdoses
* How does the explanatory power of the above variables compare to the explanatory power of spatial spread? 
* Has the declaration of a National Emergency had any visible impact (on say diffusion rate? Within demographic/geographic subgroups)?  How do we account for this in our models?

## Data Sources

### VSRR Provisional Drug Overdose Death Counts

* Description: https://data.cdc.gov/NCHS/VSRR-Provisional-Drug-Overdose-Death-Counts/xkb8-kh2a
* API Endpoint: https://data.cdc.gov/resource/xkb8-kh2a.json

### NVSS Mortality Multiple Cause Files

* Data: https://www.cdc.gov/nchs/data_access/vitalstatsonline.htm#Mortality_Multiple
* Data Documentation: https://www.cdc.gov/nchs/nvss/mortality_public_use_data.htm

### NCHS Drug Poisoning Mortality by County

* https://data.cdc.gov/NCHS/NCHS-Drug-Poisoning-Mortality-by-County-United-Sta/pbkm-d27e

### CDC Opiod Prescription Rate: IQVIA Xponent Data

* Data: Must be scraped from CDC web pages. IQVIA Xponent Data not publicly available
* Description: https://www.cdc.gov/drugoverdose/rxrate-maps/index.html
