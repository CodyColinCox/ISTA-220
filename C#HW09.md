### C#HW09
## Cox, Cody C.

1. What is an enum?
**Enum, in C#, is a keyword that represents a value type for declaring a set of named constants.**

1. Declare an enum for military ranks, either oﬃcer or enlisted. Name it Ranks. What are the symbols, like Private, Corporal, Sergeant or Lieutenant, Captain, Major?
**enum ranks { pvt, pfc, lcpl, cpl, sgt, ssgt, gysgt, msgt, mgysgt  };**

1. Using the Ranks enum, assign a rank to yourself and a friend.
**enum ranks { pvt, pfc }
ranks Cody =
ranks.pvt;

ranks larry =
ranks.pfc;**

1. Determine the numeric index of particular ranks, using the Ranks enum.
**pvt=0 pfc=1, lcpl=2, cpl=3, etc.**

1. How do you select the type of an enum?
**enum**

1. What is a struct?
**is a composite data type declaration that defines a physically grouped list of variables under one name in a block of memory, allowing the different variables to be accessed via a single pointer or by the struct declared name which returns the same address.**

1. List some diﬀerences between classes and structs.
**tructs are groups of variables and classes represent objects. Objects have attributes AND methods and be part of a hierarchy.**

1. Are structs stored on the stack or on the heap? What about enums?
**structs are stored on the stack. Enums are stored on the heap.**

1. Review the documentation for the C# System.Int32 struct. List the ﬁelds. List the methods.
**MaxValue, MinValue**

1. Declare a struct named DOD with four branches.
**struct DOD
{
string USMC;
string Boot;
string POG;
string PuddlePirate;
}**

1. Why can’t you create a default constructor for a struct?
**The reason is that, for a value type, compilers by default neither generate a default constructor, nor do they generate a call to the default constructor**

1. What is CIL? What does the CLR do to the CIL
**Common Intermediate Language, it allows you to run the language on .net framework.**
