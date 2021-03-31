# Concepts of Functional Programming in Javascript


Complexity is anything that makes software hard to understand or to modify.

What is functional programming?
Functional programming is a programming paradigm  a style of building the structure and elements of computer programs


pure functions

     - It returns the same result if given the same arguments (it is also referred as deterministic)
      - It does not cause any observable side effects

What makes a function pure?

     - If our function reads external files, it’s not a pure function — the file’s contents can change.

     - Any function that relies on a random number generator cannot be pure.




Pure functions benefits

     he code’s definitely easier to test. We don’t need to mock anything.


# Immutability

When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

## Functions as first-class entities

The idea of functions as first-class entities is that functions are also treated as values and used as data.












