# Array

## What is an Array

* A data structure to store a collection of variables of the same type

* Arrays have a fixed size and has to be specified at declaration

* Size cannot be changed once declared

* Just like in JS arrays are object

* Use `new` to allocated

* Arrays are 0 indexed

## Declaring Arrays

* Example:

```(C#)

int[] numbers = new int[3];

```

## Initializing Arrays

* First we need to specify the value type the array will contain
  * `int`, `char`, `bool` etc

* Second use the square brackets to indicate an array is being declared

* Give the Array a name

* Use the equals operator to then set the space in memory (dont forget the `new` keyword)

* The right of the equal sign fill the square brackets with a number that denotes the length of array

* Example (initializing arrays known values):

```(C#)

int[] numbers = new int[3] { 1, 2 ,3  };

--OR--

var numbers = new int[3] { 1, 2 ,3  };

```

## Access Array Elements

* Arrays are accessed using bracket notation

* Example :

```(C#)

var numbers = new int[3] { 1, 2 ,3  };

Console.WriteLine(numbers[0])


```

* The code should print `1`