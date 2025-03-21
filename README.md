# calculator.py

#Get the first 2 inputs
input1 = float(input("Enter the first number: "))
input2 = float(input("Enter the second number: "))
operator = input("Enter an operation (+, -, *, /): ")

# Perform the operation
if operator == '+':
    result = input1 + input2
    print(f"{input1} + {input2} = {result}")
elif operator == '-':
    result = input1 - input2
    print(f"{input1} - {input2} = {result}")
elif operator == '*':
    result = input1 * input2
    print(f"{input1} * {input2} = {result}")
elif operator == '/':
    if input2 != 0:
        result = input1 / input2
        print(f"{input1} / {input2} = {result}")
    else:
        print("Error:You cannot divide by zero.")
else:
    print("Invalid operation. Please enter +, -, *, or /.")
