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
