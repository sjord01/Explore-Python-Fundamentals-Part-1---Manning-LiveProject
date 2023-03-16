# Explore Python Fundamentals-Part 1: Manning-LiveProject

The series of projects work out Python skills and form sound mental models of fundamental aspects of Python.

## Project 1: Variables
[1.1. Explore the Problem with Immutable vs. Mutable Objects](https://github.com/sjord01/Explore-Python-Fundamentals-Part-1-Manning-LiveProject/blob/main/1.1%20Explore%20the%20Problem%20with%20Immutable%20vs.%20Mutable%20Objects.ipynb)
- Explore the characteristics of Python variables by examining what happens when re-assigning a value or changing an element/s in lists or arrays.

[1.2. Test Hypotheses - Are Variables Containers or Labels](https://github.com/sjord01/Explore-Python-Fundamentals-Part-1-Manning-LiveProject/blob/main/1.2%20Test%20Hypotheses%20-%20Are%20Variables%20Containers%20or%20Labels.ipynb)
- Python's built-in function id() returns an object’s integer identifier; it helps in understanding the nature of Python variables and debugging codes,

## Project 2: Objects & Methods
[2.1 Creating class using the 'type()' function](https://github.com/sjord01/Explore-Python-Fundamentals-Part-1-Manning-LiveProject/blob/main/2.1%20Creating%20a%20Class%20using%20the%20'type(%20)'%20function.ipynb)
- Aside from Python's conventional way of constructing class objects, the 'type()' function offers an alternative of creating dynamic classes.

[2.2 Exploring Objects and Instance Methods](https://github.com/sjord01/Explore-Python-Fundamentals-Part-1-Manning-LiveProject/blob/main/2.2%20Workflow%20-%20Exploring%20Objects%20and%20Instance%20Methods.ipynb)
- In object-oriented programming, a class is a custom-designed plan or model that serves as a basis for generating objects. Classes allow for the combination of data and functionality into a single entity. When a new class is established, it produces a new kind of object, enabling the creation of new instances of that type. Each instance of a class can possess properties that are associated with it to keep track of its condition. Furthermore, class instances can possess methods (specified by their class) for altering their state.

## Project 3: Class Methods & Variable

[3.1 Class Data](https://github.com/sjord01/Explore-Python-Fundamentals-Part-1-Manning-LiveProject/blob/main/3.1%20Workflow%20-%20Class%20Data-Copy1.ipynb)
- Explore about classes, attributes, and methods in Python, and how they can be used to define and manipulate objects in an OOP context.
- Leverage the benefit of using a mutable object (a list) as an attribute, instead of a scalar value, to  keep track of data across multiple instances of a class.

[3.2 Class Method](https://github.com/sjord01/Explore-Python-Fundamentals-Part-1-Manning-LiveProject/blob/main/3.2%20Workflow%20-%20Class%20Methods.ipynb)
- Scripting a Python code of classes should take into considerations what the program is about and its main purpose, its readability and maintainability, the possibility of it being scaled up in the future; these principle set the way of your class data will be accessed.
- If you need to access class-level data from within an instance, the __class__ property or @classmethod decorator might be the best choice. If you only need to access class-level data from outside the class, using the class itself might be the simplest and most efficient approach.

## Project 4: Inheritance

[4.1 Inheriting from Another Class](https://github.com/sjord01/Explore-Python-Fundamentals-Part-1-Manning-LiveProject/blob/main/4.1%20Workflow%20-%20Inheriting%20from%20Another%20Class.ipynb)
- Implementing proper inheritance in Python through creating a more organized and maintainable codebase by avoiding code duplication and reusing code from parent classes in our subclasses.

[4.2 Inheriting from More than One Class at Once - Mixins](https://github.com/sjord01/Explore-Python-Fundamentals-Part-1-Manning-LiveProject/blob/main/4.2%20Workflow%20-%20Inheriting%20from%20More%20than%20One%20Class%20Once%20-%20Mixins.ipynb)
- The code and examples demonstrate how mixins can be used to create reusable functionality that can be easily combined with other classes to create new classes with different behaviors. By separating the functionality into mixins, we can avoid repeating code and simplify the class hierarchy.


## Project 5: Iteration

[5.1 Iteration Protocol and Creating an Iterable](https://github.com/sjord01/Explore-Python-Fundamentals-Part-1-Manning-LiveProject/blob/main/5.1%20Iteration%20Protocol%20and%20Creating%20an%20Iterable.ipynb)

5.2 Creating an Iterator and Using a Generator Function
- When working with iterators and generators, it's important to be aware of the differences between the two approaches, and to choose the one that best fits your needs. If you need fine-grained control over the iteration process, or if you need to implement complex stateful behavior, then iterators may be the better choice. If you need a simple way to produce a sequence of values, or if you need to produce a very large sequence that won't fit in memory, then generators may be the better choice.

- Iterators and generators work in conjunction with for loops and can be used to create custom iterator and generator classes and functions. Overall, iterators and generators are powerful tools for working with sequences of values in Python, and can be used in a wide variety of applications.
