# the-matherator
Marked Programming Assignment 2 of the "C# Class Development" course of the "C# Programming for Unity Game Development" Specialization by the University of Colorado via Coursera

## Description

You're really excited about the four different kinds of methods we can have, so you want to implement all of them. Because you also recently learned about console app classes, you also want to put those methods into a separate class (instead of in the Program class).

In this assignment, you'll implement all four kinds of methods in a class.

Requirements

For this assignment, you need to implement a Matherator class that exposes the methods shown in the class diagram below:
* [Matherator class diagram](./matherator_class_diagram.png)

The Visual Studio project I provided to you contains the Matherator class (with the method bodies unimplemented) and a Program class that tests the Matherator class. You shouldn't change the Program.cs file at all (if you do, you'll break the automated grader), all your work in this assignment is in the Matherator.cs file.

You've probably noticed that these are the four kinds of methods we can have. Remember that you can call one method from another; you should do that as much as possible to avoid duplicating code.

The GetNthEvenNumber method gets the nth even number (based on the n parameter) and returns it. This method assumes 2 is the first even number. Note that this method doesn't print that number, it returns it from the method.

The GetTenthEvenNumber method gets the tenth even number and returns it. This method assumes 2 is the first even number. Note that this method doesn't print that number, it returns it from the method.

The PrintMToN method prints the numbers from m to n, inclusive, based on the m and n parameters.

The PrintOneToTen method prints the numbers from 1 to 10.

The best approach is to implement one of the Matherator methods, then test it by running the code, then move on to the next Matherator method, and so on. I implemented the methods in the following order: PrintOneToTen, PrintMToN, GetTenthEvenNumber, GetNthEvenNumber.  

Required Output Format

For the two Matherator methods that print (rather then return a value), print each value followed by a single space, then call the Console.Writeline method when you've printed all the values. For example, calling the PrintOneToTen method should yield the following output:

1 2 3 4 5 6 7 8 9 10 

Note: The last value in your output (10 for the example above) must be followed by a single space. Trust me, it’s easier that way, so the automated grader assumes you do that! The Program.cs file I provided makes sure your output from calling the methods that return a value is printed in the correct format.

We’d typically label our output to tell the user what those numbers are, but that will just confuse the automated grader. You must print ONLY in the format described above. For the two methods that return a value (rather than printing values), the Program.cs file I provided prints that values properly.

Running Your Code

Because of the code I included to work with the automated grader on Coursera, when you run your program the command prompt window will open and it will sit there doing nothing. To make your code run, type in 3 integers with a single space between each one and press the <Enter> key; your code should then run so you can check your output. 

You'll provide input using the following format:

<operation> <first argument <second argument>

The first input value tells what operation to perform: 1 for get the nth even number (where n is the value of the first argument), 2 for get the tenth even number (neither argument is used), 3 for print the numbers from m to n (where m is the first argument and n is the second argument), and 4 for print the numbers from 1 to 10 (neither argument is used).

The second and third input values are the arguments to use when calling the method for the selected operation. Only one of the methods requires both arguments, but it's easier for the automated grader to always process the same input format and just ignore the input values it doesn't need.

For example, your input could be

3 2 4

to print the numbers from 2, 3, and 4.

You can actually run your code again if you want to by typing in 3 integers with a single space between each one and pressing the <Enter> key again. When you’re ready to stop running your code, type q (for quit).

Here's what running the code multiple times with different inputs should look like. The first line is your input line with the operation and the two arguments, the second line is your output line, and so on:  

3 2 4

2 3 4 

2 0 0

20

q

## Getting Started

n/a

### Dependencies

* Windows 10
+ Microsoft Visual Studio

### Installing

* Download link: [Github Repository](https://github.com/lyndonpanton/the-matherator)

### Executing program

1. Go to the root directory
2. Open the _ProgrammingAssignment2_ directory
3. Open the _ProgrammingAssignment2.sln_ file in _Microsoft Visual Studio_
4. Run _Program.cs_ in _Microsoft Visual Studio_

## Help

n/a

## Authors

Lyndon Mykal Panton
[lyndonpanton](https://github.com/lyndonpanton/)

## Version History

* 0.1
    * Initial Release

## License

n/a

## Acknowledgments

n/a
