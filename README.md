# Analysis-with-HIVE

#Tasks to do  with Apache Hive


Use the cars dataset(wget https://www.dropbox.com/s/ffkwf3ixq1mjk7q/cars.csv), answer the following questions in Apache Hive.
1. Write a Hive query to create a table called used_cars from data. Use a schema that is
appropriate for the column headings
2. Look at the date column of the table used_cars. Why does the date column have all
NULL values?
3. Bonus: Create a table such that the date column is read correctly based on the format
in the dataset.
4. Write Hive queries to see how many missing values you have in each attribute? Based
on the results, document how many missing values in each column we have. Especially,
mention those columns with more than 50% missing values.
5. Group the price column and count the number of unique prices. Do you notice if there
is a single price that is repeating across the ads?
6. Write a Hive query to create a new table called clean_used_cars from used_cars with
the following conditions:
o Drop the columns with more than 50% missing values
o The manufacture year between 2000 and 2017 including 2000 and 2017
o Both maker and model exist in the row
o The price range is from 3000 to 2000,000 (3000 ≤ price ≤ 2000,000)
o Remove any price you singled out in Step 3 (ie a price that repeats too frequently for
a random set of ads).
7. Write a Hive query to find how many records remained clean_used_cars
8. Write a Hive query to find the make and model for the cars with the top 10 highest
average price
9. Write a Hive query to find the make and model for the cars with the top 10 lowest
average price
10. Write a Hive query to recommend top five make and model for Economic segment
customers (Top five manufacturers in the 3000 to 20,000 price range;3000≤price<20,000) -
based on the top average price
11. Write a Hive query to recommend top five make and model for Intermediate segment
customers (Top five manufacturers in the 20,000 to 300,000 price range;
3000≤price<20,000) - based on the top average price
12. Write a Hive query to recommend the top five make and model for the Luxury segment
customers (Top five manufacturers in the 300,000 to 2000,000 price range;
300,000≤price<2000,000) - based on the top average price
