# Variables and Constants

## Variables
  
* `type identifer(name) ;`

* Case sensitive language

* Cannot use a variable without initializing it

* Names cannot start with numbers

* Names cannot have whitespace or reserved keyword use `@` if it is reserved

* Camel Case for local variables `int number'`

* Pascal Case for constants `const int MaxZoom = 5;`

* by default the complier will use 'double'
  * if you want it to be treated differently then you need to declare it specifically
  * `float number = 1.2f;`
  * `decimal number = 1.2m;`

## Overflowing

* C# doesn't inherently control overflowing

* Overflow happens when your variable violates the constraints of its type

* Example:

```(C#)
checked
{
byte number = 255
    number = number + 1
}
```

* ^ overflow will not happen and an exception will be thrown, the program will error out

## Scope

* Block scoping, each variable has access inside each block scope 

* Example:

```(C#)
{
  int a = 1
  {
    int b = 2
    {
      int c = 3
    }
  }
}
```

## Type Conversion

* Implicit type conversion
  * when the complier is sure the types are compatible and there will be no data loss it will convert the data types

* Example:

```(C#)
byte b = 1;
int i = b;
```

* Explicit type conversion (casting)

* Example:

```(C#)
float f = 1.0f;
int i = (int)f;
```

* Conversion between non-compatible types

* Example:

```(C#)
string s = "1"
Convert.ToInt32(s);
Parse(s);
```

## Primitive Types

* All primitive types are structures

* They are small and take no more than 8 bytes