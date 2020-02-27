# JavaScript

### CH.10 Error, Handling &Debugging
**ORDER OF EXECUTION**
To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

**EXECUTION CONTEXTS**
The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new execution context. They correspond to variable scope.

**The Stack**
the javascript interpreter processes one line of code at a time.
when a statement needs data from anpther function, it stacks (or piles) the new function on top of the current task.

**UNDERSTANDING SCOPE**
In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object.

**UNDERSTANDING ERRORS**
If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code.

**ERROR OBJECTS**
Error objects can help you find where your mistakes are and browsers have tools to help you read them.

**Types Of Error Objects**
- **_Type Error:_** VALUE IS UNEXPECTED DATA TYPE.
  1. INCORRECT CASE FOR document OBJECT.
  2. INCORRECT CASE FOR write() METHOD. 
  3. METHOD DOES NOT EXIST.
  4. DOM NODE DOES NOT EXIST.
- RangeError: NUMBER OUTSIDE OF RANGE.
- Error: GENERIC ERROR OBJECT.
- NaN: NOT AN ERROR; (NOT A NUMBER).

**HOW TO DEAL WITH ERRORS**
there are two things you can do with the errors:
1. DEBUG THE SCRIPT TO FIX ERRORS.
2. HANDLE ERRORS GRACEFULLY.

**HOW TO LOOK AT ERRORS**
The console will show you when there is an error in your JavaScript. It also displays the line where it became a problem for the interpreter.

**HANDLING EXCEPTIONS**
If you know your code might fail, use try, catch, and finally.
Each one is given its own code block.