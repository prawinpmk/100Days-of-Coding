#### Statement
## Given a sequence of distinct non-negative integers, where each number is written in a separate line. The sequence ends with 0. Print the second largest element in this sequence. It is guaranteed that the sequence has at least two elements.

## Example input
```
1
7
9
0
```
## CODE
```
Number=[]
while 0 not in Number:
   ip = int(input())
   Number.append(ip)
Number.sort()
print(Number[len(Number)-2])
```
## Example output
```
7
```
