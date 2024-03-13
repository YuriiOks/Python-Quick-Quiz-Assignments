### Question 1 - Football Match Scoring: 

The following Python code is given:

```python
# Input: Number of points received by the team
points = int(input("Enter the number of points: "))

# Initialize an empty string for the output message
output = ""

# Conditional statements to determine the match result and assign it to the output variable
if points == 3:
    output = "win"
elif points == 1:
    output = "draw"
elif points == 0:
    output = "lose"

# Print the output message
print(output)
```



What will this code print?

- **A)** `win`
- **B)** `draw`
- **C)** `lose`
- **D)** `win` if `points` is `3`, `draw` if `points` is `1`, `lose` if `points` is `0`

**Your Answer:** Enter your answer on the Google Form.

---

### Question 2 - FizzBuzz Game:

What will the following Python code print?:

```python
number = 15

if number % 3 == 0 and number % 5 == 0:
    print("FizzBuzz")
elif number % 3 == 0:
    print("Fizz")
elif number % 5 == 0:
    print("Buzz")
else:
    print(number)
```

What does this code accomplish?

- **A)** It prints `Fizz`.
- **B)** It prints `Buzz`.
- **C)** It prints `FizzBuzz`.
- **D)** It prints `15`.

**Your Answer:** Enter your answer on the Google Form.

---

### Question 3 - FizzBuzz Game:


What will the following Python code print?:

```python
number = 15

if number % 3 == 0:
    print("Fizz")
elif number % 5 == 0:
    print("Buzz")
elif number % 3 == 0 and number % 5 == 0:
    print("FizzBuzz")
else:
    print(number)
```

What does this code accomplish?

- **A)** It prints `Fizz`.
- **B)** It prints `Buzz`.
- **C)** It prints `FizzBuzz`.
- **D)** It prints `15`.

**Your Answer:** Enter your answer on the Google Form.

---

### Question 4 - Truth Table:


Complete the truth table for the following Python code:

```python
salah_is_open = True
pass_is_clear = True
```

- **A)** 

| Salah is Open	| Pass is Clear	| Pass to Salah  |
|---------------|---------------|----------------|
| True          | True          | True           |
| True          | False         | False          |
| False         | True          | False          |
| False         | False         | True           |

- **B)**

| Salah is Open	| Pass is Clear	| Pass to Salah  |
|---------------|---------------|----------------|
| True          | True          | True           |
| True          | False         | False          | 
| False         | True          | True           |
| False         | False         | False          |

- **C)**

| Salah is Open	| Pass is Clear	| Pass to Salah  |
|---------------|---------------|----------------|
| True          | True          | True           |
| True          | False         | False          |
| False         | True          | False          |
| False         | False         | False          |

- **D)**

| Salah is Open	| Pass is Clear	| Pass to Salah  |
|---------------|---------------|----------------|
| True          | True          | True           |
| True          | False         | True           |
| False         | True          | True           |
| False         | False         | True           |

- **E)**

| Salah is Open	| Pass is Clear	| Pass to Salah  |
|---------------|---------------|----------------|
| True          | True          | True           |
| True          | False         | False          |
| False         | True          | True           |
| False         | False         | True           |

**Your Answer:** Enter your answer on the Google Form.


---

### Question 5 - Nested Conditional Statements:


Consider the following Python code:

```python

salah_is_open = True
pass_is_clear = False
mane_is_open = True
firmino_is_open = False

if salah_is_open:
    if pass_is_clear:
        print("Pass to Salah")
    else:
        print("Don't pass to Salah, look for other options")
elif mane_is_open:
    if pass_is_clear:
        print("Pass to Mané")
    else:
        print("Don't pass to Mané, look for other options")
elif firmino_is_open:
    if pass_is_clear:
        print("Pass to Firmino")
    else:
        print("Don't pass to Firmino, look for other options")
else:
    print("Neither Salah, Mané, nor Firmino is open, look for other options")
```

