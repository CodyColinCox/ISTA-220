### C#HW11
## Cox, Cody C.

1. What is a parameter array?
A parameter array can be used to pass an array of arguments to a procedure.

1. How do you deﬁne a method that takes an arbitrary number of arguments?
parameters

1. How do you call a method that takes an arbitrary number of arguments?
You just call the arguments that are identified in method.

1. Why can’t you use an array to pass an arbitrary number of arguments to a method?
Because it is already declared.

1. How many parameters can a method have?
vary from 0 on up.

1. Do parameter arguments have to have the same type?
Yes

1. What is the diﬀerence between a method that takes a parameter argument and one that takes optional arguments?
one only takes what is stated and the other will run an argument if needed but will not run every single time.

1. How do you deﬁne a method that takes diﬀerent (and arbitrary) types of arguments?
To define a method that takes different and arbitrary types of arguments, you use the object type params array.

. Write a method that accepts any number of arguments of a given type.
static int MethodBigDaddy(int[] args);

1. Write a method that accepts any number of arguments of any type.
