# Lab 8

## Zadania

1. Utwórz widok z pracownikami i nazwą ich stanowiska.
2. Utwórz widok z pełną informacją o zamowieniach z `Orders`.
3. Zmodyfikuj bazę danych dodając do każdej tabeli kolumnę `DeleteDate`. Jesli w danym rekordzie pole bedzie miało wartość `NULL` oznacza to, że rekord jest "aktualny". Jeśli będzie zaweirał datę, oznacza to, że rekord stracił ważność w dniu i o godzinie wskazanej przez datę.
4. Do każdej tabeli dodaj tabelę, która będzie zapamietywać rodzaj wykonanej kwerendy DML, login uzytkownika, który ją wykonał, id rekordu, który jest zmieniany, datę wykonania oraz rodzaj kwerendy (insert, update lub delete).
5. Dodaj wyzwalacze, które będą dodawały rekordy do tabel z poprzedniego punktu.
6. Dodaj wyzwalacz, który będzie zapobiegał usuwaniu rekordów i wstawiał datę do pola `DeleteDate`.
7. Dodaj wyzwalacz, który będzie zapobiegać modyfikowaniu i usuwaniu tabel.
