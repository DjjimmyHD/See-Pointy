# Conditional Statements  

## If/Else If/Else

* Seem to be the same as in JS

* You can nest if statements

## Switch Statements

* Similar to JS

* Example:

```(C#)
switch(role)
{
  case Role.Admin:
    ...
    break;
  case Role.Moderator
    ...
    break;
  default:
    ...
    break;
}
```

## Conditional Operators

* Basically ternary in JS

* Example:

```(C#)
{ 
  bool isActiveCustomer = true;

  int price;
  if(isActiveCustomer == true)
  {
    price = 10;
  } 
  else
  {
    price = 0;
  }
// SAME AS

  int price = (isActiveCustomer) ? 10 : 0;
}
```