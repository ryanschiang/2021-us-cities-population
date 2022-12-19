
# 28,000 Largest US Cities by Population (2021)

## Overview

This is a JSON file containing `28,883` US cities and populations, sorted by population.

In total, this list covers 81% of the U.S. population (~269.9 million total).

File size is 1.7 mb and contains ~45.5k lines.
## Usage

Download via command line:

`curl -o sorted_cities.json https://raw.githubusercontent.com/ryanschiang/2021-us-cities-population/main/sorted_cities.json`

## Source

This data comes from the [2020-21 US Census Population Estimates Program](https://www.census.gov/data/tables/time-series/demo/popest/2020s-total-cities-and-towns.html).

## Sample Data

```
{
    "cities": [
        { "city": "New York", "state": "NY", "population": 8467513 },
        { "city": "Los Angeles", "state": "CA", "population": 3849297 },
        { "city": "Chicago", "state": "IL", "population": 2696555 },
        { "city": "Houston", "state": "TX", "population": 2288250 },
        { "city": "Phoenix", "state": "AZ", "population": 1624569 },
        { "city": "Philadelphia", "state": "PA", "population": 1581531 },
        { "city": "San Antonio", "state": "TX", "population": 1451853 },
        { "city": "San Diego", "state": "CA", "population": 1381611 },
        ...
    ]
}
```



