## Etapy projektu dla bazy danych
Projekt bazy danych może obejmować kilka etapów, w tym:

1) Analiza wymagań: Zrozumienie potrzeb biznesowych oraz poznanie danych, które będą przechowywane w bazie danych.
2) Projektowanie schematu: Określenie tabel i relacji między nimi, a także określenie kluczy głównych i obcych.
3) Implementacja: Tworzenie bazy danych zgodnie z zaprojektowanym schematem. Może to obejmować tworzenie tabel, indeksów, procedur składowanych i innych elementów.
4) Testowanie: Przeprowadzenie testów jednostkowych i integracyjnych, aby upewnić się, że baza danych działa poprawnie.
5) Dokumentacja: Utworzenie dokumentacji dotyczącej projektu, w tym schematu bazy danych, interfejsu API i procedur postępowania w przypadku awarii.
6) Wdrożenie: Instalacja i konfiguracja bazy danych na serwerze produkcyjnym i udostępnienie jej użytkownikom.
7) Utrzymanie: Monitorowanie i utrzymanie bazy danych, w tym aktualizacje, backupy i naprawa błędów.


## Zadanie
Projekt bazy danych dotyczącej sklepu internetowego:

1) Analiza wymagań: Sklep internetowy będzie sprzedawał różne produkty, a więc baza danych musi przechowywać informacje o produktach, takie jak nazwa, cena, opis, zdjęcie, kategoria itp. Baza danych musi również przechowywać informacje o klientach, takie jak imię, nazwisko, adres e-mail i historię zamówień.

2) Projektowanie schematu:
- Tabela produktów z kolumnami: ID produktu, nazwa, cena, opis, zdjęcie, kategoria.
- Tabela klientów z kolumnami: ID klienta, imię, nazwisko, adres e-mail, hasło.
- Tabela zamówień z kolumnami: ID zamówienia, ID klienta, data zamówienia, szczegóły zamówienia (np. ID produktu, ilość, cena), status zamówienia.

3) Implementacja: Tworzenie tabel zgodnie z zaprojektowanym schematem, korzystanie z języka SQL i odpowiedniego narzędzia (np. MySQL, PostgreSQL)

4) Testowanie: Przeprowadzenie testów, wprowadzanie danych testowych i sprawdzanie poprawności ich przechowywania, testowanie różnych scenariuszy użytkowych, takich jak dodawanie produktów, klientów i zamówień, pobieranie raportów itp.

5) Dokumentacja: Utworzenie dokumentacji dotyczącej projektu, w tym schematu bazy danych, interfejsu API i procedur postępowania w przypadku awarii

6) Wdrożenie: Instalacja i konfiguracja bazy danych na serwerze produkcyjnym, integracja z aplikacją sklepu internetowego i udostępnienie jej użytkownikom.

7) Utrzymanie: Monitorowanie i utrzymanie bazy danych, w tym aktualizacje, backupy i naprawa błędów, monitorowanie wykorzystania zasobów i optymalizacja wydajności.


