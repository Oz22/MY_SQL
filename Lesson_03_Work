create database Customer;

Use Customer;

create TABLE Customer (
   Customer_ID int,
   Cust_Name NVARCHAR(30),
   City NVARCHAR(30),
   Grade int,
   Saleman_ID int
   );
 
INSERT into Customer (customer_id,cust_name,City,grade,saleman_id)
Values (3002, 'Nick Rimando','New York', 100, 5001),
	   (3007, 'Brad Davis','New York', 200, 5001),
	   (3005, 'Graham Zusi','California', 200, 5002),
	   (3008, 'Julian Green','London', 300, 5002),
	   (3004, 'Fabian Johnson','Paris', 300, 5006),
	   (3009, 'Geoff Cameron','Berlin', 100, 5003),
       (3003, 'Jozy Altidor','Moscow', 200, 5007),
       (3001, 'Brad Guzan','London', 000, 5005);
	
select * from Customer
where city in ('New York') and grade >100;

select * from Customer
where city in ('New York') or grade >100;

select * from Customer
where city in ('New York') or not grade >100;

select * from Customer
where not city in ('New York') and not grade >100;
