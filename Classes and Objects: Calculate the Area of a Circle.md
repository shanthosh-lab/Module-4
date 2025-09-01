# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

from math import pi

class circle:

     def __init__(self,r):
     
         self.b=pi*r*r
         
         print("Area of circle: {:.2f}".format(self.b))
         
a = circle(int(input()))


## Output
<img width="686" height="287" alt="Screenshot 2025-09-01 180311" src="https://github.com/user-attachments/assets/a781ac1b-5b5f-424e-80ea-23706be6599e" />
## Result

Thus, a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation is verified.

