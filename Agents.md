# Climate Data Aggregator Scraper

The **Climate Data Aggregator Scraper** collects historical climate data from regional weather stations to facilitate micro-climate analyses.

## Key Features:
- Scrapes climate data such as temperature, precipitation, humidity, and wind speed.
- Filters data by a specified date range.
- Customizable limit on the number of records per weather station.

## Inputs:
1. `stationUrls`: List of weather station URLs to scrape.
2. `dateRange`: Start and end dates for historical climate data.
3. `maxRecordsPerStation`: Limits the records scraped per weather station.

## Outputs:
- `stationName`: Name of the weather station.
- `date`: Date of the record.
- `temperature`: Measured temperature in °C.
- `precipitation`: Precipitation in mm.
- `humidity`: Humidity in %.
- `windSpeed`: Wind speed in km/h.
- `url`: URL of the source weather station.

## Use Cases:
1. Perform **micro-climate analysis** for agriculture, forestry, or research purposes.
2. Analyze **regional weather trends** over a specified period.
3. Develop **local climate models** based on historical data.

---
