# New-car-dataset-Analysis
## Overview:
**This is a sales report for car Sales products**

---

## Contents
 [Project Overview](#Project-Overview) |+[Data Source](#Data-Source)|+ [Data Source](#Data-Source) |+ [Tables Used](#Tool-Used) |+ [Table-Outlay](#Table-Outlay) |+ [Query Languages)](#Query-Languages)|+ [Visualization](#Visualization) | [Summary](#Summary)

---

## Project Overview:

>>This project analyzes a New Car Sales Dataset using SQL, Excel, and Power BI to uncover insights about car brands, pricing, sales performance, and customer behavior. The aim is to demonstrate data analysis, database design, and visualization skills suitable for real-world business decision-making..

## Data Source:
www.kaggle.com/dataset

Tools Used:
 ## Tools Used:
+ Pivot Table/Charts
+ PowerBi
+ SQL

## Table Outlay:
  First four Columns

|Car_id|	Date	|Customer Name|	Gender|	Annual Income	|Dealer_Name	|Company	Model|	Engine	|Transmission	|Color|	Price ($)	|Dealer_No |	Body Style	|Phone	|Dealer_Region|
|-------|-------|-------|-------|-------|-------|-------|-------|-------|------|-------|-------|------|-------|------|
|C_CND_000001	|1/2/2022|Geraldine|	Male	|13500|	Buddy |Storbeck's |Diesel| Service Inc	|Ford	Expedition|	DoubleÃ‚Â |Overhead |Camshaft|	Auto	Black	|26000	|06457-3834	|SUV	|8264678	|Middletown|
|C_CND_000002|	1/2/2022	|Gia	|Male|	1480000|	C & M Motors| Inc	Dodge|	Durango	|DoubleÃ‚Â| Overhead |Camshaft|	Auto	Black	|19000	|60504-7114|	SUV|	6848189|	Aurora|
|C_CND_000003	|1/2/2022	|Gianna|	Male	|1035000	|Capitol| KIA	|Cadillac	|Eldorado|	Overhead |Camshaft|	Manual|	Red	|31500|	38701-8047|Passenger	|7298798	|Greenville|
|C_CND_000004|	1/2/2022	|Giselle	|Male|	13500	|Chrysler of Tri-Cities|	Toyota	|Celica	|Overhead |Camshaft|	Manual	|Pale |White|14000	99301-3882|	SUV|	6257557|	Pasco|

## Query Languages: (SQL)
some of the query languages to retieve records are displayed here

```SQL
CREATE DATABASE new_car


CREATE TABLE Cars (
    CarID INT PRIMARY KEY,
    Brand VARCHAR(50),
    Model VARCHAR(50),
    Year INT,
    Price DECIMAL(12,2),
    FuelType VARCHAR(20),
    Transmission VARCHAR(20),
    Mileage INT,
    Color VARCHAR(20)
);

```
```SQL
---Inserting Values into Car table---

INSERT INTO Cars VALUES
(1, 'Toyota', 'Corolla', 2021, 50000, 'Petrol', 'Automatic', 20, 'white'),
(2, 'Honda', 'Civic', 2020, 25000,'Petrol', 'Manual', 22, 'black'),
(3, 'Tesla', 'Model 3', 2022, 40000,'Electric', 'Automatic', 45, 'yellow'),
(4, 'BMW', 'X5', 2019, 60000,'Diesel', 'Automatic', 55, 'blue'),
(5, 'Toyota', 'Camry', 2021,55000, 'Hybrid','Automatic', 28,'silver');

SELECT * FROM Car

```

<img width="574" height="173" alt="car table" src="https://github.com/user-attachments/assets/b8ca6e8f-f725-4475-a061-db4ab3715dc1" />


```SQL
---Creating customers table---

-- Customers Table
CREATE TABLE Customers (
    CustomerID INT PRIMARY KEY,
    FullName VARCHAR(100),
    Phone VARCHAR(20),
    Email VARCHAR(100),
    City VARCHAR(50)
);

```

```SQL
INSERT INTO Customers VALUES
(1, 'John Doe', '08012345678', 'john@example.com', 'Lagos'),
(2, 'Mary Smith', '08098765432', 'mary@example.com', 'Abuja'),
(3, 'David Johnson', '08045678901', 'david@example.com', 'Port Harcourt'),
(4, 'Sarah Williams', '08022233344', 'sarah@example.com', 'Ibadan');

```
<img width="562" height="173" alt="CUSTOMER TABLE" src="https://github.com/user-attachments/assets/c1882243-a7c1-46f4-a70b-2cf0930460f9" />

## Visualization
## Pivot Tables

![Uploading PPP.png…]()

## Chart

<img width="1468" height="728" alt="NEW CAR CHART" src="https://github.com/user-attachments/assets/5904961c-7076-4de9-b04a-433151314aec" />

## Power Bi Dashbord

![NEW CAR DASHBORD POWER BI 2](https://github.com/user-attachments/assets/7db039c2-3924-4d2e-aa15-77f614403fa6)


![Uploading NEW CAR 2.JPG…]()

## Summary
