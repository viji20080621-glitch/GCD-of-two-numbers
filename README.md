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

# Program to find the gcd of two number using function.
# Developed by: Vijiyalakshmi A
# RegisterNumber:212225240185  
```
def gcd():
    a = int(input())
    b = int(input())
    
    while b != 0:
        a, b = b, a % b
    
    print("GCD of two numbers is:", a)
```

## Output:

<img width="812" height="446" alt="Screenshot 2025-12-26 204441" src="https://github.com/user-attachments/assets/2fb0fc03-e6af-4a47-b8f6-eea3c54ca290" />

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
