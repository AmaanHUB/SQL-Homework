# SQL-Homework

**Q1: How many orders in NWDB (Northwind Database)?**

Query:
```
SELECT COUNT(*) FROM Orders;
```
Answer: 830


**Q2: How many orders have the ShipCity is Rio de Janeiro?**

Query:
```
SELECT COUNT(*) FROM Orders WHERE ShipCity = 'Rio de Janeiro';
```
Answer: 34

**Q3: Select all orders that the ShipCity is Rio de Janeiro or Reims?**

Query:
```
SELECT COUNT(*) FROM Orders WHERE ShipCity = 'Rio de Janeiro' OR ShipCity = 'Reims';
```

Answer: 39


**Q4: Select all the entries where the company name that has a z or Z in the table of Customers?**

Query:
```
SELECT COUNT(*) FROM Customers WHERE CompanyName LIKE '%[Zz]%';
```

Answer: 6 (answer without count below)

* Centro comercial Moctezuma
* Lazy K Kountry Store
* Magazzini Alimentari Riuniti
* Queen Cozinha
* Toms Spezialitäten
* Wolski  Zajazd

**Q5: Find all records without fax information, want name, contact numbers and what cities they are in**


