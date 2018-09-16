# FIX ALL THE ERRORS

## Objectives

- Demonstrate a generalized approach to dealing with different types of errors
- Show a series of errors being solved with rational debugging steps
- Demonstrate the available tools for information gathering about errors/bugs
  - Google
  - React developer tools
  - Chrome developer tools
  - Debugger
  - Console logs

## Types of Errors

### Compiler/Syntax errors

- Will throw an error and not allow the program to run
- Can be anything from a typo to a missed semi-colon
- The error will usually include the line number that the compiler failed at
- Approach:
  - Go to the designated line
  - Carefully check the line for spelling, and appropriate syntax
  - If you still can find anything, check again! Our brains go into skimming mode very easily and little details are easy to overlook
  - If a syntax error is still being thrown, it could be a misunderstanding on your part. Double check examples online/past code/documentation to make sure you're implementing the code correctly.

### Runtime Errors

- This is an error that will compile correctly, but break while the program is running
- The program understood the instructions, but the instructions were flawed
- Examples:
  - Dividing by zero
  - Referencing a variable that was never declared
  - Calling a method that does not exist
- Approach:
  - Read the error and try to glean what it is saying. Does it give a location/file where it occurred? Is it talking about a particular method?
  - Go to the location and investigate the surrounding area
  - Google the error if the message is too confusing to give you a starting place

### Logical Errors

- The most difficult to fix
- Your program compiles and runs, but it behaves in an unexpected way
- You aren't getting the desired results
- Examples:
  - Click event not firing
  - Incorrect result (wrong number, or an undefined)
  - Strange behaviors
- Approach:
  - Go to where the desired behavior is supposed to be initiated
  - Check each subsequent step until the behavior is supposed to have happened.
