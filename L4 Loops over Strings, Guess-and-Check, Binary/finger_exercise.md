# Finger Exercise Lecture 4

Assume you are given a positive integer variable named `N`. Write a piece of Python code that finds the cube root of `N`. The code prints the cube root if `N` is a perfect cube or it prints `error` if `N` is not a perfect cube. Hint: use a loop that increments a counter—you decide when the counter should stop.

## SOLUTION

```python
N = 27

if N < 0:
    cube_of_N = -abs(N) ** (1/3)
    if cube_of_N ** 3 == -abs(N):
        print(cube_of_N)
    else:
        print('error')
else:
    cube_of_N = N ** (1/3)
    if cube_of_N ** 3 == N:
       print(cube_of_N)
    else:
       print('error')
```
