# Algorithm-A1
## BubbleSort Algorithm takes in 2 pair of numbers and sorts them if they are not in the right order. This happens till there is no elements left to sort.

## a = list(word)
list(word) is going to conver the string into array of letters

## for i in range(len(a)):
len(a) returns the length of an array. range will generate series of numbers within the given range.

## for j in range(len(a)-i-1):
Traverses the array from len(a)-i-1

## if ord(a[j]) > ord(a[j+1]):
##   a[j], a[j+1] = a[j+1], a[j]
Finds decimal value of charactars in ASCII table and checks if the decimal value is greater then the letter value to the right.


