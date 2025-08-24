# student_assignment2
```# Even or Odd Number Checker

This Python program checks whether a number is *even, **odd, or **neither* (in the case of 0).

## 📜 Code

```python
num = int(input('Enter the number: '))

if num == 0:
    print(num, 'is neither even nor odd')
else:
    result = num % 2
    if result == 0:
        print(num, 'is an even number')
    else:
        print(num, 'is an odd number')
```
