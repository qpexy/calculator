## Calculator
A Python 3 calculator used from the Terminal, built step by step in SCCM4910.
## What it will do
Add, subtract, multiply and divide two numbers; display the result.
## How to run it
Run: python3 calculator.py
Operations: + - * / (two numbers)
##testing
from calculator import add, subtract, multiply, divide

def test_add():
assert add(2, 3) == 5

def test_divide():
assert divide(6, 2) == 3

def test_subtract():
assert add(5, 3) == 2

def test_divide():
assert multiply(4, 3) == 12

def test_divide_uneven():
assert divide(5, 2) == 2.5

there should be 5 successfull tests when running text via ./check.sh highlighting that the program works as intended
