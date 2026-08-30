# Day 1 — Python Basics 

**Date:** August 30, 2026

### What I covered
- Variables (int, float, str, bool)
- input() and print()
- Type conversion (int(), float(), str())
- Arithmetic operators (+, -, *, /, //, %, **)
- Basic debugging

### Programs I built
1. Calculator
2. Age Calculator
3. Temperature Converter
4. Mad Libs
5. Score Average

### What I understood
- Variables store data
- input() gets user input
- print() displays output
- int is for whole numbers, float is for decimals


1. Simple calculator

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

print("Addition:", num1 + num2)
print("Subtraction:", num1 - num2)
print("Multiplication:", num1 * num2)
print("Division:", num1 / num2)

2. Age calculator

birth_year = int(input("Enter your birth year: "))
current_year = int(input("Enter the current year: "))

age = current_year - birth_year

print("Your age is:", age)

3. Temperature converter

celsius = float(input("Enter temperature in Celsius: "))

fahrenheit = (celsius * 9 / 5) + 32

print("Temperature in Fahrenheit:", fahrenheit)

4. Mad-Libs

name = input("Enter a name: ")
place = input("Enter a place: ")
animal = input("Enter an animal: ")
food = input("Enter a food: ")

print(name, "went to", place, "and saw a", animal)
print("Then they ate", food, "and went home.")

5. Basic Arithmetic Practice
 
a = 10
b = 3

print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)
print("Floor division:", a // b)
print("Remainder:", a % b)
print("Power:", a ** b)