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
#find the square root
#Developed by : Bharath.N
#Referance number : 23003413

def sqrt(n,l):
    x=n
    for i in range (l):
        x=0.5*(x+n/x)
    print("Square root of the number:",x)
a=int(input())
l=100
sqrt(a,l)
```

## Output:
![square-root-output](https://github.com/BHARATHNATRAJAN/Square-root-of-a-number/assets/147473529/3dd8aa8c-4904-4907-97e9-0ed25d3f61b7)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
