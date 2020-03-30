1. What does an array look like in memory?
a bunch of unordered sequence of items.

1. Where is memory allocated to hold an array, on the stack or on the heap?
heap

1. Where is memory allocated to hold an array reference, on the stack or on the heap?
stack

1. Can an array hold values of diﬀerent types? This is a trick question, the answer is, “It depends.” What determines the types that an array can hold?
You determine what types an array can hold when you create the instance of an array by utilizing new.

1. Describe the syntax of the condition for a foreach loop.
The foreach statement declares an iteration variable that automatically acquires the value of each element in the array. The type of this variable must match the type of the elements in the array.

foreach(int e in myArray)
  Console.WriteLine(e);

1. How do you make a deep copy of a array?
Initialize it, Take a copy of an array and for loop and increase incrementations by 1

1. What is the diﬀerence in the syntax between a multi-dimensional array and an array of arrays?
A multi-dimensional array can consume a lot of memory, which allocates memory for unused elements in an array. An array of arrays (also known as a jagged array) is an array in which each column has a different length which allows no space to be allocated for elements that an application is not going to use.

1. What is the diﬀerence in the uses for a multi-dimensional array and an array of arrays? In other words, what determines whether you would use one as opposed to the other?
1. How do you “ﬂatten” a multidimensional array? In other words, take something that looks like a matrix  1 2 3 4 5 6 7 8 9 and turn it into an array [1,2,3,4,5,6,7,8,9]? Write the code to do this in English. 10. (Thought question) When we use a for loop, we can change the values of the array elements inside the loop. When we use a foreach loop, we cannot change the values of the arry elements inside the loop. Why not? How is for diﬀerent from foreach?
nested loop

for (each element in the outter array)
  for(each element in the in the inner array)
  print (outterArray) (innerArray))
