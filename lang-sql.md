# Podstawy języka SQL 

| Polecenie | Opis |
| ------------- |:-------------:|
| SELECT| wyświetlanie rekordów |
| INSERT| wstawianie rekordów |
| UPDATE| modyfikacja rekordów |
| DELETE| kasowanie rekordów |
| CREATE| tworzenie obiektów (np. tabel) |
| ALTER| modyfikowanie obiektów (np. tabel) |
| DROP| kasowanie obiektów (np. tabel) |

## SELECT

## INSERT

```sql
INSERT INTO client VALUES (1, 'Artur', 'Nowakowski', 'P');
INSERT INTO client VALUES (2, 'Jan', 'Kowalski', 'P');
INSERT INTO client VALUES (3, 'Roman', 'Nowak', 'U');
INSERT INTO client VALUES (4, 'Stefan', 'Antkowiak', 'A');
INSERT INTO client VALUES (5, 'Ewa', 'Konieczna', 'A');
INSERT INTO client VALUES (6, 'Anna', 'Wojtasik', 'A');
INSERT INTO client VALUES (7, 'Marek', 'Pawlak', 'P');
```

```sql
INSERT INTO client VALUES
     (1, 'Artur', 'Nowakowski', 'P'),
     (2, 'Jan', 'Kowalski', 'P'),
     (3, 'Roman', 'Nowak', 'U'),
     (4, 'Stefan', 'Antkowiak', 'A'),
     (5, 'Ewa', 'Konieczna', 'A'),
     (6, 'Anna', 'Wojtasik', 'A'),
     (7, 'Marek', 'Pawlak', 'P');
```

## UPDATE
```sql
UPDATE Persons  SET email='mrorzon@gmail.png', phone='123123123' WHERE PersonID=1;
UPDATE Persons SET email='Sid@epokalodowcowa.yes', phone='999000888' WHERE PersonID=2;
UPDATE Persons SET email='PIZZERIA@nonketchup.jpg', phone='888888888' WHERE PersonID=3;
UPDATE Persons SET email='maSłO@kefir.gif', phone='123456789' WHERE PersonID=4;
UPDATE Persons SET email='nosaty@onet.www', phone='987654321' WHERE PersonID=5;
UPDATE Persons SET email='niewolnik1@gmail.com', phone='855 559 912' WHERE PersonID=6;
UPDATE Persons SET email='kOSmita0@gmail.com', phone='000 000 000' WHERE PersonID=7;
UPDATE Persons SET email='Prezspies@gmail.com', phone='832 594 448' WHERE PersonID=8;
UPDATE Persons SET email='encyklopedia@scrace.com', phone='248 250 260' WHERE PersonID=9;
UPDATE Persons SET email='zabson@grucz.com', phone='532 653 146' WHERE PersonID=10;
```

## DELETE

## DROP

## CREATE
```sql
CREATE TABLE Persons (
    PersonID int,
    LastName varchar(255),
    FirstName varchar(255),
    Address varchar(255),
    City varchar(255)
);
```

```sql
Insert Into Persons (PersonID, LastName, FirstName, Address, City) Values (1, 'Korzon', 'Kubuś', 'Korzońska51', 'Podlaś'), (2, 'Sosna', 'Sined', 'tak 476', 'Sosnowiec'), (3, 'Italian', 'Kamil', 'Pizzerowa 90', 'MAMMA MIAAAA'), (4, 'Mselniczka', 'Kevin', 'Maślankowa 45', 'Maśleniczankowo'), (5, 'Nosaczowy', 'Nosacz', 'Smarkowa895', 'Smarkowo'),(6,'Niewolniczy', 'Niewolnik', 'niewolnicza 21a', 'Szkoła'),(7,'Koszmiczny', 'Kosmita',' strefowa 51', 'Ziemia 2.0'),(8,'Prezoesowy','prezes','biznesowa 5', 'sosnowie'),(9,'Książkowicz', 'Książka', 'Papiernicza 55g', 'Biblioteka'),(10, 'Żabski', 'Żaba', 'Wodna 35b', 'Jezioro');
```

## ALTER

```sql
ALTER TABLE Persons ADD Email varchar(255);
ALTER TABLE Persons ADD Phone varchar(50);
```

## SQL

```
SELECT * FROM Customers WHERE Country IN ('Germany', 'France', 'UK');
SELECT * FROM Customers WHERE CustomerID IN (1,2,10,11);
SELECT ProductName 
FROM Products
WHERE ProductID in (37,19,69);

SELECT ProductName 
FROM Products
WHERE ProductID in (SELECT ProductID FROM OrderDetails WHERE Quantity = 1);
```

## SQL Logical Operators

