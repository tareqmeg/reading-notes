EXECUTION CONTEXT & HOISTING 

1: PREPARE

- The new scope is created.
- Variables, functions, and arguments are created.
- The value of the this keyword is determined.

2: EXECUTE

- Now it can assign values to variables.
- Reference functions and run their code.
- Execute statements.


UNDERSTANDING
SCOPE

In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object. 

![scope](./scoop.PNG)


UNDERSTANDING ERRORS

If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handl ing code.

ERROR OBJECTS 

Error objects can help you find where your mistakes are
and browsers have tools to help you read them. 

When an Er ror object is created, it will contain the
following properties: 

PROPERTY | DESCRIPTION
----- | --------
Name | Type of execution
message | Description
file Number | Name of the JavaScript file 
lineNumber | Line number of error


When there is an error, you can see all of this
information in the JavaScript console I Error console
of the browser. 



