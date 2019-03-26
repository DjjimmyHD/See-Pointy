# Two main types

* Same as JS for the most part. Value types take up a specific place in memory while reference types are **references** to a location in memory.
Logically it should follow that the below example is true in C#

* Example:

```(JavaScript)
let x = 2
let y = x
    x = 3

console.log(y)
// y = 2

console.log(x)
// x = 3

let person = {
  name : 'james'
}

let dopple = {
  name : 'james'
}

let twin = person

console.log(person === dopple)
// false

console.log(twin === person)
// true
```

## Value Types

* Structures (see primitive types)

* int, char, byte

* When created memory is allocated automatically

* Allocated on `stack`

* Immediately removed when out of scope at run time

## Reference Types

* Classes (see classes)

* Objects, strings, arrays

* Developers are responsible for allocating memory

* See `new` operator

* Memory allocated on `heap`

* If an object goes out of the scope it will remain on the heap for a bit

* It will not be removed automatically

* Removed by CLR `garbage collection`
  * removes all unused objects
