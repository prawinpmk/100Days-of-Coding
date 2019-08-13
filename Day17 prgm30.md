<b>Statement
There was a set of cards with numbers from 1 to N. One of the card is now lost. Determine the number on that lost card given the numbers for the remaining cards.

Given a number N, followed by N − 1 integers representing the numbers on the remaining cards (distinct integers in the range from 1 to N). Find and print the number on the lost card.</b>


```
Example input
5
3
5
2
1
```


## Code
```
ip = int(input())
numbers = [int(input()) for i in range(ip-1)]
for i in range(1,ip+1):
  if  i not in numbers:
    print(i)
```


```
Example output
4
```
