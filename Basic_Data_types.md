### Question 1: 

Consider two integers, `a` and `b`:

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print("YES" * (a % b == 0) + "NO" * (a % b != 0))
```

What will this code print?

- **A)** The sum of `a` and `b` if `a` is a multiple of `b`.
- **B)** `"YES"` if `a` is a multiple of `b`, otherwise `"NO"`.
- **C)** A boolean value `True` if `a` is a multiple of `b`, otherwise `False`.
- **D)** The remainder of `a` divided by `b`.
- **E)** `"NO"` in all cases.

**Your Answer:** Enter your answer on the Google Form.

---

### Question 2:

Given two lowercase letters, `letter1` and `letter2`:

```python
letter1 = input("Enter first letter: ").lower()
letter2 = input("Enter second letter: ").lower()

print("FIRST" * (ord(letter1) < ord(letter2)) + "SECOND" * (ord(letter1) > ord(letter2)) + "EQUAL" * (ord(letter1) == ord(letter2)))
```

What does this code accomplish?

- **A)** It converts both letters to lowercase and checks if they are equal.
- **B)** It determines which letter comes first in the alphabet, prints `"FIRST"` if `letter1` does, `"SECOND"` if `letter2` does, or `"EQUAL"` if they are the same.
- **C)** It prints the ASCII values of both letters.
- **D)** It always prints `"EQUAL"` regardless of the letters' order.
- **E)** It concatenates the two letters and prints them.

**Your Answer:** Enter your answer on the Google Form.

---

### Question 3:


Consider the following Python code that determines the maximum value between two inputs, `a` and `b`, without using explicit conditional statements:

```python
a = int(input())
b = int(input())

value = a * (a > b) + b * (b >= a)
print(value)
```

What is the purpose of this code?

- **A)** It calculates the sum of `a` and `b`.
- **B)** It multiplies `a` and `b` based on their comparison results.
- **C)** It determines the maximum value between `a` and `b` and prints it.
- **D)** It always prints the value of `b`.
- **E)** It creates a boolean value indicating if `a` is greater than `b`.

**Your Answer:** Enter your answer on the Google Form.

---

### Question 4:


Consider the following Python code:

```python
# Enter a 3 digit number
number = int(input("Enter a 3 digit number: "))

# Extracting the digits
a = number // 100
b = (number % 100) // 10
c = number % 10

print(a + b + c)
```

Given this code, which pair of three-digit numbers would produce the highest and lowest possible sums of their digits?

- **A)** Highest: 999, Lowest: 001
- **B)** Highest: 999, Lowest: 111
- **C)** Highest: 900, Lowest: 100
- **D)** Highest: 999, Lowest: 990
- **E)** Highest: 27, Lowest: 1


**Your Answer:** Enter your answer on the Google Form.


---

### Question 5:


Consider the following Python code:

```python

var_1 = "Hello"
var_2 = 10
var_3 = 3.14
var_4 = True

print(bool(var_1))
print(bool(var_2))
print(bool(var_3))
print(bool(var_4))
print(bool(var_1) + bool(var_2) + bool(var_3) + bool(var_4))
```

What will this code print?

- **A)** `True`, `True`, `True`, `True`, `4`
- **B)** `True`, `True`, `True`, `True`, `1`
- **C)** `True`, `True`, `True`, `True`, `0`
- **D)** `True`, `True`, `True`, `True`, `3`
- **E)** `False`, `False`, `False`, `True`, `0`

**Your Answer:** Enter your answer on the Google Form.

---

### Question 6:

Given the following Python code:

```python

a = 10
b = 10.0
c = "10"

print(a == b)
print(b == c)
print(a == c)
```

What will this code print?

- **A)** `True`, `True`, `True`
- **B)** `True`, `False`, `False`
- **C)** `False`, `False`, `False`
- **D)** `True`, `True`, `False`
- **E)** `False`, `True`, `False`

**Your Answer:** Enter your answer on the Google Form.

---

### Question 7:

Consider the following Python code:

```python

x = 10
y = x

x = 20

print(x)
print(y)
print(x + y)
```

What will this code print?

- **A)** `20`, `10`, `30`
- **B)** `20`, `20`, `40`
- **C)** `10`, `20`, `30`
- **D)** `10`, `10`, `20`
- **E)** `20`, `10`, `20`


**Your Answer:** Enter your answer on the Google Form.

---

### Question 8:

Consider the following Python code:

```python

a = 4253

print(a % 10)
print(a % 100 // 10)
print(a % 1000 // 100)
print(a // 1000)
```

What will this code print?

- **A)** `3`, `5`, `2`, `4`
- **B)** `3`, `2`, `5`, `4`
- **C)** `3`, `2`, `5`, `2`
- **D)** `3`, `5`, `2`, `5`
- **E)** `3`, `5`, `2`, `3`

**Your Answer:** Enter your answer on the Google Form.

---


### Question 9:

Consider the following Python code:

```python
a = 3
b = 6
c = "Hello"
d = -2

print(b / a)
print(b // a)
print(c * a)
print(c * d)
```

What will this code print?

- **A)** `2.0`, `2.0`, `HelloHelloHello`, `HelloHello`
- **B)** `2.0`, `2`, `HelloHelloHello`, `HelloHelloHello`
- **C)** `2.0`, `2`, `HelloHelloHello`, `Hello`
- **D)** `2.0`, `3`, `HelloHelloHello`, `HelloHello`
- **E)** `2.0`, `2`, `HelloHelloHello`, ``

**Your Answer:** Enter your answer on the Google Form.

---

### Question 10:

Consider the following Python code:

```python
text = "Hello, Python!"
new_text = text[7:13]
length = len(new_text)
print(f"The length of '{new_text}' is {len(text)} or {length}.")
```

What will this code print?

- **A)** `The length of 'Python' is 14 or 6.`
- **B)** `The length of 'Python' is 14 or 7.`
- **C)** `The length of 'Python' is 14 or 8.`
- **D)** `The length of 'Python' is 14 or 5.`
- **E)** `The length of 'Python' is 14 or 13.`


**Your Answer:** Enter your answer on the Google Form.

---

In this assignment, you have been asked to answer 10 multiple-choice questions. Please submit your answers on the Google Form provided.

Good luck!

---

