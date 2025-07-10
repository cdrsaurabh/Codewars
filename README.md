# Codewars
In  this repository I'm going to upload the questions which I'll be solving on codewars of Python language.

Today is 09/07/2025, as I was exploring different websites and I today I got to know about codewars I was aware of leetcode but not codewars so, I explored it a little bit and I thought that it is going to help me a lot. So I started exploring it and currently I'm learning python so I thought to give it a try.

## Question 1
So today the first question which appeared on the screen(obviously as a fundamental beginners of python) was to take a number as a input and then form a number by arranging the digits of the number in descending order.
For eg: 
input: 6284.  output: 8642
```python
num = int(input("Enter any number "))
dig = [] # storing it in a list
temp = num # storing for displying the number in future
while (num>0):
    dig.append(num%10) # storing the digits of the number in the list
    num = num//10
length = len(dig)
print("The length of your no. is ",length)
dig.sort(reverse=True) # sorting the  list dig in descending order
output = 0
for i in dig:
    output =(output*10)+i # forming the number
print("The descending order of your no.",temp,"is")
print(output)
```
## Question 2
You get an array of numbers, return the sum of all of the positives ones.
eg: list = [1,-7, 4 ,12]
output = 1+4+12 = 17
```python
new_dig = [1,-4,7,12]
leng = len(new_dig)
new_num = 0
for i in range(0,leng):
    if (new_dig[i]>0):
        new_num += new_dig[i]
print(new_num)
```
