# Chapter 10: Error Handling & Debugging

JavaScript can be hard to learn and everyone makes
mistakes when writing it. This chapter will help you learn
how to find the errors in your code. It will also teach you how
to write scripts that deal with potential errors gracefully.

## ORDER OF EXECUTION

To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; (some tasks cannot complete until another statement or function has been run)

## EXECUT.ION CONTEXTS

The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope.

## The stack

the javaScript interpreter processes one line of code at a time.

## EXECUTION CONTEXT & HOISTING

Each time a script enters a new execution context, there are two phases
of activity:

1. PREPARE
2. EXECUTE

## UNDERSTANDING SCOPE

In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's varibles object.

## UNDERSTANDING ERRORS

If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code.

## ERROR OBJECTS

Error objects can help you find where your mistakes are
and browsers have tools to help you read them.

## This chapter  discuss

* If you understand execution contexts (which have two
stages) and stacks, you are more likely to find the error
in your code.
* Debugging is the process of finding errors. It involves a process of deduction.
* The console helps narrow down the area in which the
error is located, so you can try to find the exact error.
* JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.
* If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback.
