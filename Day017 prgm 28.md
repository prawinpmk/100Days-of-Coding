### Statement
<b>In mathematics, the factorial of an integer n, denoted by n! is the following product:

n! = 1 × 2 × … × n

For the given integer n calculate the value 

1! + 2! + 3! + ... + n!

Try to discover the solution that uses only one for-loop. And don't use math module in this exercise.
</b>
### Example input
```
4
```
## CODE
```
limit = int(input())
factorial = 1
Total = 0
if limit == 1 or limit == 0:
  print(1)
else:
  for i in range(1,limit + 1):
       factorial *= i
       Total += factorial
  print(Total)  
```

### Example output
```
33
```
