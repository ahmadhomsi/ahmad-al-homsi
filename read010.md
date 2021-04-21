# JavaScript book, Ch. 10, “Error Handling & Debugging”

will learn in this chapter about:

* THE CONSOLE & DEV TOOLS
Tools built into the browser
that help you hunt for errors.

* ERROR HANDLING & DEBUGGING
COMMON
PROBLEMS
Common sources of errors,
and how to solve them.
HANDLING
ERRORS
* How code can deal with
potential errors gracefully.

* ORDER OF EXECUTION
To find the source of an error, it helps to know how scripts are processed.


* EXECUT.ION CONTEXTS
The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope. 

* Each time a script enters a new execution context, there are two phases
of activity:
1. PREPARE

* The new scope is created
* Variables, functions, and arguments are created
* The value of the this keyword is determined
Understanding that these two phases happen helps
with understanding a concept called hoisting

2. EXECUTE
* Now it can assign values to variables
* Reference functions and run their code
* Execute statements 

* Error objects can help you find where your mistakes are
and browsers have tools to help you read them. 

* Now that you know what an error is and how the browser treats them,
there are two things you can do with the errors.

1. DEBUG THE SCRIPT TO FIX ERRORS
If you come across an error while writing a script
(or when someone reports a bug), you will need to
debug the code, track down the source of the error,
and fix it.

* You will find that the developer tools available in
every major modern browser will help you with
this task. In this chapter, you will learn about the
developer tools in Chrome and Firefox. (The tools in
Chrome are identical to those in Opera.)

* IE and Safari also have their own tools (but there is
not space to cover them all).
@ ERROR HANDLING & DEBUGGING
2. HANDLE ERRORS GRACEFULLY
You can handle errors gracefully using try, catch,
throw, and f i na 1 ly statements.

* Sometimes, an error may occur in the script for a
reason beyond your control. For example, you might
request data from a third party, and their server
may not respond. In such cases, it is particularly
important to write error-handling code.

* In the latter part of the chapter, you will learn how to
gracefully check whether something will work, and
offer an alternative option if it fails. 

1. If you understand execution contexts (which have two
stages) and stacks, you are more likely to find the error
in your code.

2. Debugging is the process of finding errors. It involves a
process of deduction.
The console helps narrow down the area in which the
error is located, so you can try to find the exact error.

3. JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.

4. If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements