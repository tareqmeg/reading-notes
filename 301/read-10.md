# Readings: THE CALL STACK


Call stack
A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.

- When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
- Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
- When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
- If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

> Example

`function greeting() {`

   `// [1] Some code here`

  ` sayHi();`

  ` // [2] Some code here
}`

`function sayHi() {`

  ` return "Hi!";`

`}`

`// Invoke the `greeting` function`

`greeting();`

`// [3] Some code here`

The code above would be executed like this:

Ignore all functions, until it reaches the greeting() function invocation.

Add the greeting() function to the call stack list.
Call stack list:
- greeting

Execute all lines of code inside the greeting() function.

Get to the sayHi() function invocation.
Add the sayHi() function to the call stack list.
Call stack list:
- sayHi
- greeting

Execute all lines of code inside the sayHi() function, until reaches its end.

Return execution to the line that invoked sayHi() and continue executing the rest of the greeting() function.

Delete the sayHi() function from our call stack list.

Call stack list:
- greeting

When everything inside the greeting() function has been executed, return to its invoking line to continue executing the rest of the JS code.

Delete the greeting() function from the call stack list.

Call stack list:

EMPTY

In summary, then, we start with an empty Call Stack. Whenever we invoke a function, it is automatically added to the Call Stack. Once the function has executed all of its code, it is automatically removed from the Call Stack. Ultimately, the Stack is empty again.

call stack are:
1. It is single-threaded. Meaning it can only do one thing at a time.
2. Code execution is synchronous.
3. A function invocation creates a stack frame that occupies a temporary memory.
4. It works as a LIFO — Last In, First Out data structure.



[Click here to read more](lab02b.md)