# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
a = int(input("Enter real part: "))
b = int(input("Enter imaginary part: "))

c = complex(a, b)

print("Complex number:", c)
print("Real part:", c.real)
print("Imaginary part:", c.imag)

## Output
Enter real part: 5
Enter imaginary part: 3
Complex number: (5+3j)
Real part: 5.0
Imaginary part: 3.0

## Result
Thus, the Python program successfully creates and displays a complex number along with its real and imaginary parts.
