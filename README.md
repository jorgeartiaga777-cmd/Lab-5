# Lab-5
# Part 1: Creating a Simple Function
def display_personal_info():
    print("--- Part 1: Personal Details ---")
    print("Name: Jorge Zander")
    print("Course: BS Computer Science")
    print()

# Part 2: Function with Parameters
def display_five_details(name, age, address, email, hobby):
    print("--- Part 2: Parameterized Details ---")
    print(f"Name: {name}")
    print(f"Age: {age}")
    print(f"Address: {address}")
    print(f"Email: {email}")
    print(f"Hobby: {hobby}")
    print()

# Part 3: Function with Return Value
def multiply_numbers(a, b):
    result = a * b
    return result # The purpose of return is to send the result back [cite: 20]

# Part 4: Function with User Input 
def compute_average():
    print("--- Part 4: Average Calculator ---")
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))
    num3 = float(input("Enter third number: "))
    avg = (num1 + num2 + num3) / 3
    print(f"The average is: {avg:.2f}\n")

# Part 5: Mini Project - Calculator  
def add(x, y): return x + y
def subtract(x, y): return x - y
def multiply(x, y): return x * y
def divide(x, y): return x / y if y != 0 else "Error: Division by zero"

def run_calculator():
    print("--- Part 5: Mini Calculator ---")
    n1 = 10
    n2 = 5
    print(f"Addition: {add(n1, n2)}")
    print(f"Subtraction: {subtract(n1, n2)}")
    print(f"Multiplication: {multiply(n1, n2)}")
    print(f"Division: {divide(n1, n2)}")

display_personal_info()
display_five_details("Jorge Zander", 20, "Nauring Pandan Antique", "jorgeartiaga777@gmail.com", "Coding")

product = multiply_numbers(10, 5)
print(f"--- Part 3: Return Value ---\nProduct: {product}\n")

compute_average()
run_calculator()
