# Enums

* Set of name/value pairs (constants)

* Basically an object with an intentional name who's values will never change

* Navigated via dot notation

* internally an enmum is treated as an integer

* Example :

```(C#)
public enum ShippingMethod
{
  RegularAirMail = 1,
  RegisteredAirMail = 2,
  Express = 3;
}
```