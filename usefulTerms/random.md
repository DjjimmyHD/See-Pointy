# Random Class

* Generates a random number

* Multiple methods on the class

* Fast way to create an array with certain types of numbers

* Use Case:
  * So far I can see this being useful for testing some logic when you don t have the exact data off hand
  * can be used to generate passwords 🤷🏿‍♂️

* Example:

```(C#)
{
  var random = new Random();
  for (var i = 0; i < 10; i++)
    Console.Write(random.Next(1,10))
}
```

* In the example above the program will give generate a random number between 1-10 and print it to the console each time