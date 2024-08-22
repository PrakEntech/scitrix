# Matrix

> This module provides various matrix functions to facilitate matrix operations, including creation, manipulation, and advanced computations.

---

### Table of Contents

- [Description](#description)
- [Functions and Methods](#functions-and-methods)
- [Author Info](#author-info)

---

## Description

This module allows you to create matrices using 2D arrays (lists in Python) and perform complex operations such as calculating determinants, inverses, and matrix arithmetic. It aims to save time and provide consistency in matrix operations.

[Back To The Top](#matrix)

---

## Functions and Methods

### Class Methods

#### `__init__(self, r, c)`
Initializes the matrix with dimensions `r` x `c`, with all elements set to 0.

Example:
```python
obj = Matrix(3, 3)
```

#### `list(self)`
Returns the matrix as a 2-D list.

Example:
```python
lst99 = obj.list()
```

#### `inputAdd(self)`
Allows user input to modify the matrix elements.

Example:
```python
obj.inputAdd()
```

#### `listTomatrix(self, lst: list)`
Converts a list into a matrix (self.matrix).

Example:
```python
obj.listTomatrix([1, 2, 3, 4, 5, 6, 7, 8, 9])
```

#### `printMatrix(self)`
Prints the matrix using the Tabulate module.

Example:
```python
obj.printMatrix()
```

#### `transpose(self)`
Returns the transpose of the matrix.

Returns:
- `Matrix`

Example:
```python
obj2 = obj.transpose()
```

#### `sizeMatrix(self)`
Returns the dimensions of the matrix.

Returns:
- `Tuple`

Example:
```python
tuple1 = obj.sizeMatrix()
```

#### `matrixMultiplication(self, m2: Matrix)`
Multiplies the current matrix with another matrix `m2`.

Returns:
- `Matrix`

Example:
```python
obj3 = obj.matrixMultiplication(obj2)
```

#### `matrixAddition(self, m2: Matrix)`
Adds the current matrix to another matrix `m2`.

Returns:
- `Matrix`

Example:
```python
obj4 = obj.matrixAddition(obj2)
```

#### `matrixSubtraction(self, m2: Matrix)`
Subtracts matrix `m2` from the current matrix.

Returns:
- `Matrix`

Example:
```python
obj4 = obj.matrixSubtraction(obj2)
```

#### `matrixMultiplicationConstant(self, c: int or float)`
Multiplies the matrix by a constant `c`.

Example:
```python
obj.matrixMultiplicationConstant(5)
```

#### `adj(self)`
Returns the adjoint of the matrix.

Returns:
- `Matrix`

Example:
```python
obj5 = obj.adj()
```

#### `inverse(self)`
Returns the inverse of the matrix.

Returns:
- `Matrix`

Example:
```python
obj6 = obj.inverse()
```

#### `mean(self)`
Returns the mean of all elements in the matrix.

Returns:
- `Float`

Example:
```python
float1 = obj.mean()
```

#### `rowMeans(self)`
Returns the mean of each row in the matrix.

Returns:
- `Matrix`

Example:
```python
obj7 = obj.rowMeans()
```

#### `colMeans(self)`
Returns the mean of each column in the matrix.

Returns:
- `Matrix`

Example:
```python
obj8 = obj.colMeans()
```

#### `rowSum(self)`
Returns the sum of each row in the matrix.

Returns:
- `Matrix`

Example:
```python
obj9 = obj.rowSum()
```

#### `colSum(self)`
Returns the sum of each column in the matrix.

Returns:
- `Matrix`

Example:
```python
obj10 = obj.colSum()
```

#### `sum(self)`
Returns the sum of all elements in the matrix.

Returns:
- `Float` or `Int`

Example:
```python
var = obj.sum()
```

#### `matrixDivision(self, m2: Matrix)`
Divides the current matrix by the inverse of another matrix `m2`.

Returns:
- `Matrix`

Example:
```python
obj11 = obj.matrixDivision(obj2)
```

### Functions

#### `diag(m1: Matrix or List)`
Returns a diagonal matrix if `m1` is a list, or a list of diagonal elements if `m1` is a matrix.

Returns:
- `Matrix` or `List`

Example:
```python
list1 = diag(obj)  # if obj is a Matrix
obj12 = diag([1, 2, 3, 4, 5, 6])  # if [1, 2, 3, 4, 5, 6] is a list
```

#### `identity(m1: Matrix)`
Returns an identity matrix.

Example:
```python
obj13 = identity(obj)
```

#### `determinant(m1: Matrix)`
Returns the determinant of an `N x N` matrix.

Returns:
- `Float` or `Int`

Example:
```python
det12 = determinant(obj)
```

[Back To The Top](#matrix)

---

## Author Info

- Instagram: [prak_entech983](https://www.instagram.com/prak_entech983/)
- YouTube: [Prak EnTech](https://www.youtube.com/c/PrakEnTech)

[Back To The Top](#matrix)
