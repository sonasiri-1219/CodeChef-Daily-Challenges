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
