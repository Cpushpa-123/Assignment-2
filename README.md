# Assignment-2
Assignment 2 solutions
CREATE A CALCULATOR

def add(num1, num2):
    return num1 + num2
def subtract(num1, num2):
    return num1 - num2
def multiply(num1, num2):
    return num1 * num2
def divide(num1, num2):
    return num1 / num2
print("Please select operation -\n" \
        "1. Add\n" \
        "2. Subtract\n" \
        "3. Multiply\n" \
        "4. Divide\n")
select = int(input("Select operations form 1, 2, 3, 4 :"))
  
number_1 = int(input("Enter first number: "))
number_2 = int(input("Enter second number: "))
  
if select == 1:
    print(number_1, "+", number_2, "=",
                    add(number_1, number_2))
  
elif select == 2:
    print(number_1, "-", number_2, "=",
                    subtract(number_1, number_2))
  
elif select == 3:
    print(number_1, "*", number_2, "=",
                    multiply(number_1, number_2))
  
elif select == 4:
    print(number_1, "/", number_2, "=",
                    divide(number_1, number_2))
else:
    print("Invalid input")
    
    
    NESTED IF- ELSE
    
x = 30
y = 10
if x >= y:
    print("x is greater than or equals to y")
    if x == y:
        print("x is equals to y")
    else:
        print("x is greater than y")
else:
    print("x is less than y")

FUNCTIONS WITH 1 , 2 AND 3 PARAMETER

def fun():
	print("zero parameter")
fun();

def add(a,b):
	return a+b
print(add(1,2))

def add(a,b,c):
	return a+b+c
print(add(1,2,3))
     
