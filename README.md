# MongoDB_CRUD
MongoDB_CRUD operations
Objective:
Having all this information in place we need to create a Database called
ProductOrder and various collections in it. The collections needed and
attributes which need to be in every collection are given by the Organization.
All you have to do is create collections with data in it and write some queries so
that the organization can retrieve required information.
Files Provided:
The resources that have been shared with you as part of the zipped JSON docs
folder, there are 4 main files.
Product_info.json, Inventory_info.json, User_info.json, and Order_info.json
The JSON files that contain the information to be inserted into the database.

Questions: 
1. Open VS Code and connect to MONGODB
2. Create a database "ProductOrder" and create collections
"Product","Inventory","User", and "Order" in it. 
3. Open MongoDBCompass and navigate to the "ProductOrder" database. 
i) Add "Product_info.json" file into the "Product" collection.
ii) Add "Inventory_info.json" file into "Inventory" collection.
iii) Add "User_info.json" file into the "User" collection.
iv) Add "Order_info.json" file into "Order" collection.
4. Display the first 5 rows of product, inventory, user, and order collection. 
5. Display the Unique Brand and Model names from the Product collection. 
6. Find the maximum and minimum price of the given products. 
7. Display the quantity and last_updated date and time for sku "SNY-11001". 
8. List down the count of the total number of users whose role is identified as
'Supplier' from User collection 
9. Display 'sku', 'code', 'price', 'brand' and 'warranty' information for the model
'Bravia-X' 
10. Find all the information of Sony products which have an Price greater
than 1 lakh 
11. Find the total no of products by each Brand and sort them in descending
order. 
12. Find the total no of users by each role, sort them is descending order and
save the results in the temporary collection 
