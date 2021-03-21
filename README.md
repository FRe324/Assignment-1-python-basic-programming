# Assignment-1-python-basic-programming


1.
Write a Python program to print 'Hello Python'?
code:-
print("Hello world")
o/p

Hello world


2. Write a Python program to do arithmetical operations addition and division.?
code:-
val1=int (input("Enter the first no."))
val2=int (input("enter the second no."))
#addition
add=val1+val2
#division
div=val1/val2
print(add)
print(div)

o/p
Enter the first no.5
enter the second no.3
8
1.6666666666666667

3. Write a Python program to find the area of a triangle?
 code:-

#the aREA OF TRIANGLE
R=int(input("the radius of triangle is "))
area=3.14*R*R
print("the area of triangle is",area)
O/P
the radius of triangle is 3
the area of triangle is 28.259999999999998


4. Write a Python program to swap two variables?

CODE:- 
#to swap two no.
val1=int(input("enter no. 1 "))
val2=int(input("enter no. 2 "))
t=val1
val1=val2
val2=t
print("the swapped value of no 1",val1)
print("the swapped value of no 2",val2)

O/P
enter no. 16
enter no. 2 3
the swapped value of no 1 3
the swapped value of no 2 6


5. Write a Python program to generate a random number?

 CODE:-
#generate random no.
import random
print(random.randrange(0, 100, 1))
O/P
17
