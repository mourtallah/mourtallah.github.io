![Girl Develop It Logo](../images/gdi_logo_badge.png)

###Intro to Python
####Section 1
@@@


## Welcome to GDI!
Girl Develop It is here to provide affordable and accessible programs to learn software through mentorship and hands-on instruction.

Our Central Tenets: 

* We are here for you. <!-- .element: class="fragment" -->
* Every question is important! <!-- .element: class="fragment" -->
* We are here to help each other. <!-- .element: class="fragment" -->
* Have fun! <!-- .element: class="fragment" -->
@@@

###What we will cover today: 

* What is programming? <!-- .element: class="fragment" --> 
* Why Python? <!-- .element: class="fragment" -->
* Who uses Python? <!-- .element: class="fragment" -->
* Development Vocabulary : Terminals, Shells & Text Editors. <!-- .element: class="fragment" -->
* Terminal Basics : Files & Directories. <!-- .element: class="fragment" -->
* Python Basics: Variable Assignment, Data Types, Functions and Errors. <!-- .element: class="fragment" -->
* Let's Develop It! : A simple program that calculates the area of a circle given it's radius. <!-- .element: class="fragment" -->
@@@

##What is programming?</h3>
@@@

<p> Designing and building executable instructions for that instructs a computer to accomplish a specific task. </p>  <!-- .element: class="fragment" --> 

<p> Programming code is human readable whereas computers only understand zero's and one's! </p> <!-- .element: class="fragment" --> 

<p> Intepreters and compilers do the work of converting our human readable instructions to binary machine code. </p>  <!-- .element: class="fragment" --> 
@@@

###Compilers in Action</h3>
<img src="../images/1000px-Compiler_Shematic.png">
@@@


## Why Python?
@@@

#### VERY (VERY) Popular
* A great place to start!
* Suitable for beginners, yet used by professionals. <!-- .element: class="fragment" -->

<img src="../images/Top-Companies-using-Python-01.jpg"> <!-- .element: class="fragment" -->

@@@

#### VERY ROBUST: DEEP YET FLEXIBLE 
* Easy to learn, practically impossible to master. <!-- .element: class="fragment" -->
<img src="../images/popular-programming-language.jpg"> <!-- .element: class="fragment" -->
@@@

#### GROWING VERY FAST 
* Variety of applications. <!-- .element: class="fragment" -->
* Rapid rate of development. <!-- .element: class="fragment" -->
* Readable, maintainable code. <!-- .element: class="fragment" -->
<img src="../images/python-programming.png" height=500px width=800px> <!-- .element: class="fragment" -->
@@@

##Who uses Python
@@@

###System Administrators <!-- .element: class="fragment" -->
Responsible for the day to day management and operations of computer systems, networks, cloud infrastructures, data communications and security. <!-- .element: class="fragment" -->

Notable Packages : Fabric, Salt, Ansible  <!-- .element: class="fragment" -->
@@@

###Graphic Designers and Animators <!-- .element: class="fragment" -->
Specialize in the the creation of special effects and animations for websites, advertisements, movies, video games and more.  <!-- .element: class="fragment" -->

* Notable Packages : Maya, Blender, Gimp. <!-- .element: class="fragment" -->
@@@

###Data Scientists and Statisticians <!-- .element: class="fragment" -->
Analysts and scientists who specialize in the Derivation of insights, descriptive or predictivce models from data for inference or artificial intelligence applications. <!-- .element: class="fragment" -->

* Notable Packages : Numpy, SciPy, Pandas, SciKitLearn. <!-- .element: class="fragment" -->
@@@

###Web Developers <!-- .element: class="fragment" -->
Design and create websites and web applications and specify it's structure and functionality including its layout, transitions, performance and operations. <!-- .element: class="fragment" -->

* Notable Packages : Django, Flask, Selenium. <!-- .element: class="fragment" -->
@@@


###Game Developers <!-- .element: class="fragment" -->
Developers who specialize in the creation of interactive digital gaming experiences on consoles, mobile or PC. <!-- .element: class="fragment" -->

* Notable Packages : Civilization 4, EVE Online. <!-- .element: class="fragment" -->
@@@

##Development Vocabulary
@@@

#### Command line, Python Shell, Text Editors
Term      | Description
-------------|----------
Terminal Shell | A program that has a command line interface and issues commands to the operating system. 
Python Shell | A command line program that runs inside of the terminal, takes Python code as input, interprets it, and prints out any results. 
Text Editor  | A program that opens text files and allows the user to edit and save them. 
@@@


##Terminal Basics
@@@

###Commands

Command         | Short for               | Description
----------------|-------------------------|-------------
pwd             | Print working directory | Displays what folder you are in
ls              | List                    | Displays the files and folders in the current folder
cd <folder>     | Change Directory        | Change to another folder, where <folder> is the target
cat <filename>  | Concatenate             | Prints the contents of the file
mkdir <folder>  | Make directory          | Creates a new directory
touch <filename>| --					  | Create a new file in current directory
@@@

### Exercise Preview
($ shows the shell prompt where commands are entered. Lines without $ are output)
```bash
$ ls
main.py
$ pwd
~/home/runner/Intro_to_Python
$ mkdir smf
$ ls
main.py smf
$ cd smf
$ pwd
~/home/runner/Intro_to_Python/smf
$ ls
$ touch mourtallah.txt
$ ls
mourtallah.txt
```
@@@


## Python Basics

