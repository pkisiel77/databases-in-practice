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

## DELETE

## DROP

## CREATE

## ALTER

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

