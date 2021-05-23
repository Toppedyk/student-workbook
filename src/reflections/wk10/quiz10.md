# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
declarative region that provides a scope to the identifiers (the names of types, functions, variables, etc) inside it
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A structure is a value type so it is stored on the stack, but a class is a reference type and is stored on the heap. A structure doesn't support inheritance, and polymorphism, but a class supports both. By default, all the struct members are public but class members are by default private in nature
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
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
abstract
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
the data type the fuction returns
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
from the class being instantiated elsewhere
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
used to modify a method, property, indexer, or event declared in the base class and allow it to be overridden in the derived class
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public private internal protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only things in the same namespace
```