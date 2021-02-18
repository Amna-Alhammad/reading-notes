# **Chapter 10 : Chapter 10: Error Handling & Debugging**
## Debugging is the process of finding errors. It involves a process of deduction
## If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
## If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.
## The console helps narrow down the area in which the error is located, so you can try to find the exact error.
## JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
## **ERROR OBJECTS**
- Error ------>	Generic error - the other errors are all based upon this error
- Syntax Error	------->  Syntax has not been followed
- ReferenceError ------>	Tried to reference a variable that is not declared/within scope
- TypeError --------->	An unexpected data type that cannot be coerced
- Range Error ------>	Numbers not in acceptable range
- EvalErorr	--------> eval() function used incorrectly
- URI Error --------->	encodeURI().decodeURI(),and similar methods used incorrectly

## Order of Execution
To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run:
## Excution Contexts
The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.
## The Stack
The JavaScribt interpreter processes onr line of code at a time.When a statement needs data from another function, it stacks (or piles) the new function on top of the current task.
## UNDERSTANDING SCOPE
In the interpreter, each execution context has its own variables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v ariab1 es object.
## ERROR OBJECTS
Error objects can help you find where your mistakes are and browsers have tools to help you read them.
## **HOW TO DEAL WITH ERRORS** 
1- DEBUG THE SCRIPT TO FIX ERRORS Debugging is about deduction: eliminating potential causes of an error. Try to narrow down where the problem might be, then look for clues.
2- HANDLE ERRORS GRACEFULLY You can handle errors gracefully using try, catch, throw, and finally statements.

## **THROWING ERRORS**
If you know something might cause a problem for your script, you can generate your own errors before the interpreter creates them . throw new Error ('message');

## **HANDLING EXCEPTIONS**
- TRY
- CATCH 
- FINALLY 
## **DEBUGGING TIPS**
Here are a selection of practical tips that you can try to use when debugging your scripts. 
1- ANOTHER BROWSER 
2- ADD NUMBERS
3- STRIP IT BACK 
4- EXPLAINING THE CODE 
5- SEARCH 
6- CODE PLAYGROUNDS
7- VALIDATION TOOLS