What will this code print?

- **A)** `Pass to Mané`
- **B)** `Don't pass to Salah, look for other options`
- **C)** `Pass to Firmino`
- **D)** `Neither Salah, Mané, nor Firmino is open, look for other options`
- **E)** `Don't pass to Mané, look for other options`

**Your Answer:** Enter your answer on the Google Form.

---

### Question 6 - Conditional Operator:

Given the following Python code:

```python

salah_is_open = True
message = "Pass to Salah" if salah_is_open else "Don't pass to Salah"
print(message)

distance_to_goal = 30
shot_power = "High" if distance_to_goal > 20 else "Low"
print(shot_power)
```

What construnction is used in the code to assign the value to the `shot_power` and `message` variables?

- **A)** `if-else` statement
- **B)** `if` statement
- **C)** `else` statement
- **D)** `if-elif-else` statement
- **E)** Ternary conditional operator

**Your Answer:** Enter your answer on the Google Form.

---

### Question 7 - Nested Conditional Statements:

Consider the following Python code:

```python

salah_is_open = True
pass_is_clear = False
mane_is_open = True

if salah_is_open:
    if pass_is_clear:
        print("Pass to Salah")
    else:
        print("Don't pass to Salah, look for other options")
if mane_is_open:
    print("Pass to Mané")
else:
    print("Neither Salah nor Mané is open, look for other options")
```

What will this code print?

- **A)** `Don't pass to Salah, look for other options`
- **B)** `Pass to Mané`
- **C)** `Pass to Salah`, `Pass to Mané`
- **D)** `Don't pass to Salah, look for other options`, `Pass to Mané`
- **E)** `Pass to Salah`


**Your Answer:** Enter your answer on the Google Form.

---

### Question 8 - Grading System Interpretation:

3 Python code snippets are given:

```python

# The first code snippet
if score >= 90:
    output = "Your grade is A."
elif score >= 80:
    output = "Your grade is B."
elif score >= 70:
    output = "Your grade is C."
elif score >= 60:
    output = "Your grade is D."
else:
    output = "Your grade is F."
```

```python
# The second code snippet
if score >= 90:
    output = "Your grade is A."
elif score >= 80 and score < 90:
    output = "Your grade is B."
elif score >= 70 and score < 80:
    output = "Your grade is C."
elif score >= 60 and score < 70:
    output = "Your grade is D."
elif score < 60:
    output = "Your grade is F."
```

```python
# The third code snippet
if score >= 90:
    output = "Your grade is A."
elif 80 <= score < 90:
    output = "Your grade is B."
elif 70 <= score < 80:
    output = "Your grade is C."
elif 60 <= score < 70:
    output = "Your grade is D."
elif score < 60:
    output = "Your grade is F."
```

Which of the following code snippets is correct to determine the grade based on the score?

- **A)** The first code snippet
- **B)** The second code snippet
- **C)** The third code snippet
- **D)** All of the code snippets are correct
- **E)** None of the code snippets are correct

**Your Answer:** Enter your answer on the Google Form.

---


### Question 9:

3 Python code snippets are given:

```python

# The first code snippet
if score >= '90':
    output = "Your grade is A."
elif score >= '80':
    output = "Your grade is B."
elif score >= '70':
    output = "Your grade is C."
elif score >= '60':
    output = "Your grade is D."
else:
    output = "Your grade is F."
```

```python
# The second code snippet
if score >= '90':
    output = "Your grade is A."
elif score >= '80' and score < '90':
    output = "Your grade is B."
elif score >= '70' and score < '80':
    output = "Your grade is C."
elif score >= '60' and score < '70':
    output = "Your grade is D."
elif score < '60':
    output = "Your grade is F."
```

```python
# The third code snippet
if score >= '90':
    output = "Your grade is A."
elif '80' <= score < '90':
    output = "Your grade is B."
elif '70' <= score < '80':
    output = "Your grade is C."
elif '60' <= score < '70':
    output = "Your grade is D."
elif score < '60':
    output = "Your grade is F."
```

