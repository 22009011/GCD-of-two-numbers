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
Developed by: Thanjiyappan.K
RegisterNumber:  212222240108

def gcd():
    n1,n2=int(input()),int(input())
    if n1<n2:
        smaller=n1
    else:
        smaller=n2
    for i in range(1,smaller+1):
        if n1%i==0 and n2%i==0:
            gcdvalue=i
    print("GCD of two numbers is:" ,gcdvalue)

```

## Output:
![Screenshot 2023-04-15 at 09-03-30 Exp-2a-CR- GCD of two numbers Attempt review](https://user-images.githubusercontent.com/118343461/232207198-182c39ab-16bc-485a-a8a3-5385753b0c2f.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
