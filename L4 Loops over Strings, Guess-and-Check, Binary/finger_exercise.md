# Finger Exercise Lecture 4

Assume you are given a positive integer variable named `N`. Write a piece of Python code that finds the cube root of `N`. The code prints the cube root if `N` is a perfect cube or it prints `error` if `N` is not a perfect cube. Hint: use a loop that increments a counter—you decide when the counter should stop.

## SOLUTION

```python
N = 27
counter = 1

while counter**3 < N:
    counter += 1
if counter**3 == N:
    print(counter)
else:
    print('error')

```
