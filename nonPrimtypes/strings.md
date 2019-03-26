# Strings

## What is a string

* A sequence of characters

* Denoted by `"` where characters are wrapped with `'`

* Strings can still be concatenated using the `+` operator

* Acessing strings is done via bracket notation

* Strings are immutable

## How to create strings

* Multiple ways to create strings

* Example (String Literal):

```(C#)
string firstName = "James";
```

* Example (String Format):

```(C#)
string name = string.Format("{0} {1}", firstName, lastName);
```

* In the example above we are calling the `Format` method on the `string` class

* since `Format` is a `static` method we can access it using dot notation

* **There are multiple strings methods just like in JS and they all return a new string**

* Example (Verbatim String)

```(C#)
string path = "c:\\projects\\project1\\folder1";
```

## Escape characters and verbatim strings