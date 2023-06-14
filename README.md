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
Program to find the gcd of two number using function.

Developed by: Sivaramakrishnan B
RegisterNumber: 212222110044

def gcd():
    a=int(input())
    b=int(input())
    if a>b:
        smaller=b
    else:
        smaller=a
    for i in range(1,smaller+1):
        if(a%i==0 and b%i==0):
            ch=i
    print("GCD of two numbers is:",ch)
    
```
## Program Statement: 
![image](https://github.com/SivaramakrishnanBaskar/GCD-of-two-numbers/assets/119476322/0f5245f5-4817-49cc-9723-0cf15a9adb64)

## Output:
![image](https://github.com/SivaramakrishnanBaskar/GCD-of-two-numbers/assets/119476322/dd399bc5-a741-4101-a726-88e3ab7a8827)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
