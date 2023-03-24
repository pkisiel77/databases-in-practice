Zadanie: Projektowanie bazy danych dla biblioteki miejskiej

Wymagania:

Zaprojektuj bazę danych dla biblioteki miejskiej, która będzie przechowywać informacje o książkach, czytelnikach, wypożyczeniach i pracownikach biblioteki.
Baza danych powinna umożliwiać śledzenie informacji o dostępności książek, czasie wypożyczenia, przeterminowanych wypożyczeniach oraz historii wypożyczeń każdego czytelnika.
Baza danych powinna być w stanie przechowywać informacje o różnych rodzajach materiałów, takich jak książki, czasopisma, audiobooki i e-booki.
Baza danych powinna umożliwiać śledzenie informacji o autorach, wydawnictwach i kategoriach (gatunkach) książek.
Baza danych powinna uwzględniać informacje o placówkach bibliotecznych oraz ich lokalizacji.
Schemat bazy danych:

Tabela Czytelnicy:

ID_Czytelnika (klucz główny)
Imię
Nazwisko
Data_urodzenia
Adres
Numer_telefonu
Adres_email
Data_rejestracji
Data_ważności_karty
Tabela Pracownicy:

ID_Pracownika (klucz główny)
Imię
Nazwisko
Stanowisko
Data_zatrudnienia
Adres
Numer_telefonu
Adres_email
ID_Placówki (klucz obcy)
Tabela Placówki:

ID_Placówki (klucz główny)
Nazwa
Adres
Numer_telefonu
Godziny_otwarcia
Tabela Książki:

ID_Książki (klucz główny)
Tytuł
ID_Autora (klucz obcy)
ID_Wydawnictwa (klucz obcy)
ID_Kategorii (klucz obcy)
Rok_wydania
ISBN
Ilość_egzemplarzy
Ilość_dostępnych_egzemplarzy
Tabela Autorzy:

ID_Autora (klucz główny)
Imię
Nazwisko
Tabela Wydawnictwa:

ID_Wydawnictwa (klucz główny)
Nazwa
Adres
Numer_telefonu
Adres_email
Tabela Kategorie:

ID_Kategorii (klucz główny)
Nazwa_kategorii
Tabela Wypożyczenia:

ID_Wypożyczenia (klucz główny)
ID_Czytelnika (klucz obcy)
ID_Książki (klucz obcy)
ID_Pracownika (klucz obcy)
Data_wypożyczenia
