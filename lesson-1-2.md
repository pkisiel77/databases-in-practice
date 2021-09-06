# Podstawowe pojęcia związane z bazami danych (2021)

## Podstawa

### Baza danych 

***Baza danych - to zorganizowany zbiór usystematyzowanych informacji, czyli danych, zwykle przechowywany w systemie komputerowym w formie elektronicznej. Bazą danych steruje zwykle system zarządzania bazami danych (DBMS). Dane i system DBMS oraz powiązane z nimi aplikacje razem tworzą system bazodanowy, często nazywany w skrócie bazą danych.***
[lit. 1](https://www.oracle.com/pl/database/what-is-database/)

***Baza danych – zbiór danych zapisanych zgodnie z określonymi regułami. W węższym znaczeniu obejmuje dane cyfrowe gromadzone zgodnie z zasadami przyjętymi dla danego programu komputerowego specjalizowanego do gromadzenia i przetwarzania tych danych. Program taki (często pakiet programów) nazywany jest „systemem zarządzania bazą danych” (ang. database management system, DBMS).***
[lit. 2](https://pl.wikipedia.org/wiki/Baza_danych)

[Ustawa z dnia 27 lipca 2001r.](http://isap.sejm.gov.pl/isap.nsf/download.xsp/WDU20011281402/T/D20011402L.pdf)

Każdy projekt w IT powinien być wykonywany zgodnie z wcześniej ustalonymi wymaganiami. W wymaganiach powinny być zawarte min. definicje, pojęcia na bazie kótrych będzie wykonywan projekt.

#### Dodatkowo
***Jaka jest różnica między bazą danych a arkuszem kalkulacyjnym?***
[Odpowiedź](https://www.oracle.com/pl/database/what-is-database/)
![image](https://user-images.githubusercontent.com/26519123/132105452-401fa3fb-b03b-4240-bf57-ecee210c34fc.png)

https://eduinf.waw.pl/inf/utils/015_2015/0009.php

### Relacyjna baza danych

***Relacyjna baza danych to rodzaj bazy danych, który pozwala przechowywać powiązane ze sobą elementy danych i zapewnia do nich dostęp. Relacyjne bazy danych są oparte na modelu relacyjnym — jest to prosty i intuicyjny sposób przedstawiania danych w tabelach. W relacyjnej bazie danych każdy wiersz tabeli jest rekordem z unikatowym identyfikatorem nazywanym kluczem. Kolumny tabeli zawierają atrybuty danych, a każdy rekord zawiera zwykle wartość dla każdego atrybutu, co ułatwia ustalenie relacji między poszczególnymi elementami rekordu.***
[lit. 5](https://www.oracle.com/pl/database/what-is-a-relational-database/)


> Relacyjna baza danych jest to zestaw encji i związków zachodzących miedzy nimi.


### Encja

> Encja jest to każdy przedmiot, zjawisko, stan lub pojęcie, czyli każdy obiekt, który potrafimy odróżnić od innych obiektów (np. osoba, samochód, książka itd)

> Podobne do siebie encje ( te same parametry ) grupujemy w zriór encji. 

> Projektując bazę danych należy precyzyjnie zdefiniować encje i określić parametry.

![image](https://user-images.githubusercontent.com/26519123/132177912-e84d5700-56e0-4730-a83c-535730d25625.png)

### Atrybut

> Encje mają określonr cechy wynikające z ich natury. Cechy te nazywamy **atrybutami**.  

![image](https://user-images.githubusercontent.com/26519123/132178385-7a460559-f6b6-42e3-9d02-880c67980e8b.png)


### Dziedzina

> Atrybuty encji mogą przyjmować różne wertości. Projektując bazę danych, możemy określić, jakie wartości może przyjmować dany atrybut. Zbiór wartości atrybutu nazywamy dziedziną (domeną).

## Diagram ERD - wstęp

> Konceptualne projektowanie baz danych to konstruowanie schemtu danych niezależnego od wybranego modelu danyc, docelowego systemu zarządzania bazą danych, prgramów użytkowych czy jezyka programowania.

> Do tworzenia modelu graficznego schematu bazy danych wykorzystujemy diagramy związków encji - diragram ERD (ang. Entity Relationship Diagram)

> Diagram ERD składa się z trzech rodzajów elementów:
> - zbiór encji
> - atrybuty encji
> - związki zachodzące między encjami 

![image](https://user-images.githubusercontent.com/26519123/132180556-039f0428-0ad2-4c3c-a7ad-0a35f745597a.png)

### Przykład diagramu ERD

![image](database-erd-ex1.png)

## [Literatura](literature.md)

## [Narzędzia](utils.md)
