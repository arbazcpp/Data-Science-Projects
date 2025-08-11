# Aviation Delays

This project utilizes data from the NTSB on aviation-related accidents from 1962 to 2023 alongside Wikipedia in order to create a more descriptive dataset as well as demonstrate some statistics regarding injuries in these crashes throughout the years.

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)

## Overview
The data from this project can be found at https://www.kaggle.com/datasets/yassereleraky/aviation-accident-ntsb, with the Wikipedia article used for data mining at https://en.wikipedia.org/wiki/List_of_accidents_and_incidents_involving_commercial_aircraft
Additionally, the NTSB's JSON data found at https://data.ntsb.gov/data.json
The Wikipedia dataset was mined using BeautifulSoup to take relevant data from the table on the page, and merge it based on date with data from the other datasets. This creates a larger dataset that shows not only the NTSB accident statistics, but a brief description of the crash from Wikipedia, allowing for further exploration on the causes of these crashes alongside injuries sustained.

## Installation
```bash
# Clone this repo
git clone https://github.com/arbazcpp/Data-Science-Projects
cd Data-Science-Projects/Documenting Aviation-Related Injuries with Data Mining
