#make a simple calculator
operation = input("Enter an operation (+, -, *, /): ")
num1 = float(input("enter 1st number: "))
num2 = float(input("enter 2nd number: "))

if operation == "+":
    result = num1 + num2
    print(round(result, 3))
elif operation == "-":
    result = num1 - num2 
    print(round(result, 3))
elif operation == "*":  
     result = num1 * num2 
     print(round(result, 3))
elif operation == "/": 
    result = num1 / num2
    print(round(result, 3))
else:
    print(f"{operation} is not a valid operator")
