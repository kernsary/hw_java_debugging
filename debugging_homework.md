# Introduction to Debugging in IDE

## Learning Objectives
- Know how to debug a Java application
- Understand breakpoints
- Understand the debugger console
- Know how to evaluate code fragments

## Task
As an introduction to debugging:
- watch the following video: [Intro to Debugging video](https://youtu.be/ErVZrVWZrko)


Answer the following questions:
1. What is the purpose of a breakpoint?

A breakpoint makes the program stop running when it gets to the line that you mark, so that you can see the values of variables etc at that point.

2. Does the line of code on a breakpoint run when you start debugging?

No.

3. How do we debug the next line of code?

We use the 'step over' command to move on to the next line of code.

4. What does the step into command do?

It takes you to the first line of code that is referenced in the line you are on, eg if the line you are on calls a function, it will take you to the start of that function, even if it is a separate class. Then you can see the value of variables etc at that point.

5. What is the difference between evaluate expression and evaluate code fragment?

Evaluate expression evaluates a single line of code. Evaluate code fragment allows you to write several lines of code, including setting temporary variables, and see what happens when you run that code.
