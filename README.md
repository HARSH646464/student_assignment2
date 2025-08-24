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

```# Sum of Numbers from 1 to 50

This Python program calculates the sum of all numbers from *1 to 50* using a for loop.

## 📜 Code

```python
sum = 0
for i in range(51):
    sum += i
print('The sum of numbers from 1 to 50 is', sum)
```
