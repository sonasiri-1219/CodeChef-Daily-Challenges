# 🚀 CodeChef Coding Journey – Python

## 🟢 Day 1 – Cooking Problem

```python
t = int(input())

for i in range(t):
    x, y, a, b = map(int, input().split())

    c = a * b
    z = x * y

    if c >= z:
        print("Yes")
    else:
        print("No")
```

---

## 🟢 Day 2 – Chef and Candies

```python
t = int(input())

for i in range(t):
    n, x = map(int, input().split())

    if x >= n:
        print(0)
    else:
        remaining = n - x
        print((remaining + 3) // 4)
```

---

## 🟢 Day 3 – Car or Bike

```python
t = int(input())

for i in range(t):
    x, y = map(int, input().split())

    if x < y:
        print("BIKE")
    elif y < x:
        print("CAR")
    else:
        print("SAME")



 Day 4 – Monopoly


💻 Python Solution

t = int(input())

for i in range(t):
    a, b, c, d = map(int, input().split())

    if a > b + c + d or b > a + c + d or c > a + b + d or d > a + b + c:
        print("YES")
    else:
        print("NO")

## 🟢 Day 5 – Count Values Greater Than or Equal to 1000

**Problem:** Given `N` numbers, count how many numbers are greater than or equal to `1000`.

### 💻 Python Solution

```python
t = int(input())

for i in range(t):
    n = int(input())
    d = list(map(int, input().split()))

    c = 0
    for i in range(n):
        if d[i] >= 1000:
            c += 1

    print(c)
```

**
DAY-6
t = int(input())

for i in range(t):
    x = int(input())

    if x <= 50:
        print("LEFT")
    else:
        print("RIGHT")**



day-7:
# cook your dish here
t = int(input())

for i in range(t):
    a, b = map(int, input().split())

    if (2 * a) > b:
        print("FIRST")
    elif (2 * a) < b:
        print("SECOND")
    else:
        print("ANY")

day-8:
#Good or Not Good
t = int(input())

for i in range(t):
    n = int(input())

    if n % 4 == 0:
        print("Good")
    else:
        print("Not Good")


Day 9 – Qualify or Not Qualify

Problem: Given the qualifying score X and the values A and B, calculate the total score using A × 1 + B × 2. If the total score is greater than or equal to X, print Qualify; otherwise, print NotQualify.

💻 Python Solution

t = int(input())

for i in range(t):
    x, a, b = map(int, input().split())

    c = a * 1 + b * 2

    if c >= x:
        print("Qualify")
    else:
        print("NotQualify")


Day 10 – Count Eligible People

# cook your dish here
t = int(input())

for i in range(t):
    count = 0
    n, x = map(int, input().split())
    age = list(map(int, input().split()))

    for a in age:
        if a >= x:
            count += 1

    print(count)


    Day 11 – Chef and Candies

    # cook your dish here
t = int(input())

for i in range(t):
    n = int(input())
    d = int(n / 4)

    if n % 4 == 0:
        print(d)
    elif n < 4:
        print(1)
    elif n > 4 or n % 4 != 0:
        print(d + 1)


 Day 12 :

**Problem: Check Whether Y Is a Multiple of X Within N**

📝 **Approach:**
- Read the number of test cases.
- Take `N`, `X`, and `Y` as input.
- Use a `while` loop to check whether `X * i == Y` for any `i` from `1` to `N`.
- Print `YES` if a match is found; otherwise, print `NO`.

💻 **Concepts Used:** Python, Loops, Conditional Statements, Basic Logic

🎯 **Learning Outcome:** Practiced using loops and conditions to solve mathematical problems efficiently.

#Python #CodeChef #ProblemSolving #100DaysOfCode

day-13:
### 🚀 CodeChef Problem Solving – Python

**Problem: Check Divisibility and Conditions**

📝 **Approach:**
- Read the number of test cases `t`.
- For each test case, take two integers `n` and `x`.
- Check whether `n <= x` and `x % n == 0`.
- If both conditions are true, print `YES`; otherwise, print `NO`.

💻 **Python Concepts Used:**
- `for` loop
- `if-else` statements
- Modulus operator (`%`)
- Logical operators (`and`)

🎯 **Learning Outcome:** Practiced conditional statements and divisibility checks using Python.

#Python #CodeChef #ProblemSolving #CodingPractice



day-14:

### 🚀 Python Coding Practice – Find the Maximum

**Problem:** Find the Largest Among Three Numbers

📝 **Approach:**
- Read the number of test cases `n`.
- For each test case, take three integers `a`, `b`, and `c`.
- Use Python's built-in `max()` function to find the largest number.
- Print the maximum value.

💻 **Concepts Used:**
- `for` loop
- Multiple inputs using `map()`
- Built-in `max()` function

🎯 **Learning Outcome:** Practiced handling multiple test cases and finding the largest value using Python.

#Python #CodeChef #ProblemSolving #CodingPractice


DAY-15:
### 🚀 Python Coding Practice – Sum of Maximum Values

**Problem:** Find the Maximum of Two Pairs and Calculate Their Sum

📝 **Approach:**
- Read the number of test cases `t`.
- Take four integers `a`, `b`, `c`, and `d` for each test case.
- Find the maximum of the first pair using `max(a, b)`.
- Find the maximum of the second pair using `max(c, d)`.
- Add both maximum values and print the result.

💻 **Concepts Used:**
- `for` loop
- Multiple inputs using `map()`
- Built-in `max()` function
- Arithmetic operations

🎯 **Learning Outcome:** Practiced finding maximum values from two pairs and combining them using Python.

#Python #CodeChef #ProblemSolving #CodingPractice


DAY-16:

### 🚀 CodeChef Problem Solving – Python

**Problem: Calculate the Total**

📝 **Approach:**
- Read two integers `x` and `y`.
- Calculate half of `y` using integer division (`y // 2`).
- Calculate the remaining value by subtracting `y` from `x`.
- Add both results and print the total.

