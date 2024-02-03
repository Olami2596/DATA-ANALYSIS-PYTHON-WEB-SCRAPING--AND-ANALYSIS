# Car Sales Analysis

## Overview
This project analyzes car sales data obtained from [The AA](https://www.theaa.com/cars/) website using Python libraries such as Beautiful Soup and Requests. The data was extracted, cleaned, and analyzed to derive insights into various aspects of car sales, including total sales based on year, comparison of sales by transmission type, popular car sales by body type, and top cars based on the number of reviews.

## Data Extraction
- The data was extracted from The AA website using Beautiful Soup and Requests libraries.
- Information such as vehicle ID, title, price, location, mileage, year, fuel type, transmission, body type, color, doors, engine size, CO2 emission, number of reviews, and rating was collected.

## Data Wrangling
- The extracted data was cleaned and formatted for analysis.
- Comma's were removed from price and mileage columns and converted to integer format.
- SI units were removed from engine size and CO2 emission columns for conversion to integer format.
- Columns were converted to their respective data types.
- Null values and unnecessary ID column were dropped from the dataset.

## Analysis Questions
1. **Total Car Sales Based on Year:**
   - Calculated the total car sales for each year.
   
2. **Comparison of Car Sales by Transmission:**
   - Compared car sales between manual and automatic transmission.

3. **Popular Car Sales Based on Body Type:**
   - Identified the most popular car sales based on body type.

4. **Top 10 Cars with Highest Number of Reviews:**
   - Listed the top 10 cars with the highest number of reviews.

## Results
1. Total car sales were highest in certain years, indicating trends in consumer preferences. 

| year |   price  |
|------|----------|
| 2011 |  960000  |
| 2016 | 1773000  |
| 2018 | 4116000  |
| 2019 | 6512400  |
| 2020 | 4098000  |
| 2021 | 2571000  |


2. Cars with manual transmission generated more sales than automatic transmission cars.6842400

| transmission |   price   |
|--------------|-----------|
|  Manual      | 13188000  |
|  Automatic   | 6842400   |

3. Hatchback was the most popular body type, followed by van and saloon.

|  body type  |   price   |
|-------------|-----------|
|  Hatchback  | 15108000  |
|    Estate   |  3962400  |
|    Saloon   |   960000  |

4. The top cars with the highest number of reviews were listed.

|       title        | review_count |
|--------------------|--------------|
|   Ford Fiesta      |     89520    |
|   Ford Focus       |     37200    |
|   Vauxhall Astra   |     22080    |
|   Volkswagen Golf  |      9420    |
|   Audi A3          |      9120    |
|   Nissan Qashqai   |      6000    |
|   SEAT Ibiza       |      2820    |
|   Kia Sportage     |      2700    |
|   Jaguar XJ        |      2340    |
|   BMW 1 Series     |      1860    |

## Requirements
- Python 3.x
- Beautiful Soup
- Requests
- Pandas
- NumPy
