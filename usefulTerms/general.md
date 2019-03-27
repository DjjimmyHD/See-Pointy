# General Glossary of Terms

* Will serve as a place to put terms as I am learning them or as a reference for terms I want to look up or wrestle with later

## Method Overloading

* Most of the class methods in C# have what is called method overloading

* When the `Array` class was created there were also a number of methods that were added on

* Each of those methods seem to have multiple ways you can use the method (`IndexOf()` has 5)

* To achieve this, you have to `overload` the method
  * Meaning that when the constructor is created you write the different ways the methods can be used
  * They exist on the constructor
  * Essentially saying "hey I have this method, I have prebuilt x amount of ways to use one method, take it or leave it chump"

* This is nifty but very nuanced, when you are creating a class method you have to make a lot of assumptions on how the method will be used
could get messy. Predicting the future is hard.