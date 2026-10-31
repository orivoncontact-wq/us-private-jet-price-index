# US Private Jet Price Index (monthly)

Estimated charter prices for private jets in the United States: all-in hourly rates by jet size, and one-way prices for 60 common US routes. Updated every month.

Full tables, method and the latest edition: https://flyprivateroutes.com/private-jet-price-index/

## What's in the file

`private-jet-price-index.csv`, one row per item:

| column | meaning |
|---|---|
| type | `hourly_rate` (price per flight hour) or `one_way_route` (whole aircraft, one way) |
| item | jet size for hourly rates, route name for routes |
| jet_size | Turboprop, Light, Midsize, Super-midsize or Heavy jet |
| low_usd / high_usd | price range in US dollars |
| unit | what the price covers |
| edition | month of the edition (YYYY-MM) |
| source | page with the details for that row |

Current edition: October 2026. 5 hourly rates, 60 routes.

## How the numbers are made

These are estimates, not booked prices. For each route we take the flight time for that distance and jet size and multiply it by the hourly range, with a one-hour minimum. The hourly ranges are checked every month against one-way prices that charter companies publish for reference routes. When those move, the ranges move.

Real quotes depend on the date, positioning of the aircraft, airport fees, catering and peak-day rules, so a quote can land outside the range. Use the index to know the right order of magnitude, not as a quote.

## Use and credit

Free to use, including for articles and research, under CC BY 4.0. Please credit **FlyPrivateRoutes** with a link to https://flyprivateroutes.com/private-jet-price-index/ so readers can see the method and the newest numbers.

Questions or corrections: contact@flyprivateroutes.com
