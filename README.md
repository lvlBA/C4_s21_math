# s21_math  


Implementation of your own version of the math.h library.  

The russian version of the task can be found in the repository.

## Chapter I  

## Introduction

In this project you will develop your own version of the standard math.h library in the C programming language. This library implements basic mathematical operations, which are then used in various algorithms. As part of the project you will learn the basics of computational methods and solidify knowledge of structured programming.

## Chapter II

## Information

C mathematical operations are a group of functions in the standard library of the C programming language implementing basic mathematical functions. All functions use floating-point numbers in one manner or another. Different C standards provide different, albeit backwards-compatible, sets of functions. Any functions that operate on angles use radians as the unit of angle.

### Overview of some "math.h" functions

| No. | Function | Description |
| --- | -------- | ----------- |
| 1 | `int abs(int x)` | computes absolute value of an integer value |
| 2 | `long double acos(double x)` | computes arc cosine |
| 3 | `long double asin(double x)` | computes arc sine |
| 4 | `long double atan(double x)` | computes arc tangent |
| 5 | `long double ceil(double x)` | returns the nearest integer not less than the given value |
| 6 | `long double cos(double x)` | computes cosine |
| 7 | `long double exp(double x)` | returns e raised to the given power |
| 8 | `long double fabs(double x)` | computes absolute value of a floating-point value |
| 9 | `long double floor(double x)` | returns the nearest integer not greater than the given value |
| 10 | `long double fmod(double x, double y)` | remainder of the floating-point division operation |
| 11 | `long double log(double x)` | computes natural logarithm |
| 12 | `long double pow(double base, double exp)` | raises a number to the given power |
| 13 | `long double sin(double x)` | computes sine |
| 14 | `long double sqrt(double x)` | computes square root |
| 15 | `long double tan(double x)` | computes tangent |  


## Chapter III

## Part 1. Implementing the math.h library functions

The functions of the math.h library must be implemented (only those directly described [above](#overview-of-some-mathh-functions)):

- The library must be developed in C language of C11 standard using gcc compiler
- The library code must be located in the src folder on the develop branch
- Do not use outdated and legacy language constructions and library functions. Pay attention to the legacy and obsolete marks in the official documentation on the language and the libraries used. Use the POSIX.1-2017 standard.
- When writing code it is necessary to follow the Google style
- Make it as a static library (with the s21_math.h header file)
- The library must be developed according to the principles of structured programming; code duplication must be avoided
- Use prefix s21_ before each function
- Prepare full coverage of library functions code with unit-tests with the Check library  
- Unit-tests must check the results of your implementation by comparing them with the implementation of the standard math.h library
- Unit tests must cover at least 80% of each function (checked using gcov)
- Provide a Makefile for building the library and tests (with the targets all, clean, test, s21_math.a, gcov_report)
- The gcov_report target should generate a gcov report in the form of an html page. Unit tests must be run with gcov flags to do this  
- It is forbidden to copy the implementation of the standard math.h library and to use it anywhere, except unit-tests
- You must follow the logic of the standard library (in terms of checks, working with memory and behavior in emergency situations - tests will help you with that)
- The total verifiable accuracy is 16 significant digits
- Verifiable accuracy of the fractional part is up to 6 decimal places.
