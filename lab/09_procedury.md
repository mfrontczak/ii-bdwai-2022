# Lab 9

## Zadania
1. Stwórz procedurę, która wyświetli w osobnych rekordach liczby od 1 do podanej wartości.
2. Stwórz funkcję liczącą silnię (wersję iteracyjną i rekruencyjną).
3. stwórz procedurę składowaną, która wypisze wszystkie imiona i nazwiska  pracowników. 
4. Stwórz procedurę, która wypisze wszystkie rekordy z widoku utworzonego dla zamówień. 
5. Stwórz procedurę, która doda rekord do tabeli `Orders`.
6. Stwórz procedurę, która doda rekord do tabeli `Employees`, wpisujemy nazwę etatu nie ID, jeśli wprowadzono pensję większą lub mniejszą od dozwolonej rekord nie może być utworzony. Procedura ma zwrócić ilość ddodanych rekordów.
7. Sprawdzić działanie `IDENTITY_INSERT` - dodać rekord do pracowników z i bez `IDENTITY_INSERT`.
8. Stwórz procedurę, która wybierze rekordy pracowników, każde wystąpienie NULL ma być zastąpione odpowiednio przez 0 dla liczb lub '' dla napisów.
9. Stwórz procedurę, która zwróci rekord zawierający pracownika, który zarabia najwięcej.
10. Stwórz procedurę, która wybierze od `m`-tego do `n`-tego rekordu z tabeli `Employees`.
11. Stwórz procedurę składowaą, która będzie cofała wszystkie usunięcia dokonane przez dany login od zadanej daty.
12. Dodaj procedury składowane, pozwalające na "cofnięcie" usunięcia rekordu. Kryterium wyszukiwania rekordu to klucz głównym, przedział czasowy usunięcia (usunięcie w okresie od - do), login użytkownika. Co najmniej jeden parametr musi być podany, jeśli podane jest więcej niż jeden zachodzi koninkcja parametrów.
13. Stwórz procedurę zwracającą różnice między pensją najlepiej i najgorzej zarabiających pracownikiem oraz ich nazwiska.
