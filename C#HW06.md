###C#HW06
##Cox, Cody C.

1. What is an exception?
An exception is an error in the code.

1. What happens in a try block if the program executes without errors
The code will keep running the remainder of the code and then go to the finally block where the code will execute.

1. How does the catch mechanism work for unhandled exceptions?
It will stop running the program.

1. What happens in a program if an exception block fails to handle an particular error?
If this occurs and the try block is part of a method, the method immediately exits and execution returns to the calling method.

1. What is the parent class for all exceptions? How does this work?
Exception. Exception is a catch all handler.

1. How do you determine the type of an error?
By the type of exception handler that was used when the exception was thrown after the try statement.

1.  What is the purpose of integer checking?
If you don't know the limits of your data types.

1. What is the range of values than a signed Int32 type can contain? State the lowest value and the highest value.
–2147483648 to 2147483647.

1. What is the range of values than an unsigned Int32 type can contain? State the lowest value and the highest value. What is the diﬀerence between a signed integer and an unsigned integer? Can signed integers and unsigned integers represent the same amount of numbers?
0 to 4,294,967,295.. A signed number indicating the relative values of this instance and value, he UInt32 value type represents unsigned integers with values ranging from 0 to 4,294,967,295. Yes they both represent the same amount of integers.

1. What does the ﬁnally block do?
Finally block, in the context of C#, refers to a block of statements that are always executed, regardless of unexpected events or exceptions that may occur during an application's execution.

1. When would you not use a ﬁnally block in a try/catch construction?
When you are running debug and only want to know the errors and not to complete a construction of code.
