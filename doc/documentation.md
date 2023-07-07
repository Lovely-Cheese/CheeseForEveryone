



---
# MySQL

Connect to MySQL

> To interact with the MySQL database run the following commands:


`mysql --host=sql-srv-001 --user=sqladmin --password=Omega9Alfa3 mydb`

`mysql -h sql-srv-001  -u sqladmin -pOmega9Alfa3 mydb`


SQL config:

> `mysql --port=13306 --host=10.0.16.99`
> `mysql --port=13306 --protocol=TCP`

Run the following query to get user information stored in the MYSQL DB 


`SELECT USER_NAME(1);`

> Output:

Dany Jhonson | 19/03/1978 | Las Vegas Boulevard s.v. Bringstone 2349 | +1 (011)-472-9066 | 5425233430109903	04/2026



`SELECT CHEESE_INFO(1);`

> Output:

"Order Number" -  "PO123456789"

"Supplier" -  "ABC Company"

"Item Description" -  "Widget A"

"Quantity" -  "100"

"Unit Price" -  "$10.99"

"Total Amount" -  "$1,099.00"




`SELECT SHIPPING_ADDRESS(1);`

> Output:


 "Street" : "123 Main Street"
 "City" : "New York"
 "Postal Code" : "10001"