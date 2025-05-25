Exp.No:4.a
CLASS AND OBJECTS - AREA OF CIRCLE
AIM
To write a Python program to take the radius from the user and find the area of a circle using the class name umbrella and function name rain.

ALGORITHM
Begin the program.
Create a class named umbrella.
Define a method rain(self, r) inside the class umbrella that accepts a radius r as an argument.
Inside the rain method:
Calculate the area of a circle using the formula:
[ \text{Area} = \pi \times r^2 ]
Use the math.pi constant to get the value of π and perform the calculation.
Print the result, formatted to two decimal places.
Prompt the user for an integer input to represent the radius of the circle.
Create an instance of the umbrella class and store it in the variable u.
Call the rain method of the umbrella class, passing the user-provided radius r as an argument.
Terminate the program.
PROGRAM
import math

class umberella:

def rain(self, radius):
    area = math.pi * radius ** 2  
    return area 
r= float(input())

u = umbrella()

print(f"Area of circle: {u.rain(r):.2f}")

OUTPUT
image

RESULT
Thus, Python program to take the radius from the user and find the area of a circle using the class name umbrella and function name rain was implemented successfully.
