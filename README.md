# MiniMaths
MiniMaths is a beginner-friendly Python calculator that performs basic arithmetic operations: addition, subtraction, multiplication, and division. It's a simple console-based tool designed to help new Python learners understand input handling, conditionals, and basic math logic.


a = float(input("Enter first number: "))
b = float(input("Enter second number: "))
op = input("Enter operator (+, -, *, /): ")

if op == '+':
    print("Result:", a + b)
elif op == '-':
    print("Result:", a - b)
elif op == '*':
    print("Result:", a * b)
elif op == '/':
    if b != 0:
        print("Result:", a / b)
    else:
        print("Cannot divide by zero")
else:
    print("Invalid operator")
