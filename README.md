# An example - relative import

First we add the path to the core folder to the PYTHONPATH environment variable so that the program can find the contents of the core in any location.

There are several ways to add PYTHONPATH. For example,

```shell
export PYTHONPATH="$PYTHONPATH:$(The/Project/Path)"
```

You can also wite a setup.py file to install your code as a package.



Then we can import the code in core folder anywhere in python code.

```python
>>> from core import Demo
>>> demo = Demo()
>>> demo()
I am demo.
```