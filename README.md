# Bay Area Apartment Pricing - Exploratory Analysis

## Table of Contents
- [Background](#Background)
  - [Datacleaning](#datacleaning)
- [Findings](#Findings)
- [Usage](#Usage)

<a name="Background"/>

## Background
In this project I collected data by webscraping Craigslist using Python & BeautifulSoup package. The data was collected on March 2020 and contains information for postings from 3 months prior. The goal of this project was to analyze the apartment postings to find which locations in the the Bay Area were the more beneficial to live in based on multiple variables. I'm originally from the Peninsula area so I wanted to know more about the other areas.

<a name="datacleaning"/>

### Data Cleaning
-----------------------
Right after the data was scraped it was organized and simple data cleaning was performed such as stripping unneeded characters in each column and making each column the correct datatype. Besides that after the dataframe was ready there was some more data cleaning that had to be performed to be able to explore the data accurately such as:
1. Removing identical post since craiglist usually has spammed postings.
2. Identifying outliers that would skew the data horrendously. For example there was apartments with the cost of $68 or up to $45000 for a 5bd home. This doesn't represent our data well so I just decided to omit these posts.

<a name="Findings"/>

## Findings
<img src ="https://github.com/EdgarFonseca94/CraigslistAptPricing/blob/32d2db53991b7ed341b4cb0f63f8aa2b035ea8da/IMG_Folder/download.png" width="300" height = "300">

<a name="Usage"/>

## Usage
