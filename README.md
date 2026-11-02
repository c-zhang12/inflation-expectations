# Inflation Expectations vs. Reality

## Question
Do Americans' inflation expectations match actual inflation, when did the most difference exist, and recent trends of the differences?

## Why it matters
Expectations affect the budgeting of individual's life, including groceries, gas, and other daily expenditures.  It would affect wage demands and savings plans.  If the gap between the expectation and the actual inflation is significant, the economy will be affected

## Data
- University of Michigan Surveys of Consumers (via FRED): inflation expectations and consumer sentiment
- Consumer Price Index (via FRED / Bureau of Labor Statistics): actual inflation

## Status Obervation

Expected inflation:
- There is a peak at around 1980, from 1978-1983 the expectation for inflation is quite high compared to the expected inflation during other years.
- there is a low at around 2002, where the expected is about 1%
- the expected inflation is pretty consistent besides a few peaks at around 1990 and 2008.
- after 2020 the expected inflation seems to be increasing with 2 spikes at 2022 and 2025
Actual Inflation:
- there is a major peak of inflation at around 1979, minor peaks at 1990, 2022
- there seems to be a negative trend from 1990 to 1999
- there is a major dip at around 2009
- the inflation was quite stable around 1 until after 2019 where is spiked up to about 9% but later dropped to around 3%
Both:
- the expected value for inflation tends to understate the change in actual inflation, causing the expected trendline to be a lot more smoother than the actual.
- in general, the overall trends for both expected and actual are the same
- the two lines are apart the most from periods around 1979-1983 and 2008-2017
- around 2021-2023, post covid-19, the inflation was significantly higher than the expectation while from 2023-2025 the inflation is a lot lower than expected
- the expected inflation and actual has a strong positive relation, where most of the data are clustered below 5.0 actual inflation
- when actual value >10, most of the expected inflation seems to be higher than the LSRL
 

## Method
Both of the data series with the FRED API, converted CPI to a year-over-year percent change, merged them by month, and stored the result in a SQLite database. Pandas was used to analyze the data and matplotlib was used for the charts and visual

## Findings


## Limitations


## How to run
1. Get a free FRED API key.
2. Install: pip install pandas matplotlib fredapi
3. Run the notebook.
