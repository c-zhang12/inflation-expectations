# Inflation Expectations vs. Reality

## Question
Do Americans' inflation expectations match actual inflation, when did the most difference exist, and recent trends of the differences?

## Why it matters
Expectations affect the budgeting of individual's life, including groceries, gas, and other daily expenditures.  It would affect wage demands and savings plans.  If the gap between the expectation and the actual inflation is significant, the economy will be affected

## Data
- University of Michigan Surveys of Consumers (via FRED): inflation expectations and consumer sentiment
- Consumer Price Index (via FRED / Bureau of Labor Statistics): actual inflation

## Method
Both of the data series with the FRED API, converted CPI to a year-over-year percent change, merged them by month, and stored the result in a SQLite database. Pandas was used to analyze the data and matplotlib was used for the charts and visual

## Findings


## Limitations


## How to run
1. Get a free FRED API key.
2. Install: pip install pandas matplotlib fredapi
3. Run the notebook.
