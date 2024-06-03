# Data Structures
In Python, Arrays are implemented using list, Hash tables using Dictionary and Linked List is not available in Python

# Big O Notation
It is used to measure how running time or space requirements for your program grows as input size grows

O(n):
```py
def sqaureNumber(numbers):
  squaredNumbers = []
  for n in numbers:
    squaredNumbers.append(n*n)
  return squaredNumbers

numbers = [1,2,3]
print(squareNumber(numbers))
```
O(1):
```py
def firstPe(prices,eps,index):
  pe = prices[index]/eps[index]
  return pe
```
O(%n^2%)
