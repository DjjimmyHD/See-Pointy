# What is `C#`

## Check your learning on C#

* When an exception is thrown what happens?
  * processing in the current method stops

* How do you indicate that class a derives from class b?
  * Use a colon between a and b

* If you push the values 1,2,3,5,7,11 onto a stack and then start popping values, what will be the third value dequeued?
  * 5

* A field is typically
  * Private

* What is a double?
  * a number that can hold a  fractional value

* Which of the following statements about Stored Procedures is true?
  * They allow you to store libraries of functions inside the database server
  *  **All of these**
  *  They can improve security by limiting users to specific approved queries
  *  They can provide a common set of database operations to multiple applications

* Where does extra space matter
  * In strings

* What are static methods
  * Class methods

* If an if statement is true what is executed?
  * the next statement or block of statements

* A constructor with no parameters is called
  * a default constructor

## Overview of C#

* CLR 
  * is common language run time
  * application that translates IL (intermediate language into Native Machine Code)
  * ^ this style is called Just in time Compilation

* Built out of a series of classes
  * Classes work together at run time to make an application 

* Class
  * Class is made up of data (attributes) and methods (functions)
  * Classes have behaviors (they do things for us)
  * Data represents the `state` of the application  
  * groups of classes are organized by a namespace
  * assembly is a collection of namespaces usually DLL (dynamically linked library) or EXE
  * compiler builds one or more assembly

* Void
  * Expects nothing to be returned from the function

* Parameters declare the expected type at creation

* Example:

```(C#)
Public class Calculator
{
  public int Add(int a, int b)
  {
    return a + b;
  }
}
```