💻 **Concepts Used:**
- User input
- Integer division (`//`)
- Arithmetic operations
- Variables and calculations

🎯 **Learning Outcome:** Practiced integer division and basic arithmetic operations using Python.

#Python #CodeChef #ProblemSolving #CodingPractice #Programming



DAY-17:
### 🚀 CodeChef Problem Solving – Python

**Problem: Conditional Calculation Using N and M**

📝 **Approach:**
- Read the number of test cases `T`.
- For each test case, take two integers `N` and `M`.
- If `M >= N`, print `N`.
- Otherwise, print `2 * N - M`.

💻 **Concepts Used:**
- `for` loop
- `if-else` statements
- Comparison operators (`>=`)
- Arithmetic operations

🎯 **Learning Outcome:** Practiced conditional logic and arithmetic calculations to solve programming problems efficiently.

#Python #CodeChef #ProblemSolving #CodingPractice #Programming

DAY-18

### 🚀 Python Coding Practice – Factorial Using Recursion

**Problem:** Calculate the Factorial of a Number

📝 **Approach:**
- Define a function `fact(n)` to calculate the factorial.
- Use the base case: if `n == 0` or `n == 1`, return `1`.
- Otherwise, calculate `n * fact(n-1)` using recursion.
- Read multiple test cases and print the factorial of each number.

💻 **Concepts Used:**
- Functions
- Recursion
- Base cases
- Conditional statements
- Loops

**Example:**
- Input: `5`
- Output: `120`

🎯 **Learning Outcome:** Understood how recursion works and how a function calls itself to solve a mathematical problem.

#Python #CodeChef #Recursion #Factorial #ProblemSolving #CodingPractice


DAY-19:
### 🚀 Python Coding Practice – Factorial Using Recursion

**Problem:** Calculate the Factorial of a Number

📝 **Approach:**
- Define a function `fact(n)` to calculate the factorial.
- Use the base case: if `n == 0` or `n == 1`, return `1`.
- Otherwise, calculate `n * fact(n-1)` using recursion.
- Read multiple test cases and print the factorial of each number.

💻 **Concepts Used:**
- Functions
- Recursion
- Base cases
- Conditional statements
- Loops

**Example:**
- Input: `5`
- Output: `120`

🎯 **Learning Outcome:** Understood how recursion works and how a function calls itself to solve a mathematical problem.

#Python #CodeChef #Recursion #Factorial #ProblemSolving #CodingPractice


DAY-20:

### 🚀 CodeChef Problem Solving – Python

**Problem: Calculate the Remaining Requirement**

📝 **Approach:**
- Read the number of test cases `t`.
- For each test case, take three integers `x`, `y`, and `z`.
- Calculate `y // x` using integer division.
- Subtract the result from `z`.
- Use `max(0, total)` to ensure the answer is never negative.
- Print the final result.

💻 **Concepts Used:**
- `for` loop
- Multiple inputs using `map()`
- Integer division (`//`)
- Built-in `max()` function
- Arithmetic operations

🎯 **Learning Outcome:** Practiced integer division, conditional calculations, and handling negative results using Python.

#Python #CodeChef #ProblemSolving #CodingPractice


DAY-21:
### 🚀 CodeChef Problem Solving – Python

**Problem: Calculate the Minimum Number of Groups**

📝 **Approach:**
- Read the number of test cases `t`.
- For each test case, take two integers `x` and `y`.
- Calculate the difference using `rr = y - x`.
- Divide the difference by `8` to find the number of complete groups.
- If a remainder exists, add `1` to include the extra group.
- Print the final answer.

💻 **Concepts Used:**
- `while` loop
- User input using `map()`
- Integer division and modulo (`%`)
- Conditional statements
- Basic mathematical logic

🎯 **Learning Outcome:** Practiced calculating the minimum number of groups required using division and remainder logic.

#Python #CodeChef #ProblemSolving #CodingPractice #Programming


DAY-22:

### 🚀 CodeChef Problem Solving – Python

**Problem: DNA Complement / DNA String Transformation**

📝 **Approach:**
- Read the number of test cases `t`.
- For each test case, read the string length `n` and DNA string `s`.
- Initialize an empty string `res`.
- Iterate through each character in the DNA string.
- Replace each nucleotide with its complementary nucleotide:
  - `A → T`
  - `T → A`
  - `C → G`
  - `G → C`
- Print the transformed DNA string.

💻 **Concepts Used:**
- `for` loop
- String manipulation
- Conditional statements (`if`)
- Character mapping
- String concatenation

🎯 **Learning Outcome:** Practiced string traversal and character replacement using conditional statements in Python.

#Python #CodeChef #DNASequence #StringManipulation #ProblemSolving #CodingPractice


DAY-23:

### 🚀 CodeChef Problem Solving – Python

**Problem: Calculate the Maximum Number of Items**

📝 **Approach:**
- Read the number of test cases `t`.
- For each test case, take three integers `n`, `x`, and `k`.
- Check the following conditions:
  1. If `x > k`, print `0`.
  2. If `n * x < k`, print `n`.
  3. Otherwise, print `k // x`.
- Use conditional statements to determine the final answer.

💻 **Concepts Used:**
- `for` loop
- `if-elif-else` conditions
- Integer division (`//`)
- Comparison operators
- Mathematical logic

🎯 **Learning Outcome:** Practiced conditional problem-solving, integer division, and handling different input scenarios using Python.

#Python #CodeChef #ProblemSolving #CodingPractice #Programming
