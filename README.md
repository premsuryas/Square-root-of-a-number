# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: prem kumar
RegisterNumber:23013598  
*/
```
def Sqrt(a,b):
  x=a
  for i in range(b):
    x=0.5*(x+a/x)
  print("Square root of the number:",x)
a=int(input())
b=100
Sqrt(a,b) 

## Output:
![gcd of two number](![sqrt output](https://github.com/premsuryas/Square-root-of-a-number/assets/147473858/f15f9764-956e-43a2-84f5-9e3a5a2e0c82)
.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
