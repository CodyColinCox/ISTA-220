### C#HW07
## Cox, Cody C

1. What is a class? According to the book, what does a class “arrange?”
(Class is a type) Class is the root word of the term classiﬁcation. When you design a class, you systematically arrange information and behavior into a meaningful entity. This arranging is an act of classiﬁcation and is  something that everyone does, not just programmers.

1. What are the two purposes of encapsulation?
Encapsulation is an important principle when defining classes.
To combine methods and data within a class, in other words, to support classification

1.  How do you instantiate an instance of a class? How do you access that instance?
In C#, you use the class keyword to deﬁne a new class. The data and methods of the class occur in the body of the class between a pair of braces.

1. What is the default access of the ﬁelds and methods of a class? How do you change the default?
Public and private. By declaring

1.  What is the syntax for writing a constructor?
public class Person
{
   private string last;
   private string first;

   public Person(string lastName, string firstName)
   {
      last = lastName;
      first = firstName;
   }

1.  What is the diﬀerence between class ﬁelds and methods, and instance ﬁelds ad methods? How do you create class ﬁelds and methods? class fields and methods are available to all classes where instance is only available in that instance

1. How do you bring a static class in scope? Why would you want to bring a static class in scope?
You use the name of the class and the assignment operator(.). To reference the desired method.

1.  Can you think of a good reason to create an anonymous class? What is it?
To not use all the properties in a class.

1. What is polymorphism as this term is used in computer science?
it describes the concept that objects of different types can be accessed through the same interface.

1. What is message passing as this term is used in computer science?
invoking behavior

1. What was the ﬁrst object-oriented programming language?
Simula
