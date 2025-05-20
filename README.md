# 2025-Housing-Lottery-Applicants-

In Greenpoint, Brooklyn, "affordable" housing units are priced with income requirements far exceeding the earnings of many longtime residents, highlighting a deep disconnect between policy standards and local realities.


## Byline and Credits

**By:** Zhenjia Zhang

**Date** 05/19/25

----


## Project summary


This story reveals how so-called “affordable” housing in Greenpoint, Brooklyn, remains out of reach for many longtime residents. New lottery units require incomes of $65K–$125K, while some locals earn closer to $50K. The piece shows how Area Median Income (AMI) calculations inflate affordability standards, creating a mismatch between housing policy and neighborhood realities. Through data analysis and resident voices, the story highlights the growing displacement risk in a rapidly gentrifying community.


## Data Sources

1. **Data from NYC Housing Connect:** https://housingconnect.nyc.gov/PublicWeb/search-lotteries?householdType=2&householdSize=1&neighborhoods=66&update=true

3. **Data from Streeteasy:** https://streeteasy.com/blog/data-dashboard/[object%20Object]?agg=Total&metric=Inventory&type=Sales&bedrooms=Any%20Bedrooms&property=Any%20Property%20Type&minDate=2010-01-01&maxDate=2025-04-01&area=Greenpoint

4. **Data from Keep Tracking Online, The Status of New York City Children:** https://data.cccnewyork.org/data/map/66/median-incomes#66/39/3/107/131/301/a

## Methodology

1. **Import data**
     Greenpoint 2025 Lottery Units
     Rising rents in Greenpoint
     Household income in NYC

2. **Cleaning the data**
     Drop rows without rent values
     Extract min income from the "Income Range" column

3. **Calculation**
     Average minimum income required
     The rent Burden for each unit for the house income

## How to Reproduce This Analysis

1. Clone this repository
   git clone [https://github.com/zhenjiazhang/2025-Housing-Lottery-Applicants-](https://github.com/zhenjiazhang/2025-Housing-Lottery-Applicants-.git)


   
