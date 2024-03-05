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

**Correct Answer:** B

**Explanation:** The code checks if `a` is a multiple of `b` and prints `"YES"` if it is, otherwise it prints `"NO"`.

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

**Correct Answer:** B

**Explanation:** The code compares the ASCII values of the two letters and prints `"FIRST"` if `letter1` comes first, `"SECOND"` if `letter2` comes first, and `"EQUAL"` if they are the same.

---

### Question 3:


Consider the following Python code that determines the maximum value between two inputs, `a` and `b`:

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

**Correct Answer:** C

**Explanation:** The code multiplies `a` and `b` based on their comparison results, effectively selecting the maximum value between the two, and then prints it.

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

- **A)** Highest: 27, Lowest: 001
- **B)** Highest: 999, Lowest: 111
- **C)** Highest: 900, Lowest: 100
- **D)** Highest: 999, Lowest: 990
- **E)** Highest: 27, Lowest: 1


**Correct Answer:** E

**Explanation:** The highest possible sum of digits is obtained by the number `999`, which results in `9 + 9 + 9 = 27`. The lowest possible sum of digits is obtained by the number `100`, which results in `1`.


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

**Correct Answer:** A

**Explanation:** The code prints the boolean value of each variable and then prints the sum of these boolean values. The boolean value of a non-empty string is `True`, and the boolean value of a non-zero number is also `True`. The boolean value of `True` is `True`. Therefore, the sum of these boolean values is `4`.

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

**Correct Answer:** B

**Explanation:** The code compares the values of `a`, `b`, and `c`. The first comparison is `True` because `a` and `b` have the same value. The second comparison is `False` because `b` and `c` have different types. The third comparison is `False` because `a` and `c` have different types.

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

**Correct Answer:** A

**Explanation:** The code assigns the value of `x` to `y`, then changes the value of `x` to `20`. Therefore, `x` is `20`, `y` is `10`, and `x + y` is `30`.

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

**Correct Answer:** A

**Explanation:** The code prints the remainder of `a` divided by `10`, `100`, and `1000`, and then prints the result of `a` divided by `1000`. The remainder of `a` divided by `10` is `3`, the remainder of `a` divided by `100` is `53`, and the remainder of `a` divided by `1000` is `253`. The result of `a` divided by `1000` is `4`.

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

**Correct Answer:** E

**Explanation:** The code prints the result of `b` divided by `a`, the result of `b` floor divided by `a`, the string `c` repeated `a` times, and the string `c` repeated `d` times. The result of `b` divided by `a` is `2.0`, the result of `b` floor divided by `a` is `2`, the string `c` repeated `a` times is `"HelloHelloHello"`, and the string `c` repeated `d` times is an empty string (because negative repetition results in an empty string).

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


**Correct Answer:** A

**Explanation:** The code extracts the substring from index `7` to `12` (inclusive) from the string `text`, which is `"Python"`. The length of this substring is `6`, and the length of the original string `text` is `14`.

---

Correct answers:

1. B
2. B
3. C
4. E
5. A
6. B
7. A
8. A
9. E
10. A

---

