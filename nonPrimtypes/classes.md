# Classes

* Arrays and strings are classes, we can also create custom classes

* separated into fields (data) and methods

* Objects are an instance of a class

* Creating a class

  * Specify access with an access key word
    * `public` or `private`

  * Use the `class` keyword

  * Name the class

* Example:

```(C#)
public class Person
{
  public string Name;
}
```

* Fields are variable in the class (properties)
  * In the above example `Name` is a field in the class
  * Fields also have access keywords

* When you create objects or a new instance of the class you have to declare memory upfront
  * we can use the reserved key word `new`

* CLR will handle garbage collection at runtime. Removes all objects that are unused

* Example:

```(C#)
var person = new Person();
person.Name = "james";
person.Introduce();
```

* If you use the `static` keyword you do *not* have to create a new object to access that object
  * use `static` when only a single instance of that method needs to exist in memory
  * this parent method can be referenced in memory when we need it in other objects
