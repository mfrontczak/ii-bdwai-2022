# Lab 11

## Materiały pomocnicze
1.	Samouczek: wprowadzenie do platformy ASP.NET Core: https://learn.microsoft.com/pl-pl/aspnet/core/getting-started/?view=aspnetcore-6.0&tabs=windows
2.	Samouczek: Wprowadzenie do ASP.NET Core MVC: https://learn.microsoft.com/pl-pl/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-6.0&tabs=visual-studio 
3.	Adnotację danych dla modelu:  https://learn.microsoft.com/pl-pl/dotnet/api/system.componentmodel.dataannotations.datatype?view=netcore-3.1 
4.	Pomocnicze tagi dla formularzy (forms): https://learn.microsoft.com/pl-pl/aspnet/core/mvc/views/working-with-forms?view=aspnetcore-6.0 
5.	Walidacja modelu: https://learn.microsoft.com/pl-pl/aspnet/core/tutorials/first-mvc-app/validation?view=aspnetcore-6.0, https://learn.microsoft.com/pl-pl/aspnet/mvc/overview/older-versions/mvc-music-store/mvc-music-store-part-6 
6.	Wyszukiwanie w liście: https://learn.microsoft.com/pl-pl/dotnet/api/system.linq.enumerable.singleordefault?view=net-7.0 
7.	Usuwanie elementów z listy: https://learn.microsoft.com/pl-pl/dotnet/api/system.collections.generic.list-1.remove?view=net-7.0 

```Csharp
  public static class Repository
  {
      private static List<Dish> dishes = new List<Dish>() {
        // dodaj jakieś obiekty
      };


      public static IEnumerable<Dish> Dishes => dishes;

      public static void AddDish(Dish dish)
      {
        // zaimplementuj
      }

      public static void RemoveDish(int? id)
      {
        // zaimplementuj
      }
  }
```

## Zadania
1. Utwórz nowy projekt **RestaurantMVC**, projekt ASP.NET (Model-View-Controller)
2. Dodaj nowe modele **Dish** zawierający pola: 
**Name** (string), **Price** (decimal), **Ingrediants** (string), **Preperation** (string), **IsAvailable** (boolean)
3. Utwórz kontroler **DishController**, zmodyfikuj akcję **Index** aby zwracała listę dostępnych potraw (model **Dish**). 
4. Wykorzystaj klasę **Repository**, zaimplementuj odpowiednie metody pozwalające na wykonanie odpowiednich modyfikacji. 
RemoveDish powinno ustawiać pole **IsAvailable** na false.
5. Zmodyfikuj akcję **Index** aby wyświetlała tylko dostępne potrawy.
6. Dodaj formularz pozwalający na dodawanie nowych dań, pamiętaj o zastosowaniu specjalnych tagów asp.
7. Dodaj nową akcję pozwalającą na "usunięcie" danego dania z listy.
