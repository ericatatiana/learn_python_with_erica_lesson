# 🐍 Day 4 — Operators

Welcome to Day 4 of **Learn Python with Erica — 30 Days** 

Today we will learn about operators in Python.

Operators are used to perform calculations and comparisons.

---

#  Arithmetic Operators

Arithmetic operators are used in mathematical operations.

| Operator | Meaning        | Example  |
| -------- | -------------- | -------- |
| `+`      | Addition       | `5 + 2`  |
| `-`      | Subtraction    | `5 - 2`  |
| `*`      | Multiplication | `5 * 2`  |
| `/`      | Division       | `5 / 2`  |
| `//`     | Floor Division | `5 // 2` |
| `%`      | Modulus        | `5 % 2`  |
| `**`     | Power          | `5 ** 2` |

---

#  Example

```python id="qfnd6f"
a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
```

---

#  Output

```python id="q3q4m8"
13
7
30
3.3333333333333335
```

---

#  Modulus Operator

The modulus operator `%` returns the remainder.

##  Example

```python id="u4m6kg"
print(10 % 3)
```

---

#  Output

```python id="f5j1gl"
1
```

---

#  Power Operator

The power operator `**` is used for exponents.

##  Example

```python id="v5z8i2"
print(2 ** 3)
```

---

#  Output

```python id="5x7u0y"
8
```

---

#  Comparison Operators

Comparison operators compare values.

| Operator | Meaning          |
| -------- | ---------------- |
| `==`     | Equal            |
| `!=`     | Not Equal        |
| `>`      | Greater Than     |
| `<`      | Less Than        |
| `>=`     | Greater or Equal |
| `<=`     | Less or Equal    |

---

#  Example

```python id="3w5u0n"
x = 10
y = 5

print(x > y)
print(x == y)
print(x != y)
```

---

#  Output

```python id="4y7xme"
True
False
True
```

---

#  Logical Operators

Logical operators are used with conditions.

| Operator | Meaning                      |
| -------- | ---------------------------- |
| `and`    | Both conditions must be true |
| `or`     | One condition must be true   |
| `not`    | Reverses the result          |

---

#  Example

```python id="5j0qcn"
age = 20

print(age > 18 and age < 30)
```

---

#  Output

```python id="n5i79k"
True
```

---

#  Exercise

Create two variables:

* `num1`
* `num2`

Then:

* add them
* subtract them
* multiply them

Display all results.

---

#  Challenge

Ask the user for two numbers and display:

* addition
* subtraction
* multiplication
* division

Example:

```python id="dz3o1k"
Enter first number: 10
Enter second number: 2

Addition: 12
Subtraction: 8
Multiplication: 20
Division: 5
```

---

#  Note

Operators are essential in programming because they allow programs to calculate, compare and make decisions 
