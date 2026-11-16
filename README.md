#Write a Python program to print "Hello, Python!"
print("Hello, Python!")

#Store your name, age, and city in variables and display them.
name = "Rahul"
age = 25
city = "Jamshedpur"

print("Name:", name)
print("Age:", age)
print("City:", city)

#Take two numbers from the user and display their sum.
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

sum = num1 + num2

print("Sum:", sum)

#Take two numbers and display their addition, subtraction, multiplication, and division.
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)

#Write a program to calculate the area of a rectangle.
length = float(input("Enter length: "))
width = float(input("Enter width: "))

area = length * width

print("Area of Rectangle:", area)

#Write a program to calculate the area of a circle.
radius = float(input("Enter radius: "))

area = 3.14 * radius * radius

print("Area of Circle:", area)

#Write a program to convert Celsius into Fahrenheit.
celsius = float(input("Enter temperature in Celsius: "))

fahrenheit = (celsius * 9/5) + 32

print("Temperature in Fahrenheit:", fahrenheit)

#Take a student's name and marks and display the details.
name = input("Enter student name: ")
marks = float(input("Enter marks: "))

print("Student Name:", name)
print("Marks:", marks)

#Write a program to calculate Simple Interest using Principal, Rate, and Time.
p = float(input("Enter Principal: "))
r = float(input("Enter Rate: "))
t = float(input("Enter Time: "))

si = (p * r * t) / 100

print("Simple Interest:", si)

#Write a program to swap the values of two variables.
a = 10
b = 20

a, b = b, a

print("Value of a:", a)
print("Value of b:", b)


