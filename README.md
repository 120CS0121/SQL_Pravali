'''
******************* BASIC CALCULATOR ************************

Here we can find
1. Addition
2. Subtraction
3. Multiplication
4. Division of 2 Numbers

'''

print("+ Addition")
print("- Subtraction")
print("* Multiplication")
print("/ Division")

operator = input("Enter any Operator : ")
num1 = float(input("Enter Number 1 : "))
num2 = float(input("Enter Number 2 : "))

if operator == "+":
    print(num1, "+", num2, "=", (num1+num2))
elif operator == "-":
    print(num1, "-", num2, "=", (num1-num2))
elif operator == "*":
    print(num1, "*", num2, "=", (num1*num2))
elif operator == "/":
    if num2 == 0:
        print("Divide by 0. So it's an Error")
    else:
        print(num1, "/", num2, "=", (num1/num2))
else:
    print("Invalid Operator")

    
'''
***************** END OF THE PROGRAM *************************
'''

