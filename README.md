Python Programming Exercises
Programs
1. Binary Numbers Divisible by 5
Aim
Write a Python program that accepts a sequence of comma-separated 4-digit binary numbers and checks which numbers are divisible by 5.

Algorithm
Read comma-separated binary numbers from the user.
Split the input using split(",").
Convert each binary number into decimal using int(i, 2).
Check whether the decimal value is divisible by 5.
Store the divisible numbers in a list.
Print the numbers as a comma-separated sequence.
Program
s=input().split(",")
result=[]
for i in s:
    if (int(i,2)%5==0):
        result.append(i)
print(",".join(result))
OUTPUT
image
2. Count Letters and Digits
Question
Write a Python program that accepts a sentence and calculates the number of letters and digits.

Aim
Write a Python program that accepts a sentence and calculates the number of letters and digits.

Algorithm
Read a sentence from the user.
Initialize letters and digits to 0.
Traverse each character using a for loop.
Check whether the character is a letter using isalpha().
Check whether the character is a digit using isdigit().
Increment the respective counter.
Display the number of letters and digits.
Program
n=input("Enter the sentence:")
letters=0
digits=0
for i in n:
    if i.isalpha():
        letters+=1
    elif i.isdigit():
        digits+=1
print("LETTERS: ",letters)
print("DIGITS: ",digits)
OUTPUT
image
3. Factorial of a Number
Question
Write a program which can compute the factorial of a given number. The results should be printed in a comma-separated sequence on a single line. Suppose the following input is supplied to the program: 8

Aim
Write a Python program to compute the factorial of a given number.

Algorithm
Read a number from the user.
Initialize fact to 1.
Use a for loop from 1 to the given number.
Multiply each number with fact.
Store the calculated factorial.
Display the factorial.
Program
n=int(input("Enter the value:"))
fact=1
for i in range(1,n+1):
    fact=fact*i
print(fact)
OUTPUT
image
