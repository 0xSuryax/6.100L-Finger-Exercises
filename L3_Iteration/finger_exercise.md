# Finger Exercise Lecture 3

Assume you are given a positive integer variable named `N`. Write a piece of Python code that prints `hello world` on separate lines, `N` times. You can use either a `while` loop or a `for` loop.

## SOLUTION 1

```python
N = 2

for n in range(N):
    print('hello world\n')
```

## SOLUTION 2

```python
N = 2
counter = 0

while counter < N:
    counter += 1
    print('hello world\n')
```





