# Float
Custom floating-point library that is able to handle arbitrary precision with no precision lose.

# Installation instructions
Download the Float.py into <Python executable folder>\Lib\

# Use
To use this library you just import it like any other library. e.g.
```
>>> import Float
>>> num = Float.Float(2.1)
>>> num
Float((-1, 21, 1))
>>> float(num)
2.1
```

Alternatively you can use
```
>>> from Float import Float
>>> num = Float(2.1)
>>> num
Float((-1,21,1))
```

The Float class can take different types of inputs:
- Float class
- tuple of length 3
- string representation of a number
- floating point number
- integer

# License
The use of this library is free. However, whenever you use this, you must acknowledge Matthew Richards as the creator.
