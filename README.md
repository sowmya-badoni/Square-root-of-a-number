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
#FINDING THE GREATEST COMMON DIVISOR OF THE TWO NUMBERS
#DEVELOPED BY: SOWMYA BADONI
#REGISTER NUMBER: 212223230211
def gcd():
    num1,num2 = int(input()),int(input())
    if num1>num2:
        small=num2
    else:
        small=num1
    for i in range(1,small+1):
        if (num1%i==0) and (num2%i==0):
            gcdd=i
    print("GCD of two numbers is:",gcdd)
```


## Output:
![image](https://github.com/sowmya-badoni/Square-root-of-a-number/assets/152136324/72c4c520-dbf7-4d74-8f92-5bd102ceb3f0)




## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
