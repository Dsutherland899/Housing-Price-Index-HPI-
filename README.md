# Housing Price Index (HPI) Investigation

**Project Background**

This data comes from the UK Government's publishing of the aggregated data behind the UK House Price Index published on the 18th of Feburary 2026. 

The dataset contains many differnet items, which can be grouped into the following categories: 

**Core Identifiers**
* Date: The month and year the data refers to (usually the 1st of the month)
* RegionName: The geographical area (e.g., "United Kingdom", "London", "Aberdeenshire").
* AreaCode: The official ONS (Office for National Statistics) code for that specific region.

**General Market Metrics**
* AveragePrice: The average price of all residential properties sold in that area during that month.
* Index: A number representing the relative price change compared to a "base period" (usually January 2015 = 100).
* IndexSA / AveragePriceSA: "SA" stands for Seasonally Adjusted. This removes predictable seasonal patterns (like the market slowing down in December) to show the underlying trend.
* 1m%Change: The percentage change in the average price compared to the previous month.
* 12m%Change: The percentage change in the average price compared to the same month last year (annual inflation).
* SalesVolume: The total number of completed property sales in that month.

**Property Type Columns**
 
 The dataset tracks four main building types. For Detached, SemiDetached, Terraced, and Flat, you have:

* {Type}Price: The average price for that specific house type.
* {Type}Index: The growth index for that specific type.
* {Type}1m%Change: The monthly price shift for that type.
* {Type}12m%Change: The annual price shift for that type.

**Funding Type (Cash vs. Mortgage)**

* CashPrice / Index / 1m% / 12m%: Data specifically for properties bought without a loan.
* CashSalesVolume: How many cash buyers are in that market.
* MortgagePrice / Index / 1m% / 12m%: Data for properties bought with a mortgage.
* MortgageSalesVolume: How many mortgage-backed sales happened.

**Buyer Type (FTB vs. FOO)**

* FTBPrice / Index / 1m% / 12m%: Data for First-Time Buyers.
* FOOPrice / Index / 1m% / 12m%: Data for Former Owner Occupiers. 

**Property Age (New vs. Old)**
* NewPrice / Index / 1m% / 12m%: Prices and growth for New Build homes.
* NewSalesVolume: How many new builds are being sold (useful for tracking construction booms).
* OldPrice / Index / 1m% / 12m%: Prices and growth for Existing (second-hand) homes.
* OldSalesVolume: How many resales are happening.
  
