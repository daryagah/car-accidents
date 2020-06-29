# Car Accidents Data Analysis and Visualization

## Dataset Used

US Traffic Fatality Records (2016), free access with BigQuery

Described here: https://www.kaggle.com/usdot/nhtsa-traffic-fatalities

Manual: https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812827

## Project Information

Data was loaded by joining some of the most interesting columns of “accidents”, “people”, and “vehicle” tables using Python’s BigQuery helper. Only drivers were selected among all people involved in the accidents. Each row of the resulting “flat” dataset represents one driver/vehicle per accident. Dataset came with unique IDs per accident as “consecutive number”, but there was no ID per vehicle to properly join the tables. Hence, so a composite key for vehicles was created. The data was cleaned, decoded according to the manual, and exported to a CSV file.

The Data contains a wide range of useful information across all Accident types, including:
- Vehicle Make & Model
- Location and Time of the Accident
- Roadway Conditions
- Driver Information (DWI, Non-Identifying License Info)

Dataset CSV File was used as the Data Source for use in Microsoft Power BI.

## Power BI Dashboard

Link: https://app.powerbi.com/reportEmbed?reportId=69238692-8b30-4b31-8502-e74556fbc4ba&autoAuth=true&ctid=741bf7de-e2e5-46df-8d67-82607df9deaa&config=eyJjbHVzdGVyVXJsIjoiaHR0cHM6Ly93YWJpLXVzLWVhc3QyLXJlZGlyZWN0LmFuYWx5c2lzLndpbmRvd3MubmV0LyJ9
