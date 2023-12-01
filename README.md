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
# python program to find the square root for the given number(newton's method) using function
# developed by : sai vivek ragala
# reference no : 23003676
def newton_method(number,number_iters = 100):    
    a=float(number)
    for i in range(number_iters):
        number=0.5* (number + a / number)
    return number
a = int(input())
print("Square root of the number:",newton_method(a))
*/
```

## Output:
![Screenshot 2023-12-01 090905](https://github.com/RAGALASAIVIVEK/Square-root-of-a-number/assets/144979718/c21fae9b-bef3-49a1-957d-5056c3fd9acc)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
