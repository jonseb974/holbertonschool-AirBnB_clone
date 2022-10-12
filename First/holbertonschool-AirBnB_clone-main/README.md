# holbertonschool-AirBnB_clone
team repository
# JONAD Sébastien and THIAM Khady 
## AirBnB clone project

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)
* [cmd module](https://docs.python.org/3.4/library/cmd.html)
* [uuid module](https://docs.python.org/3.4/library/uuid.html)
* [datetime](https://docs.python.org/3.4/library/datetime.html)
* [unittest module](https://docs.python.org/3.4/library/unittest.html#module-unittest)
* [args/kwargs](https://yasoob.me/2013/08/04/args-and-kwargs-in-python-explained/)
* [Pyton test cheatsheets](https://www.pythonsheets.com/notes/python-tests.html)
- See 
- ✨Magic ✨

## General
    - How to create a Python package
    - How to create a command interpreter in Python using the cmd module
    - What is Unit testing and how to implement it in a large project
    - How to serialize and deserialize a Class
    - How to write and read a JSON file
    - How to manage datetime
    - What is an UUID
    - What is *args and how to use it
    - What is **kwargs and how to use it
    - How to handle named arguments in a function
    

# Tasks
## 0. README, AUTHORS

* Write a README.md:
    * description of the project
    * description of the command interpreter:
        * how to start it
        * how to use it
        * examples

* You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository. For format, reference Docker’s AUTHORS page
* You should use branches and pull requests on GitHub - it will help you as team to organize your work


## 1. Be pycodestyle compliant!
Write beautiful code that passes the pycodestyle checks.



## 2.  Unittests

Write a function that appends a string at the end of a text file (UTF8) and returns the number of characters added:



```
guillaume@ubuntu:~/AirBnB$ python3 -m unittest discover tests
...................................................................................
...................................................................................
.......................
----------------------------------------------------------------------
Ran 189 tests in 13.135s

OK
guillaume@ubuntu:~/AirBnB$ 
```
Note that this is just an example, the number of tests you create can be different from the above example.

### Warning:

Unit tests must also pass in non-interactive mode:
```
guillaume@ubuntu:~/AirBnB$ echo "python3 -m unittest discover tests" | bash
...................................................................................
...................................................................................
.......................
----------------------------------------------------------------------
Ran 189 tests in 13.135s

OK
guillaume@ubuntu:~/AirBnB$
```
