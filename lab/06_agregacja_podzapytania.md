# Lab 6
## Zadania
1. Dodaj do bazy danych poniższe tabele. Pamiętaj o utworzeniu odpowiednich kluczy głównych i obcych.

**ORDERS**
| ID | CustomerID | EmployeeID | OrderDate           | ShippedDate         | DeliveryCity    | DeliveryStreet       |
|----|------------|------------|---------------------|---------------------|-----------------|----------------------|
| 1  | 1          | 4          | 07.11.2022 12:53:21 | 07.11.2022 13:11:01 |  New York       | 729 7th Avenue       |
| 2  | 1          | 4          | 11.11.2022 11:14:03 | 11.11.2022 20:35:16 |  New York       | 934 5th Avenue       |
| 3  | 1          | 4          | 11.11.2022 13:32:03 | 11.11.2022 13:55:43 |  New York       | 934 5th Avenue       |
| 4  | 1          | 4          | 11.11.2022 16:57:59 | 11.11.2022 17:26:33 |  New York       | 45 Rockefeller Plaza |
| 5  | 2          | 4          | 06.12.2022 10:41:32 | 11.11.2022 11:41:33 |  New York       | 20 W 34th St         |

**ORDERDETAILS**
| ID | OrderID | PizzaID | UnitPrice | Quantity | Discount | Comments  | 
|----|---------|---------|-----------|----------|----------|-----------|
| 1  | 1       | 1       |  7,49     | 1        |  0       | no cheese |
| 2  | 2       | 2       |  9,99     | 1        |  0       |           |
| 3  | 2       | 3       |  12,00    | 2        |  0       |           |
| 4  | 3       | 3       |  12,00    | 1        |  0       |           |
| 5  | 4       | 3       |  12,00    | 1        |  0       |           |
| 6  | 4       | 4       |  7,99     | 2        |  0       |           |
| 7  | 4       | 5       |  12,99    | 2        |  0       |           |


**CUSTOMERS**
| ID | FirstName | LastName      | City     | Street         | PhoneNumber  | PostCode |
|----|-----------|---------------|----------|----------------|--------------|----------|
| 1  | Benedict  | Cucumber      | New York | 729 7th Avenue | 555-123-1234 |  10019   |
| 2  | Bill      | Washington    | New York | 20 W 34th St   | 555-123-1234 |  10010   |

