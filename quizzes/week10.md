# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
namespace is a keyword used to declare scope that contains a set of related objects. you can use a namespacce to organize code elements and to create globally unique types
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
the difference between a class and a struct is default accessibility of member variables and methods. in a struct they are public, in a class they are private.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void function
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
type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
the abstract modifer indicates that the thing being modified has a missing or incomplete implementation
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual keyword is used to modify a method, property, indexer, or event declaration and allow for it to be overridden in a derived class. For example, this method can be overridden by any class that inherits it:
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public 
abstract
internal
private
virtual
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the methods within the file or class
```