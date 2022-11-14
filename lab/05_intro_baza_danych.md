# Lab 5
 
## Zadania
1. Utwórz nową bazę danych. Dodaj do niej poniższe tabelki z odpowiednimi kluczami głównymi (z ustawionym na true identity specification) i obcymi. Uzupełnij dane. Niech wszystkie kolumny liczbowe prócz Price będą typu `int`, kolumna Price `Decimal(8,2)`, tekstowe `nvarchar(60)`, z datą `datetime`.

**EMPLOYEES**                                                       
| ID | FirstName | LastName   | JobPositionID | Rate | Bonus | HireDate   |
|----|-----------|------------|---------------|------|-------|------------|
| 1  | John      | Silverhand | 1             | 3400 | 340   | 01.01.2009 |
| 2  | Bart      | Simpson    | 5             | 1150 |       | 01.02.2018 |
| 3  | Morty     | Smith      | 2             | 1300 |       | 02.12.2013 |
| 4  | Rick      | Sanchez    | 4             | 1800 | 180   | 02.12.2013 |
| 5  | Sarah     | Connor     | 3             | 1600 |       | 15.06.2015 |


**JOBPOSITIONS**
| ID | Title        | Rate_from | Rate_to |
|----|--------------|-----------|---------|
| 1  | Manager      | 3200      | 4200    |
| 2  | Bartender    | 1200      | 1500    |
| 3  | Waitress     | 1200      | 1450    |
| 4  | Pizzaiolo    | 1800      | 2100    |
| 5  | Delivery Boy | 900       | 1300    |

**PIZZAS**
| ID | Name       | Price | Ingredients                                                     |
|----|------------|-------|-----------------------------------------------------------------|
| 1  | Margharita | 7,49  | Cheese                                                          |
| 2  | Hawaiian   | 9,99  | Ham, Pineapple                                                  |
| 3  | Veggie     | 12,00 | Red Peppers, Onions, Mushrooms, Green Olives, Italian Seasoning |
| 4  | Pepperoni  | 7,99  | Pepperoni                                                       |
| 5  | Meat Lover | 12,99 | Pepperoni, Italian Sausage, Bacon                               |

2. Zrób backup bazy danych.
3. Wyświetl wszystkich pracowników - ich imię, nazwisko, płacę oraz płacę powiększoną o 20%.
4. Wyświetl inicjały pracowników zbudowane z ich imienia i nazwiska. 
5. Policz ile lat pracuje każdy z pracowników.
6. Wyświetl pracowników pracujących ponad 8 lat.
7. Wyświetl pracowników zatrudnionych między 2012 a 2014.
8. Wyświetl wszystkie pizze zaczynające się na literę P lub H.
9. Wyświetl wszystkie pizze zawierające 'Pepperoni' w składnikach.
10.  Dla każdego pracownika wyświetl jego nazwisko, płacę podstawową i informację o tym, czy jego pensja jest mniejsza, równa lub większa od 1700. Wyniki posortuj wg nazwisk pracowników.
