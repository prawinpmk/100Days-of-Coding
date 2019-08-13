### Statement
#### For the given integer N calculate the following sum:

#### 1³ + 2³ + ... + N³


## Example input
```
3
```
## CODE
```
limit = int(input())
Total = 0
for i in range(1,limit+1):
  Total+=(i**3)
print(Total)  
```
## Example output
```
36
```
