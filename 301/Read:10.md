# Call stack

A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function.


# The JavaScript Call Stack

The JavaScript engine (which is found in a hosting environment like the browser), is a single-threaded interpreter comprising of a heap and a single call stack. The browser provides web APIs like the DOM, AJAX, and Timers.

The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

# JavaScript error messages && debugging


- Types of error messages

    - Reference errors

    This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

    - Syntax errors

     I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

    - Range errors

    Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up. 


    