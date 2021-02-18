[GitHub Pages](https://haneenzyad98.github.io/Reading-notes/201/class-10.html)

# Ch10 Error Handling & Debugging

To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run: 
If you understand execution contexts (which have two
stages) and stacks, you are more likely to find the error
in your code.

Debugging is the process of finding errors. It involves a
process of deduction. 


The console helps narrow down the area in which the
error is located, so you can try to find the exact error. 

JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error. 


HANDLING EXCEPTIONS TRY, CATCH, FINALLY