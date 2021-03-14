# Storing Information

### 1. Integers
- Represented as `int`.
- Can be stored between: **-9,223,372,036,854,775,808** and **9,223,372,036,854,775,808**
- Numeric Bases:
  - `bin()`: Base 2 : 0 and 1
  - `oct()`: Base 8 : 0 through 7, & : Base 10 : The usual number system
  - `hex()`: Base 16 : 0 through 9 , A through F

##### Example:
```
>>> myInt = 10
>>> print(myInt)
10
```
### 2. Float
- Represented as `float`.
- Can store immensely large or icredibly small values
- E.g. of float: 2.1, 2.111, 43.2, 70.0, etc.

##### Example:
```
>>> myFloat = 10.1
>>> print(myFloat)
10.1
```

### 3. Boolean Values
- **True** or **False**
- It consists of True or False value.
- This value checks the condition and according to that will give the result.

##### Example:
```
>>> myBool = 1>2
>>> print(myBool)
False
>>> myBool1 = 2<3
>>> print(myBool1)
True
```

### 4. String
- Normal English Sentence containing works, letters.
- It is declared (usually) within double quotes e.g `mySent = "This is a string."`

##### Example:
```
>>> mySent = "This is a string."
>>> print(mySent)
This is a string.
```
<hr>

## Checking the Data Type
Sometimes we often get confused in recognizing the data type of a variable and therefore we have a function which checks the data type of the particular variable.
To check the type of data-type we need to call `type()` function. [Don't worry, we will learn about function in later episodes]

##### Example:
```
>>> print(type(myInt)) #Integer
>>> print(type(myFloat)) #Float
>>> print(type(myBool)) #Boolean
>>> print(type(mySent)) #String
<class 'int'> 
<class 'float'>
<class 'bool'>
<class 'str'>

