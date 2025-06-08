try:
    num_1 = int(input("Please, enter the first number: "))
except ValueError:
    num_1 = "You can only enter a number"
    print(num_1)
    exit()

try:
    num_2 = int(input("Please, enter the second number: "))
except ValueError:
    num_2 = "You can only enter a number"
    print(num_2)
    exit()

operand = input("Please, enter one of the mathematical signs: +, -, *, /: ")

if operand == "+":
    result = int(num_1 + num_2)
    print(f"The result of the addition of {num_1} and {num_2} equals {result}")
elif operand == "-":
    result = int(num_1 - num_2)
    print(f"The result of the subtraction of {num_1} and {num_2} equals {result}")
elif operand == "*":
    result = int(num_1 * num_2)
    print(f"The result of the multiplication of {num_1} and {num_2} equals {result}")
elif operand == "/":
    try:
        result = int(num_1 / num_2)
        print(f"The result of the division of {num_1} and {num_2} equals {result}")
    except ZeroDivisionError:
        result = "You cannot divide by 0"
        print(result)
else:
    print("You can only enter one of the following mathematical signs: +, -, *, /")
    exit()
