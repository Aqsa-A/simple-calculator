# simple-calculator
a simple calculator program that preform the main operations

import math 

def addition ( x , y ):
    
    return x + Y


def subtraction ( x , y ):
    
    return x - y


def multiplication ( x , y ):
    
    return x * y


def dividation ( x , y ):

    return x / y

def square_root ( x ):

    return math.sqrt (x)

def Exponent ( x , y ):
    
    return x**y
    

print("Select operation.")
print("1.addition")
print("2.subtraction")
print("3.multiplication")
print("4.dividation")
print("5.square_root")
print("6.Exponent")


choice = input ( " Enter choice (1/2/3/4/5/6): " )


while True :

    if choice in ('1', '2', '3', '4'):
        num1 = float(input("Enter first number: "))
        num2 = float(input("Enter second number: "))
        
    elif choice in ('5'):
            num1 = float(input("Enter number: "))

    elif choice in ('6'):
        num1 = float(input("Enter number: "))
        num2 = float(input("Enter power : "))
        
            

    

    if choice == '1':
            print(num1, "+", num2, "=", addition(num1, num2))

    elif choice == '2':
            print(num1, "-", num2, "=", subtraction(num1, num2))

    elif choice == '3':
            print(num1, "*", num2, "=", multiplication(num1, num2))

    elif choice == '4':
            print(num1, "/", num2, "=", dividation(num1, num2))

    elif choice == '5':
            print(num1, square_root (num1))

    elif choice == '6':
         print(num1, "**", num2, "=", Exponent(num1, num2))
        
    break

else:
        print("Invalid Input")
    
