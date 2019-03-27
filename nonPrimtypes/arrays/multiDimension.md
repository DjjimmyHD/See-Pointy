# Multi-Dimensional Arrays

* CLR is maximized to process single dimension arrays so using a jagged array might be a better option

## Rectangular

* Each column has the exact same amount of items

* Can be 2-D or 3-D

* Example:

```(C#)
var matrix = new int[3, 5];

var matrix = new int[3, 5]
{
   {1,2,3,4,5,}
   {1,2,3,4,5,},
   {1,2,3,4,5,}
};
```

## Jagged

* Can be thought of as an array of arrays

* Each row of arrays will vary in length

* Example:

```(C#)
var array = new int[3][];

array[0] = new int[4];
array[1] = new int[5];
array[2] = new int[3];

```