# Home_Sales
In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.
## Analysis
**Query 1:** Average price for a four-bedroom house sold for each year
<img width="624" alt="Screenshot 2023-05-24 at 7 30 41 PM" src="https://github.com/Jan0405/Home_Sales/assets/120051602/d501e66b-869c-4889-b5df-8e8b2b3ce908">

**Query 2:** Average price of a home for each year the home was built that have 3 bedrooms and 3 bathrooms rounded to two decimal places
<img width="594" alt="Screenshot 2023-05-24 at 7 38 50 PM" src="https://github.com/Jan0405/Home_Sales/assets/120051602/7e4127a8-00ee-494d-a3ff-3313bf943c59">

**Query 3:** average price of a home for each year built that have 3 bedrooms, 3 bathrooms, with two floors and are greater than or equal to 2,000 square feet rounded to two decimal places

<img width="649" alt="Screenshot 2023-05-24 at 7 40 14 PM" src="https://github.com/Jan0405/Home_Sales/assets/120051602/a363aa44-98ec-4b5c-9853-cb66b9e3e4d4">

**Query 4:** The "view" rating for the average price of a home, rounded to two decimal places, where the homes are greater than or equal to $350,000

<img width="515" alt="Screenshot 2023-05-24 at 7 40 52 PM" src="https://github.com/Jan0405/Home_Sales/assets/120051602/05a283bb-e0c2-4f03-9e13-b747cbf36953">

## Compare Run Times on Query 4.
1. Uncache Runtime: 0.8288760185241699 seconds
2. Cached Runtime: 0.6935641765594482 seconds
3. Runtime with the parquet DataFrame: 0.8239700794219971 seconds
