## Recitation 1

### Intro to Python
* **Anaconda** is a Python distribution, which contain Python, a set of Python packages, a code editor (**Spyder**), and an interactive interpreter/shell (**IPython**)
* Spyder: Scientific Python Development Environment
  * A place to edit code, run it, and debug it
* We encourage this dev environment for this class
* **Make sure you run your code before you turn it in**

### Lecture 1 Recap: Intro to Python + Fundamental Programmming Concepts
* **Python programs**
  * Set of instructions telling the computer exactly what to do.
  * Can be run from a script (e.g. script1.py) or directly from the console
  * Each line of code is executed in the order it's written in.
  * It's good practice to write tidy code & comments

* **Objects**
  * Programs manipulate data objects.
  * Typically define an object with a variable name (e.g. my_name = "Nicole")
  * Each object has a type (e.g. string, list, integer, float, boolean, etc...)
  * Scalar objects cannot be subdivided.
  * Non-scalar objects have an internal structure that can be assessed.
  * The type defines what you can do with the object

* **Operations & Expressions**
  * Operations are carried out on objects (what operations are valid is controlled by object type)
  * Expressions are formed by a combination of operations and objects.
  * Complex & long expressions often evaluate to one value.

### Example Code

```py
# declaring a simple string
basic_string = "My name is Nicole!"

# intergers and simple operations
a = 1
b = 20
sum_ab = a + b
difference_ab = b - a

# example operations on integers and strings
my_numbers_as_string = str(9) + ' ' + str(10) + ' ' + str(7)
```