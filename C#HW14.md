### C#HW14
### Cox, Cody C.

1. What is the difference between a managed resource and an unmanaged resource?
Managed resources are taken care of by the CLR the unmanaged are not. things like file streams network connections.

1. When is memory for an object (reference type) allocated? When is the memory deallocated?
When a new instance is created, its deallocated when it goes out of scope.

1. What is a destructor?
Is a method similar to a constructor; the CLR calls it after the reference to an object has disappeared.

1. What is the difference in syntax between a constructor and a destructor?
A destructor is prefixed with a tilde ~

1. Give some examples of scarce resources. Why would you want to manage scarce resources?
memory, database connections, or file handles

1. What is exception-safe disposal?
it ensures that a disposal method is always called by placing it in the finally block

1. How do you think that the using statement works for resource management? Give an informal, English language, explanation of how it works.
it creates its own block of code and makes sure that the object is discarded

1. What ill effects could result from attempting to dispose of a resource more than once?
You might affect the logical integrity

1. We will look at threads later in the term. For now, what is your understanding of how threads interact with resource management? A good guess is a sufficient answer to this question.
its independent path of execution

1. Why does the book recommend not attempting to force the garbage collector? Are their any exceptions to this recommendation?
Because it makes your program slow. You only want to use it to reclaim unmanaged resources
