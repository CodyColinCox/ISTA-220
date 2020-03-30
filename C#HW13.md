### C#HW13
## Cox, Cody C.

1. What is an interface as the term is used on object-oriented programming?
set of methods (or messages) that an instance of a class that has that interface could respond to.

1. How do you deﬁne an interface?
Deﬁning an interface is syntactically similar to deﬁning a class, except that you use the interface keyword instead of the class keyword.

1. Can an interface have variables, ﬁelds, or properties?
Variables-No, you can have variables in Base classes though.
Fields-No, don't allow fields because they consist of a contract that is a list of methods, whose implementation is provided by a class.
properties- Yes, because they are paired with methods.

1. How do you deﬁne a method in an interface?


1. Can you instantiate an object through an interface? Why or why not?
Yes

1. Using the new keyword, can you declare a reference to an interface?
Yes

1. Can an object inherit from multiple interfaces? Can a class implement multiple interfaces? If so, how can it do so?
Yes, No

1. What does it mean to explicitly implement an interface?
You have to specify what the interface is.

1. What are the restrictions on interfaces?
■ You’re not allowed to deﬁne any ﬁelds in an interface, not even static ﬁelds. A ﬁeld is an  implementation detail of a class or structure.
■ You’re not allowed to deﬁne any constructors in an interface. A constructor is also considered to be an implementation detail of a class or structure.
■ You’re not allowed to deﬁne a destructor in an interface. A destructor contains the statements used to destroy an object instance. (Destructors are described in Chapter 14, “Using garbage collection and resource management.”)
■ You cannot specify an access modiﬁer for any method. All methods in an interface are implicitly public.
■ You cannot nest any types (such as enumerations, structures, classes, or interfaces) inside an interface.
■ An interface is not allowed to inherit from a structure or a class, although an interface can inherit from another interface. Structures and classes contain implementation; if an interface were allowed to inherit from either, it would be inheriting some implementation.



1. What is the diﬀerence between an abstract class and an interface?
Abstract class can be considered as an abstract version of a regular (concrete) class, while an interface can be considered as a means of implementing a contract.

1. What is an abstract method?
An abstract method is similar in principle to a virtual method, except that it does not contain a method body.

1. What is an sealed class?
With C#, you can use the sealed keyword to prevent a class from being used as a base class if you decide that it should not be.

1. What is an sealed method
You can also use the sealed keyword to declare that an individual method in an unsealed class is sealed. This means that a derived class cannot override this method. You can seal only a method declared with the override keyword, and you declare the method as sealed override.
