# Built-in Functions -Binary Conversion Using Built-in Functions in Python
# 🎯 Aim
To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

# 🧠 Algorithm
Assign the value 16 to a variable a.
Use the built-in bin() function to convert the number to binary.
Print the result.
# 🧾 Program
```
x=16
y=bin(x)
print(y)
```
# Output

![Screenshot 2025-05-15 151341](https://github.com/user-attachments/assets/d6d97c84-830f-4cf4-a20b-e24a3a36ac33)

# Result
Thus,the Python program to convert the number 16 into its binary representation using built-in Python functions is created successfully.

# Functions in Python: Modulo Calculator
# 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

# 🧠 Algorithm
Define a function called result that takes two arguments a and b.
Inside the function, compute the modulo using a % b.
Print the result of the modulo operation.
Get two integer inputs from the user.
Call the result function with the user-provided values.
# 🧾 Program
```
def result(a, b):
    modulo_value = a % b
    return modulo_value

a=int(input())
b=int(input())
print("modulo is", result(a, b))
```
# Output
![Screenshot 2025-05-15 151227](https://github.com/user-attachments/assets/fbc74548-1a80-4aba-a278-fb38edb82af8)


# Result
Thus,the Python program that defines a function which accepts two values and returns their modulo using the % operator is created successfully.

# Lambda Function in Python: Addition of Two Numbers
# 🎯 Aim
To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.

# 🧠 Algorithm
Get two integer inputs from the user.
Use a lambda function to define a function f that returns a + b.
Call the function with the user inputs and print the result.
# 🧾 Program
```
i=int(input())
j=int(input())
z=int(input())

f = lambda a, b,c: a+b+c

print(f(i, j,z))
```
# Output
![Screenshot 2025-05-15 151202](https://github.com/user-attachments/assets/ccf8a39e-beb0-4c88-b445-3ef6146f4ecb)



# Result
Thus,the Python program that defines a lambda function which takes two arguments a and b, and returns their sum is created successfully.

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python
This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

# 🎯 Aim
To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

# 🧠 Algorithm
Start the program.
Input the number of rows from the user.
Loop from 0 to the number of rows.
For each row:
Print appropriate spaces to shape the triangle.
Compute values using the formula:
[ C(n, k) = \frac{n!}{k!(n-k)!} ]
Print all rows of Pascal’s Triangle.
End the program.
# 🧪 Program
```
rows = int(input())
coef = 1

for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            coef = 1
        else:
            coef = coef * (i - j)//j
        print(coef, end = " ")
    print()
```
# Sample Output
![Screenshot 2025-05-15 151045](https://github.com/user-attachments/assets/ddb2f6f5-6797-40f6-8408-699d58cc99e1)


# Result
Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.

# Loops in Python: Palindrome Number Checker
 # 🎯 Aim
To write a Python program that checks whether a given number is a palindrome using loops.

# 🧠 Algorithm
Get input from the user and assign it to a variable num.
Assign the value of num to a temporary variable temp.
Initialize a variable rev to 0 (used to store the reversed number).
Use a while loop to reverse the digits:
While temp > 0:
rev = (10 * rev) + temp % 10
temp = temp // 10
After the loop, compare rev with num:
If equal, print that the number is a palindrome.
Else, print that it is not a palindrome.
# 🧾 Program
```
num=int(input())
rev=0
temp=num
while temp>0:
    rev=(10*rev)+temp%10
    temp//=10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
 print("The given number {} is not a palindrome".format(num))
```
# Output
![Screenshot 2025-05-15 151016](https://github.com/user-attachments/assets/8a70d0d0-b709-47b9-94fe-d663595621cc)


# Result
Thus,the Python program that checks whether a given number is a palindrome using loops is created successfully.

