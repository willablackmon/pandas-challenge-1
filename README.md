







## Part 1: Explore the Data (30 points)
import the data and use Pandas to learn more about the dataset

+ View the column names. (4 points)

+ Use the describe function to gather some basic statistics. (4 points)
  + explore data, create more cells as needed
  
+ Correctly identify the __(3) categories__ (category?) with the most entries. (4 points)

+ For the category with the most entries, correctly identify the __subcategory with the most entries__. (5 points)

+ Correctly identify the __5 clients with the most entries__ in the data. (5 points)
  + Store the __client ids__ of those top 5 clients in a list. (4 points)

+ Display the __total units__ (the qty column) that the __client with the most entries__ ordered. (4 points)

## Part 2: Transform the Data (30 points)
transform the data for better and easier analysis

+ Create a column that calculates the __subtotal__ for each line using the unit_price and the qty. (6 points)

+ Create a column for __shipping price__. Assume a shipping price of $7 per pound for orders over 50 pounds and $10 per pound for items 50 pounds or under. (6 points)

+ Create a column for the __total price__ using the subtotal and the __shipping price__ along with a __sales tax of 9.25%__. (6 points)

+ Create a column for the __cost of each line__ using unit cost, qty, and shipping price (assume the shipping cost is exactly what is charged to the client). (6 points)

+ Create a column for the __profit__ of each line using line cost and line price. (6 points)

## Part 3: Confirm Your Work (15 points)
verify the results; you have email receipts showing the total prices for 3 orders.

+ Confirm that Order ID 2742071 had a total price of $152,811.89. (5 points)

+ Confirm that Order ID 2173913 had a total price of $162,388.71. (5 points)

+ Confirm that Order ID 6128929 had a total price of $923,441.25. (5 points)
  
Confirm that your calculations match the receipts. Remember, each order has multiple lines.

## Part 4: Summarize and Analyze (25 points)
+ Calculate the __total revenue__ from each of the __top 5 clients__ in Part 1. (5 points)

+ Create a __summary DataFrame__ showing the totals for the top 5 clients with the following information:
  + total units purchased
  + total shipping price
  + total revenue, and 
  + total profit. (5 points)

+ Create a __function__ to change the currency to __millions of dollars__.
  + Format the data and rename the columns to names suitable for presentation. 
  + Then, __sort the DataFrame in descending order__ by total profits. (5 points)

+ Write a brief 2-3 sentence summary of your findings. (10 points)





## Developer Information:
repository for this project called pandas-challenge-1

DataFrame documentation:
https://pandas.pydata.org/docs/reference/frame.html
