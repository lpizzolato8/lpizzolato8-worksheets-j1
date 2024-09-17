## Worksheet J1

Question: What is fault localization?

**Fault localization is the act of debugging** and back tracing through code to 
locate errors that damage/stop the code from functioning in the way that 
the coder wants it to.
 
Question: What are three benefits of Test Driven Development (TDD)? 
* Your tests are not biased by your code
* Writing tests helps you think about how you might write code
* Writing tests helps you think about the requirements of your system

Question: What are the input domain paritions for this exercise?
*  Only letters, numbers, and a single underscore
*  There must not be an @ symbol or anything that resembles an email address
*  At least 1 number, 1 lowercase, and 1 uppercase
*  At least 4 "characters" including the underscore

Question: Complete truth table for the following function
if ( ( (a > b) or G ) and (x < y) )

| a | b | a>b | x | y |
|---|---|---|---|---|
| T |   |   |   |   |
| T |   |   |   |   |
| T |   |   |   |   |
| T |   |   |   |   |
| F |   |   |   |   |
| F |   |   |   |   |
| F |   |   |   |   |
| F |   |   |   |   |

Consider the control flow graph below. What are all the paths (using node numbers) that would achieve full path coverage as a test criteria? Is this a finite set?
```ruby
12567,1257,13567,1357,134357,1343567
yes this is a finite set
``` 

Question: What benefit does mutation testing offer over other testing methods discussed in class?
Assume the current version of the code is “correct,” and then seed faults into that code base and re-run the test suite. A good test suite will now have at least one test case fail for such a seeded fault. Otherwise, it didn’t do a good enough job of testing the code.
[Dr.Kinga Dobolyi Software Engineering Notes]https://cs2113-f24.github.io/j/software_testing