Which of the following code snippets is correct to determine the grade based on the score?

- **A)** The first code snippet
- **B)** The second code snippet
- **C)** The third code snippet
- **D)** All of the code snippets are correct
- **E)** None of the code snippets are correct


**Your Answer:** Enter your answer on the Google Form.

---

### Question 10 - Conditional Statements:

User enters `A` and `B` as the inputs. The following Python code is given:

```python
char_2 = input("Enter the first character: ")
char_1 = input("Enter the second character: ")

output = f"{char_2}" if char_2 > char_1 else f"{char_1}"
```

What will this code print?

- **A)** `A`
- **B)** `B`
- **C)** `AB`
- **D)** `BA`
- **E)** `It will raise an error`

### Question 11 - Leap Year Determination:

Select Python Code that best represent checking if the year is a leap year.

- **A)** 

```python
if year % 4 == 0:
    if year % 100 == 0:
        if year % 400 == 0:
            print("Leap year")
        else:
            print("Not a leap year")
    else:
        print("Leap year")
else:
    print("Not a leap year")
```

- **B)** 

```python
if year % 4 == 0:
    if year % 100 == 0:
        if year % 400 != 0:
            print("Leap year")
        else:
            print("Not a leap year")
    else:
        print("Leap year")
else:
    print("Not a leap year")
```


- **C)** 

```python
output = "Leap year" if year % 4 == 0 and year % 100 != 0 or year % 400 == 0 else "Not a leap year"
print(output)
```

- **D)** 

```python
output = "Leap year" if year % 4 == 0 and year % 100 == 0 and year % 400 == 0 else "Not a leap year"
print(output)
```

- **E)** 

```python
if year % 4 != 0:
    if year % 100 != 0:
        if year % 400 != 0:
            print("Leap year")
        else:
            print("Not a leap year")
    else:
        print("Leap year")
else:
    print("Not a leap year")
    
```

### Question 12 - Next Day Date Validation:

The following Python code is given:

```python
# Input: Current date (day, month, year)
day = int(input("Enter the day: "))
month = int(input("Enter the month: "))
year = int(input("Enter the year: "))

# Check for leap year
is_leap = (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0)

# Initialize output message
output = ""

# Manually handle each month's end-of-month logic
if month == 1 or month == 3 or month == 5 or month == 7 or month == 8 or month == 10:
    if day < 31:
        day += 1
    else:  # Last day of the month
        day = 1
        ___
elif month == 4 or month == 6 or month == 9 or month == 11:
    if day < 30:
        day += 1
    else:  # Last day of the month
        day = 1
        month += 1
elif month == 2:
    # Check for leap year
    if is_leap:
        if day < 29:
            ___
        else:  # Last day of February in a leap year
            day = 1
            month += 1
    else:  # Not a leap year
        if day < 28:
            day += 1
        else:
            day = 1
            month += 1
elif ___:
    if day < 31:
        day += 1
    else:  # Transition to the next year
        day = 1
        month = 1
        year += 1
else:
    output = "Invalid date provided."

# Prepare the output message if it's not set to "Invalid date provided."
if output == "":
    output = f"Next day's date: {day:02d}.{month:02d}.{year}"

# Print the output message
print(output)
```

What should be placed in the blanks to complete the code?

- **A)** `month += 1`,`day += 1` and `year += 1`
- **B)** `day += 1`, `month += 1` and `month = 1`
- **C)** `day += 1`, `month += 1` and `year += 1`
- **D)** `day += 1`, `month += 1` and `day = 1`
- **E)** `day += 1`, `month += 1` and `month == 12`


**Your Answer:** Enter your answer on the Google Form.

---

In this assignment, you have been asked to answer 10 multiple-choice questions. Please submit your answers on the Google Form provided.

Good luck!

---

