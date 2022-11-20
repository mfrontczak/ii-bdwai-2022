# Lab 6
## Zadania
1. Dodaj do bazy danych poniższe tabele. Pamiętaj o utworzeniu odpowiednich kluczy głównych i obcych.

**ORDERS**
| ID | CustomerID | EmployeeID | OrderDate | ShippedDate | DeliveryAddress | DeliveryStreet      |
|----|------------|------------|-----------|-------------|-----------------|---------------------|
| 1  | 1          | 2          |           |             |                 |                     |


**ORDERDETAILS**
| ID | OrderID | PizzaID | UnitPrice | Quantity | Discount | Comments  | 
|----|---------|---------|-----------|----------|----------|-----------|
| 1  | 1       | 1       |  7,49     | 1        |  0       | no cheese |

**CUSTOMERS**
| ID | FirstName | LastName | City     | Street         | PhoneNumber  | PostCode |
|----|-----------|----------|----------|----------------|--------------|----------|
| 1  | Benedict  | Cucumber | New York | 729 7th Avenue | 555-123-1234 |  10019   |

