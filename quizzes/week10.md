# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```

use to declare a scope that contains a set of related objects

```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```

structs are values, classes are references

```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```

A constructor

```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```

public

```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```

string is the type of response.

```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```

its preventing it being defined.

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```

allows it to be overwritten by the class.

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```

private public internal protected

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```

Only that service,class,etc. 

```