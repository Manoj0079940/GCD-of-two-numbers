# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
### Register num:21223230122
### Name: MANOJ M

def gcd():
    num1,num2=int(input()),int (input())
    if num1<num2:
        smallest=num1
    else:
        smallest=num2
    for i in range(1,smallest+1):
        if num1%i==0 and num2%i==0:
            gcd1=i
    print("GCD of two numbers is:",gcd1)        
```

## Output:
![image](https://github.com/drgbhuvaneswari/GCD-of-two-numbers/assets/149366208/b77e60d0-7341-41b4-985a-ff05172ef722)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
