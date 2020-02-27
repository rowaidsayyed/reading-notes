# Welcome 201d3

The JavaScript interpreter uses the concept of **execution contexts**.

Javascript interepter process one line of code at a time.

Each time a script enters a new execution context, there are two phases of activity:
1. PREPARE
2. EXECUTE

Note : Understanding that these two phases happen helps with understanding a concept called hoisting.
If we are anticipating that something in the code may cause an error, we can use a set of statements to handle the error

## Error objects
Error objects can help us to find where the mistakes are and browsers have tools to help to read them.
There are seven types of built-in error objects
* Error
* Syntax Error
* Reference Error
* Type Error
* Range Error
* URI Error
* Eval Error

## HOW TO DEAL WITH ERRORS
1. DEBUG THE SCRIPT TO FIX ERRORS
2. HANDLE ERRORS GRACEFULLY

## LOGGING DATA TO THE CONSOLE
`console.log()`
### MORE CONSOLE METHODS
1. conso1e.info() can be used for general information
2. console.warn() can be used for warnings
3. console.error () can be used to hold errors
4. console.group() can be used to write a set of related data to the console
5. console.table() can be used to write data as a table
6. console.assert() can be used to test if a condition is met,and write to the console only if the expression evaluates to false.

## BREAKPOINTS
We can pause the execution of a script on any line using breakpoints.
### CONDITIONAL BREAKPOINTS
We can indicate that a breakpoint should be triggered only if a condition that we specify is met.
### DEBUGGER KEYWORD
we can create a breakpoint in the code using just the debugger keyword. When the developer tools are open, this will automatically create a breakpoint.

## HANDLING EXCEPTIONS
* TRY
* CATCH
* FINALLY

## THROWING ERRORS
If we know something might cause a problem for our script, we can generate our own errors before the interpreter creates them. using `throw new Error`


