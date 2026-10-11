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
```

---

## 🎯 My Goals
- Practice coding every day.
- Improve Python and logical thinking.
- Build problem-solving skills.
- Prepare for coding interviews.

**Consistency beats perfection. One problem at a time! 💻🔥**

#CodeChef #Python #CodingJourney
