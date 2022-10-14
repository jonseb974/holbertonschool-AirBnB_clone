# AirBnB clone - The console

![This is a alt text.](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20221014%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20221014T115756Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=1b2ec24d209834f625960b3401d62423eaf603849a9eee75e5a2ca87a906e1d9)







## Lists

### Resources

* cmd module
* packages concept page
* uuid module
* datetime
* unittest module
* args/kwargs
* Python test cheatsheet

### Definition

 * #### cmd

The cmd class provides a simple framework for writingline-oriented command
writing line-oriented command interpreter.
The interpreter to manipulate data without a visual interface, like in a Shell, is useful for debugging, administrative tools,  proyotypes.

* #### Python packages

Python's file can be module
when the file is in a folder, it become a package


* ### uuid

Is an inbuilt python function and stands for Universal Unique Identifier.
It provides the uniqueness as it generates ids on the basis of time.
UUID, can be used as general utility to generate unique random id, also in cryptography, hashing applications and to generate random documents.

* ### datetime

The datetime module is used to work with dates and times. It is include in the python library.
```

import datetime

d = datetime.date(2019, 4, 13)
print(d)
```
#### The output will look like this:
```
2019-04-13
```

* #### Unittest module

Unit testing framework was inspired by JUnit.

In python unittest is a built-in framework used for testing program.
And helps saving time for debugging process.

```
python -m unittest test_filename.py.
```
#### Example test case self.assertFalse(utils.is_prime(1)).
```
import unittest

import utils


class TestUtils(unittest.TestCase):
    def test_is_prime(self):
        self.assertFalse(utils.is_prime(4))
        self.assertTrue(utils.is_prime(2))
        self.assertTrue(utils.is_prime(3))
        self.assertFalse(utils.is_prime(8))
        self.assertFalse(utils.is_prime(10))
        self.assertTrue(utils.is_prime(7))
        self.assertEqual(utils.is_prime(-3),
                         "Negative numbers are not allowed")


if __name__ == '__main__':
    unittest.main()
```

 * ### args/kwargs

##### *args(Non-Keyword Arguments)

In python is used to pass a variable number of arguments to a function.
```
def myFun(*argv):
    for arg in argv:
        print(arg)


myFun('Hello', 'Welcome', 'to', 'GeeksforGeeks')
```
##### Output:
```
Hello
Welcome
to
GeeksforGeeks
```


##### **Kwargs(keyword Arguments)
In python is used to pass a keyword or variable-length argument list.
The double stars allows to pass keyword arguments.

```
def myFun(**kwargs):
    for key, value in kwargs.items():
        print("%s == %s" % (key, value))


# Driver code
myFun(first='Geeks', mid='for', last='Geeks')
```
##### Output:
```
first == Geeks

mid == for

last == Geeks
```

## Requirements
### Python Scripts
* Allowed editors: vi, vim, emacs
* All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
* All your files should end with a new line
* The first line of all your files should be exactly #!/usr/bin/python3
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should use the pycodestyle (version 2.7.*)
* All your files must be executable
* The length of your files will be tested using wc
* All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
* All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
* All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
* A documentation is not a simple word, it’s a real sentence explaining * what’s the purpose of the module, class or method (the length of it will be verified)





## The console

We have to create a console like in the shell project with two mode: an interactive mode, and a non-interactive mode.

#### Interactive mode:
The interactive mode is a command line shell which gives immediate feedback for each statement.So as we enter a command and press enter we get an output.
```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
```
#### Non-Interactive mode:
The non-interactive mode we have to specify the path, by doing so we give all instruction to the build with a command explicitly.

```
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
```
An other way to quit the console mode is shortcut:
```
 Ctrl + D
```


### Methods and functions

* #### super()
super() is a function used too give access to methods an properties of a parent or dsibling class.

* #### isoformat()
This function is used to return a string of date, time, respecting the time zone in ISO 8601 format standard.


* #### save()
Save() methode is used to save an array to a binary file in Numpy.npy

* #### all()
This function returns True if all items in an iterable are True, else False is returns.
If iterable object is empty, all() returns True.


* #### strptime()
This python function return a formated string representation of date and time.It takes as parameterdate, time, or both parses it. A ValueError can be raised if the string cannot be formatted.
