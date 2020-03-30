### C#HW12
## Cox, Cody C.

1. How does inheritance promote the principle of don’t repeat yourself (DRY)?
Inheritance enables derived classes to use the methods and fields defined in the base class. Once you write the common methods and fields in the base class, you don't repeat yourself for each of the derived classes.

1. What is the syntax of a derived class that inherits from a base class?
The syntax of a derived class that inherits from a base class is class Derived Class.

1. Do all user deﬁned types (classes and structs) inherit from some base class? If so, what is it?
All classes inherit from System.Object. User defined structs cannot use user defined inheritance hierarchy, but inherit from the abstract class System.ValueType.

1. What happens if you do not have a default constructor in a base class when creating a derived class?
If you do not have any constructors in a base class, the compiler generates a default constructor for you. If you have defined a non-default constructor in a base class, the derived classes must call a base class constructor or it will result in a compile-time error.

1. Can you assign a variable of a derived class to another variable of its base class? Why or why not?
Yes because of matching logics.

1. Can you assign a variable of a derived class to another variable of of a derived class of its base class? Why or why not?
No

1. Can you assign a variable of a base class to another variable of a derived class? Why or why not?
Yes

1. Under what circumstances would you want to use the new keyword when deﬁning a method in a derived class?
You use the new keyword when defining a method in a derived class when defining a method with the same signature as the base class to signify that you understand that the method in the derived class is hiding the base class method.

1. What is a virtual method? Why would you want to deﬁne a virtual method?
A method that is intended to be overridden is called a virtual method. You want to define a virtual method to ensure standardization across derived classes.

1. What does override do? Why does it do it?
Overriding a method is a mechanism for providing different implementations of the same method.

1. How do you deﬁne an extension type?
You define an extension method in a static class and specify the type to which the method applies as the first parameter to the method, along with the this keyword.

1. Why do you deﬁne an extension type?
Using an extension method, you can extend an existing type (a class or a structure) with additional static methods.

1. (Not in book) Explain the Liskov substitution principle.
