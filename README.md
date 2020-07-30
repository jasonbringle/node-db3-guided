# Node DB3 Guided Project

Guided project for **Node DB3** Module.

## Prerequisites

- [SQLite Studio](https://sqlitestudio.pl/index.rvt?act=download) installed.
- [This Query Tool Loaded in the browser](https://www.w3schools.com/Sql/tryit.asp?filename=trysql_select_top).
- a rest client like [Insomnia](https://insomnia.rest/download/) or [Postman](https://www.getpostman.com/downloads/) installed.

## Project Setup

- [ ] fork and clone this repository.
- [ ] **CD into the folder** where you cloned **your fork**.
- [ ] type `npm i` to download dependencies.
- [ ] type `npm run server` to start the API.

Please follow along as the instructor creates database access methods for a multi table schema.


<!-- THIS IS THE GUIDED PROJECT SQL QUERIES WE DID IN CLASS
--SELECT employee.id,
--       employee.FirstName,
--       employee.lastname,
--       employee.title,
--       [order].*
--  FROM employee
--       JOIN
--       [order] ON [order].employeeid = employee.id
--   ORDER BY employee.id;

--SELECT Productname,
--       Categoryname
--  FROM Product AS P
--       JOIN
--       Category AS C ON P.CategoryId = C.Id;

--select *
--from customer
--left join [order] on customer.id = [order].customerId
--Order By customer.id;

--select count(*) as [total orders] from [order]
--
--select c.categoryname as category, count(p.productname) as [Total Number]
-- from product as p
-- join category as c on p.categoryid = c.id
-- group by c.categoryname
-- order by c.categoryname
--
--SELECT c.categoryname AS category,
--       min(p.unitprice) 
--  FROM product AS p
--       JOIN
--       category AS c ON p.categoryid = c.id
-- GROUP BY c.categoryname
-- ORDER BY p.unitprice;

--
--SELECT CompanyName,
--       count([order].id) AS [Total Orders]
--  FROM customer AS c
--       JOIN
--       [order] ON c.id = [order].CustomerId
-- GROUP BY c.companyName; -->