* Feel free to explore as well. You will not accidentally break things <!-- .element class="fragment" -->
* $ means you are in the terminal (not python). >>> means you are in python <!-- .element class="fragment" -->
* Type exit() to leave python and return to the terminal. <!-- .element class="fragment" -->
@@@

### Data Types

Everything in Python is an object, and every object has a type. <!-- .element class="fragment" -->
#### Numeric : int, float <!-- .element class="fragment" -->
int: 1, 7, 9000 <!-- .element class="fragment" -->
float: 1.0, 3.1415926536, 9000.5 <!-- .element class="fragment" -->
<br>
#### Text <!-- .element class="fragment" -->
str: "abx", "?", "It's over 9000!","9000" <!-- .element class="fragment" -->
@@@

### Functions <!-- .element class="fragment" -->
* Code that we call on by it's name to complete a particular task. <!-- .element class="fragment" -->
* Distinguished by parenthesis. <!-- .element class="fragment" -->
* type(): accepts a object and returns its type. <!-- .element class="fragment" -->
* str() : converts input to type string. <!-- .element class="fragment" -->
* int() : converts input to type int. <!-- .element class="fragment" -->
* float() : converts input to type float. <!-- .element class="fragment" -->
* print() : prints input to screen. <!-- .element class="fragment" -->
* input() : takes a prompt as input and pauses program to accept input from user <!-- .element class="fragment" -->
@@@


### Variables and Assignment 
* Python assignment is done with "=".
* Python evaluates code on the right hand side and saves the output to the variable on the left hand side.
* Variables can be overwritten! 

```python
>>> a = 2
>>> print a
2
>>> b = 3
>>> c = a + b
>>> print c
5
```
```python
>>> a = 0
>>> a = a + .5
>>> print a
0.5
```
@@@

### Arithmetic 
```python
>>> 3 + 4
7
>>> 2 * 4
8
>>> 6 - 2
4
>>> 4 / 2
2
>>> 3 ** 2
9
```
@@@


###Strings
```python
>>> a = 'Hello '
>>> b = 'World'
>>> c = a + b
>>> print c
'Hello World'
```

```python
>>> a = "Spam "
>>> b = a * 4
>>> print b
"Spam Spam Spam Spam"
```
@@@

### Importance of Data Types
* Functions and commands may behave differently or "break" if given the wrong data type.

```python
>>> a = "3"
>>> b = 3 
>>> a + a
'33'
>>> b + b
6 
```

```python
>>> a = "3"
>>> b = 3
>>> a * 5
"33333"
>>> b * 5
15
```

```python
>>> print "a" * "5"
# Traceback (most recent call last):
#  File "<stdin>", line 1, in <module>
# TypeError: can't multiply sequence by non-int of type 'str'
```
@@@

###Errors

* There are different kinds of errors that can occur. We've seen one so far. <!-- .element class="fragment" -->
* A runtime error results in an Exception. An Exception gives us some information about the nature of the error and how to correct it <!-- .element class="fragment" -->
* One type of exception is a SyntaxError. This results when our code can not be evaluated because it is incorrect at a syntactic level. In other words, we are not following the "rules" of the language. <!-- .element class="fragment" -->
* Some other examples are the TypeError and NameError exceptions. <!-- .element class="fragment" -->
@@@

###Errors - continued ...

* A \# is a code comment. These are not evaluated by Python

```python
# SyntaxError - Doesn't conform to the rules of Python.
# This statement isn't meaningful to the computer
>>> 4spam)eggs(garbage) + 10

# NameError - Using a name that hasn't been defined yet.
>>> a = 5
>>> print b

# TypeError - Using an object in a way that its type does not support
>>> 'string1' / 'string2'
```
@@@

###Exercise Preview
```python
print("Welcome to Mourtallah's Area Calculator!")
input_value = input("Enter a radius:")
radius = float(input_value)
area = 3.14159 * radius ** 2
print("The area of a circle with radius", input_value, "is", area)
```

## Let's Develop It!
@@@

###Let's Develop It
* We'll practice what we've learned by: <!-- .element class="fragment" -->
*	navigating through the shell <!-- .element class="fragment" -->
* creating a folder in the terminal shell. <!-- .element class="fragment" -->
*	creating a file in that folder. <!-- .element class="fragment" -->
* writing a python program that prompts the user for the radius of a circle, calculates and returns the corresponding area. <!-- .element class="fragment" -->
* Hint : the input function returns a string object! <!-- .element class="fragment" -->	
* Ask the teacher or a TA for any help <!-- .element class="fragment" -->
@@@

###Let's Develop It!
<img src="../images/drake.png" height=600px>
@@@

###Enter Repl.it
<img src="../images/replithomepage2.png" height=600px width=1000px>
@@@

###Why Repl.it?
####* Saves time! <!-- .element: class="fragment" -->
####* Multiplayer means working together! <!-- .element: class="fragment" -->
####* Will come in handy later! <!-- .element: class="fragment" -->
@@@

### Setting Up Repl.it
* Open your browser of choice and Go to Repl.it. <!-- .element: class="fragment" -->
* Click Sign-Up in the upper right corner. <!-- .element: class="fragment" -->
* Create an account using Google, Facebook or Github authorization, or with email and username. <!-- .element: class="fragment" -->
* Complete the intro flow. <!-- .element: class="fragment" -->
* Breakout!  <!-- .element: class="fragment" -->
@@@


###Questions?
