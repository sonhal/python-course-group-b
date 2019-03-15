author: Sondre Halvorsen
id: nav-python-course
summary: This course is meant as an introduction to programming using Python
status: draft
feedback link:

# Learn Programing with Python!

## About this Course
Duration: 5:00

![Python Logo](resources/python-logo-generic.svg)

This course will walk you through the basic concepts of Programming using the Python programming language.


## Programming 1

Programming is simply the act of entering instructions for the computer to perform. These instructions might crunch some numbers, modify text, look up information in files, or communicate with other computers over the Internet.

A program is like a:
 - Cooking recipe
 - Ikea assembly manual

But for the computer!


## Programming 2

All programs, written in any language uses the same basic building blocks

Her are a few of the most common:
 - "Do this; Then do that"
 - "If this condition is true, perform this action; otherwise, do that action"
 - "Do this action that number of times"
 - "Keep doing that until this condition is true"



## Programming 3

For most people, their computer is just an appliance instead of a tool. But by learning how to program, you’ll gain access to one of the most powerful tools of the modern world, and you’ll have fun along the way. Programming isn’t brain surgery—it’s fine for amateurs to experiment and make mistakes.

### Python
Python is a clear and powerful object-oriented programming language, comparable to Perl, Ruby, Scheme, or Java.


Developed by Guido van Rossum



## Installation
Duration: 10:00

### Windows
 - Go to https://www.python.org/downloads/
 - Download the latest version of Python (as of this course being written: Python 3.7.2)
 - Run the installer
 - enable PATH
 ![Python Installer image](resources/python_win_install_checkbox.png)
 - click [Install now]

Test that Python is properly installed by running
```bash
python --version
```
in a CMD/Powershell shell.
In case of errors reference the - Using Python on Windows page: [link](https://docs.python.org/3/using/windows.html)

### Linux

Ubuntu
```bash
sudo apt-get update
sudo apt-get install python3.7
python3 --version
```

### Mac

On macOS, the best way to install Python 3 is to use Homebrew. Not familiar with homebrew? [link](https://brew.sh/)

```bash
brew install python3
```


## Table-Of-Contents
Duration: 1:00

 There are several tools installed with the Python interpeter. Here are some of them:


| Tool      | Description  |
| ------------- |:-------------:|
| python interpreter     | The python interpreter. The executable that can be called directly from the commandline/terminal to start a new interactive python session (REPL) or to run python modules/files/packages |
| pip     | The Python package manager. The official Python package manager. Lets the user download and manage third-party packages hosted on the Python package index (PyPI)      | 
| IDLE | IDLE is Python’s Integrated Development and Learning Environment. Its a Python IDE for and by Python | 
| pydoc| The pydoc module automatically generates documentation from Python modules. | 




## Development Tools

Python can be used and developed with using only a basic text editor and the python interpreter. But for larger and more complex projects there is a benefit to use porpouse built tools for Python development.


## Python a overview
Duration: 2:00


Objects are Python’s abstraction for data. All data in a Python program is represented by objects or by relations between objects.

 - Python is strongly typed and dynamically typed.

 - Python is a general porpouse progragramming language. It is not the best choice for time critical or memory constrained tasks.

 - Python is really a compiled programming language, but it acts as a interpred language.

 - There exist different implementation of Python. The most common, and the one we will use in this course is CPython.

 - Python comes with "Batteries included", meaning Python comes with a feature rich standard libary.



## Python 2 and Python 3
Duration: 1:00

Python has two main versions. Python 2 and Python 3. Python 3 is the newest, but it has struggeled with adoption for some time. Python 3 has as of 2018 taken the mantle as the main version from Python 2.

Practicly this means that new Python packages and application will in most cases be written in Python 3. 

### Python 2 end of life is january 1 2020.

![Python 2 to Python 3](resources/2_to_3.jpeg)


