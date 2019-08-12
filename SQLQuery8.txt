--SELECT * FROM Customers;

--SELECT Country FROM Customers;

--SELECT * FROM Customers WHERE CustomerId LIKE 'bl%';

--SELECT * FROM Orders Where OrderID < 10348;

--SELECT * FROM Customers
       -- WHERE PostalCode = '1010' 
        --OR PostalCode = '3012' 
        --OR PostalCode='12209' 
        --OR PostalCode='05023';

--SELECT * FROM Orders WHERE ShipRegion IS NOT NULL;

--SELECT * FROM Customers ORDER BY City,Country;

--INSERT INTO Customers (CustomerId,City, CompanyName)
   -- VALUES ('JKLF','Detroit','Design Systems');

   --UPDATE Orders
   --SET ShipRegion = 'EuroZone'
   --WHERE ShipCountry='France';

  -- DELETE FROM [Order Details] WHERE Quantity = 1;

   --SELECT AVG(Quantity) AS "Average Order Amount",
   -- MAX(Quantity) AS "Largest Ordered",
   -- MIN(Quantity) AS "Smallest Order"
   -- FROM [Order Details];

   --SELECT AVG(Quantity) AS "Average Order Amount",
    --MAX(Quantity) AS "Largest Ordered",
   -- MIN(Quantity) AS "Smallest Order"
    --FROM [Order Details]
    --GROUP BY OrderId;


	--SELECT CustomerID FROM Orders
	 --WHERE OrderID = '10290';


	--SELECT * FROM CUSTOMERS LEFT JOIN Orders ON Customers.CustomerID = Orders.CustomerID;
	--SELECT * FROM CUSTOMERS RIGHT JOIN Orders ON Customers.CustomerID = Orders.CustomerID;
	--SELECT * FROM CUSTOMERS INNER JOIN Orders ON Customers.CustomerID = Orders.CustomerID;

	 --SELECT FirstName FROM Employees 
    --WHERE ReportsTo IS NULL;

	--SELECT FirstName FROM  Employees 
    --WHERE ReportsTo='2'; --Needs ID number from Andrew