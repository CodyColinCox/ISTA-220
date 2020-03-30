### C#HW15
## Cox, Cody C.

1. What is the diﬀerence between a property and a ﬁeld?
Properties are accessed similarly to fields, but the compiler generates accessor methods in the form of getters and setters.

1. What is the diﬀerence between a property and a method?
Methods represent actions, and properties represent data. Properties can't accept arguments.

1. What is your understanding of encapsulation?
Encapsulation is the concept of modularizing functionality in code that hides some inner workings from the user. Certain properties, methods, or fields might be exposed to the users, others might not depending on your needs

1. Some languages are case insensitive, that is, an ‘a” and an “A” are considered to be the same letter. C# is case sensitive. What implications does this have regarding the naming of variables, methods, and other identiﬁers? Do you think that the diﬀerence in case in the initial character of two diﬀerent identiﬁers is suﬃcient to distinguish them?
I think that case sensitivity is effective as long as the programmer is very good at remembering the distinctiveness through out the entire script.

1. Give an example that is not in the book of an instance where you might want to use a read-only property. Give an example not in the book of an instance where you might want to use s write-only property.
fourwheelerwheels = 4, pincode for your phone.

1. Can you think of a reason why you might ever want to make getters and setters private? Give an example. Also, make a case why getters and setters should never be private.
There is no reason.

1. What are restrictions on the use of properties?
Must be initialized before value is assigned, can't be used as ref or out, only one get/set, no parameters, can't declare const properties

1. What is an object initializer? What is the syntax for an object initializer?
The syntax is Object object = new Object("param, param") {property1= 1, property2 = 2};
