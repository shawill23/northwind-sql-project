## Query 1: How many orders has each customer placed? Show customer name and total number of orders, ordered from highest to lowest. Limit list to 10.
Answer/Output:
# ContactName, total_orders
'Jose Pavarotti', '31'
'Roland Mendel', '30'
'Horst Kloss', '28'
'Maria Larsson', '19'
'Patricia McKenna', '19'
'Christina Berglund', '18'
'Paula Wilson', '18'
'Carlos Hernández', '18'
'Laurence Lebihan', '17'
'Renate Messner', '15'


## Query 2: Show the product name and total sales. 
Answer/Output:
# ProductName, total_sales
'Chai', '180'
'Chang', '456'
'Aniseed Syrup', '120'
'Chef Anton\'s Cajun Seasoning', '1056'
'Chef Anton\'s Gumbo Mix', '768.6'

## Query 3: Find the average unit price of all products. Limit list to 10. 
Answer/Output: 
# ProductName, product_price
'Alice Mutton', '780'
'Aniseed Syrup', '120'
'Boston Crab Meat', '441.59999999999997'
'Camembert Pierrot', '510'
'Carnarvon Tigers', '1000'
'Chai', '180'
'Chang', '456'
'Chartreuse verte', '13500'
'Chef Anton\'s Cajun Seasoning', '1056'
'Chef Anton\'s Gumbo Mix', '768.6'



## Query 4: Create a query that shows each product along with a label that classifies it as low stock if the units in stock are under 20, and in stock otherwise. Limit list to 8.
Answer/Output:
# ProductName, Product_In_Stock
'Chai', 'In Stock'
'Chang', 'Low Stock'
'Aniseed Syrup', 'Low Stock'
'Chef Anton\'s Cajun Seasoning', 'In Stock'
'Chef Anton\'s Gumbo Mix', 'Low Stock'
'Grandma\'s Boysenberry Spread', 'In Stock'
'Uncle Bob\'s Organic Dried Pears', 'Low Stock'
'Northwoods Cranberry Sauce', 'Low Stock'



## Query 5: Show each employee alongside the EmployeeID (and/or) Title of the person they report to.
Answer/Output: 
# EmployeeID, FirstName, LastName, Title, ReportsTo
'1', 'Nancy', 'Davolio', 'Sales Representative', '2'
'3', 'Janet', 'Leverling', 'Sales Representative', '2'
'4', 'Margaret', 'Peacock', 'Sales Representative', '2'
'5', 'Steven', 'Buchanan', 'Sales Manager', '2'
'6', 'Michael', 'Suyama', 'Sales Representative', '5'
'7', 'Robert', 'King', 'Sales Representative', '5'
'8', 'Laura', 'Callahan', 'Inside Sales Coordinator', '2'
'9', 'Anne', 'Dodsworth', 'Sales Representative', '5'

Project Note:
The Northwind schema only contains ReportsTo as an employee ID, and Title for role descriptions. It does not include manager names directly. A self-join could normally return the managers name, but in this dataset the output doesnt display correctly. Instead, this query lists employees with the ID's or titles they report to. This shows the reporting structure based on the available schema. 


## Query 6: Show the customers who have placed more than 5 orders.
Answer/Output: 
# ContactName, orders_placed
'Maria Anders', '6'
'Antonio Moreno', '7'
'Thomas Hardy', '13'
'Christina Berglund', '18'
'Hanna Moos', '7'
'Frédérique Citeaux', '11'
'Laurence Lebihan', '17'
'Elizabeth Lincoln', '14'

