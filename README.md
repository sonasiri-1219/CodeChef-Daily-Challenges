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
