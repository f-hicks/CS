## Variables
Without variables, we would need to rewrite values everywhere.
Variables give names to data, making programs flexible and reusable.

A variable is a **named storage** for a value.
![[Pasted image 20251003161059.png]]
Like a labelled box, it stores a value. 

## Creating variables
- first assignment will declare and initialise the value
	- it cannot be used before declaration
- Python is **dynamically typed**
	- you don't need to declare types
	- a variable's type can change
- naming principles
	- variable names are identifiers
	- can contain _ , letters and digits.
	- CANNOT start with digits
	- case-sensitive (Name $\neq$ name)
	- cannot use python keywords (if, for, class)

### Variables
- a name that refers to a value
- can change during program execution
```python
myValue = 20
myValue = 21
```

Literals
- a fixed value written directly in the code
- do not change (unless replaced in code)
- e.g. 20 (integer literal), "Hello" (string literal)
```python
20
"Hello"
```

## Data Types

Not all information in real life is the same
- Age is a number
- price of an item is a decimal
- a person's name is text
- a yes/no answer is a truth value
Python provides different data types to handle different kinds of information.
- int
- str
- bool
- float

### Integer
Python integers can be arbitrary large, limited only by the size of memory
In other languages, they often use either 32 or 64 bit integers
- need to be careful about overflows.

Operators:

| +: Addition                | -: Subtraction       | *: Multiplication |
| -------------------------- | -------------------- | ----------------- |
| /: Division                | //: Integer division | %: modulo         |
| **: Exponentiation (power) |                      |                   |

### Float
float represents floating-point numbers
- looks like decimal numbers

Operators
- +: Addition
- -: Subtraction
- *: Multiplication
- /: Division
- **: Exponentiation (power)

Computers store numbers in binary with limited precision
many decimals (like 0.1, 0.2) cannot be represented exactly
The computer stores a close approximation, which sometimes leads to tiny errors
```python
>>> 5/3
1.6666666666666667
>>> 0.1+0.2
0.30000000000000004
```

### String

sequence of characters
operators:
- +: Concatenation

Literals
- Double-quoted: "Hello, World!"
- Single-quoted: 'Hello, World!'
	- useful when " is part of the string"

### Boolean
The bool datatype has only two values, **True** and **False**
operators **and**, **or**, **not**
- a and b is True if and only if both a and b is True
- a or b is False if and only if both a and b is False
- not a is True if and only if a is False


## Type checking
use `type()` to check a variable's type.
`type(x)` will return the type of `x`
```python
>>> age = 20
>>> type(age)
<class 'int'>
```

`type(<expression>)` will return the type of the expression
- expressions are combinators of variables, literals, and operators
```python
>>> age = 20
>>> type(age>18)
<class 'bool'>
```


There is a static type checker for python called `mypy`.
- helps find type errors before running the code
- type annotation, e.g., 
```python 
x:int = 4
```
- ignored by Python interpreter
- `mypy <your python script>`
- helps prevent mistakes early
