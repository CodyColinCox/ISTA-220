1. What is a compound assignment operator? How does it work?
Assignment variables can be used to change the value of a variable and can be combined with any arithmetic operator with the assignment operator. They are can be used to append one string to another and update numeric values.

1. List all the compound assignment operators.
 - ++
 - /
 - %
 - *
 - --.

1. List two ways to increment a numeric variable by 5. List two ways to decrement a numeric variable by 50.
- EX1: variable +=5;
- Ex2: 0 + 5
  Decrement:
- Ex1: variable -=50;
- Ex2: variable - 50

1. How long does a while loop run?
A while loop iterates through the file one line at a time until there are no more lines available.

1. What is an iteration variable? (Not in book)
An iteration variable performs a custom iteration over a collection. Uses the yield return statement to return each element one at time. You use a 'foreach' statement or by using a LINQ query

1. What happens if you don't change the loop variable in the body of the while loop block?
You can possibly run into the common mistake of letting the loop run forever. The 'i' variable controls how often it runs

1. How many parts does a for loop statement have? Can you omit any of them? Can you omit all of
   them? What happens if you omit all of them?
- the for loop contains just a single statement.
- The three parts for a for loop are initialization, Boolean expression, and code that updates the control variable
- initialization occurs just once, at the very beginning of the loop. Then, if
  the Boolean expression evaluates to true, the statement runs. The control
  variable update occurs, and then the Boolean expression is reevaluated
- Yes you can omit certain parts of the for loop. By omitting Boolean expression, it defaults to true, so the following for statement runs
  forever:
- If you omit the initialization and update parts, you have a strangely spelled while loop

1. How do you guarantee that a loop runs at least once?
You guarantee that a loop runs at least once by making sure that the Boolean expression evaluates to true.

1. What does the break statement do?
break statement: allows you to jump out of the body of an iteration statement. When you break out of a loop, the loop exits immediately, and execution continues at the first statement that follows the loop. Neither the update nor the continuation condition of the loop is rerun.

1. What does the continue statement do?
the continue statement causes the program to perform the
next iteration of the loop immediately (after reevaluating the Boolean
expression).
if you execute a continue statement from within a for statement, the update part runs before performing the next iteration of the loop.

1. (Thought question) Can you think of any reason why you would want to have an infinite loop? An infinite loop is a loop without an update variable that in effect runs forever. As you will see, these
    kinds of loops are written intentionally to perform various kinds of tasks.
 Yes for programs that need to run for extended periods of time like a web server.
