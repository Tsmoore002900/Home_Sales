# Home_Sales

Goal of the project is to use SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

jupyter notebook file created using google colab is called Home_Sales.ipynb.
Data from home_sales_revised.csv was read in and a temporay table called home_sales was created.

Using SparkSQL the fallowing questiong where answered
What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
![image](https://github.com/Tsmoore002900/Home_Sales/assets/119066378/2629b2bc-6698-4b10-8498-7ffd66f61dad)

What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
![image](https://github.com/Tsmoore002900/Home_Sales/assets/119066378/82be06c3-2dd2-46dd-bc3c-92c44fd79cbb)

What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
![image](https://github.com/Tsmoore002900/Home_Sales/assets/119066378/fe4040a5-6e99-44b1-9eca-3727723236af)

What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
![image](https://github.com/Tsmoore002900/Home_Sales/assets/119066378/b5dee09d-a632-4be3-99e1-f45f2f1ddca4)


Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
![image](https://github.com/Tsmoore002900/Home_Sales/assets/119066378/1f876968-ba8c-4eb6-9a41-e2a416460587)

Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
![image](https://github.com/Tsmoore002900/Home_Sales/assets/119066378/2e38db3b-db75-4d90-bad9-5c1088809124)

Final conclussion is that the cached data run time was faster then the parquet data
