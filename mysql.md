# MySQL (Oracle)

## Install

```
https://www.mysql.com/downloads/
https://docs.ovh.com/pl/clouddb/mysql-i-mariadb/
```

## SQL

### SELECT
```sql
SELECT pozycje
FROM nazwy_tabel
[WHERE warunek]
[GROUP BY rodzaj_grupowania]
[HAVING wartość_funkcji]
[ORDER BY porządek_sortowania]
[LIMIT ilość];
```
```sql
SELECT * FROM kategoria;
SELECT * FROM biblioteka.zamowienie WHERE id_czytelnik = 1;
```
```sql
SELECT z.id_zamowienie, k.isbn, z.id_czytelnik, z.data_zamowienia, z.data_odbioru
FROM zamowienie z, ksiazka k
WHERE k.isbn = '9788324685301'
AND z.id_ksiazka = k.id_ksiazka
ORDER BY z.data_zamowienia DESC
LIMIT 1;
```
### INSERT
```sql
INSERT [INTO] nazwa_tabeli (kolumna_1, kolumna_2, kolumna_3, ...)
VALUE (wartość_1, wartość_2, wartość_3, ...);
```
### UPDATE
```sql
UPDATE nazwa_tabeli
SET kolumna_1 = wyrażenie_1, kolumna_2 = wyrażenie_2, …
[WHERE warunek]
[LIMIT ilość]
```
```sql
UPDATE zamowienie SET data_odbioru = CURRENT_TIMESTAMP WHERE id_zamowienie = '4';
```

## Literatura
[1] https://www.wiedzanaplus.pl/bazy-danych/20-mysql/9-przykladowy-projekt-bazy-danych-internetowy-system-biblioteczny.html
