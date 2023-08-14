# C++ Command Line Calculator

This is an extremely simple calculator I made while relearning C++.

Download the repo, compile and run it:

```
$git clone https://github.com/paynekerz/CPPCalculator
$cd cpp-calculator
$make
```

It has two modes, regular and scientific, that a user can switch between.

### Overview

The program has 2 classes. A simple calculator class called Calculator, and a class that inherits Calculator called Scientific.

Some member functions of Calculator are virtual and are overridden in the Scientific class.

The program flow is:

1. Prompt user for the desired operation (polymorphically determine the message based on the current mode; show more options while in scientific mode)
2. Get additional data from the user (if doing addition, get 2 numbers)
3. Perform calculation, print to screen
4. Repeat from (1)
