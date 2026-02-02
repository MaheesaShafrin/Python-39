# Python-39
 Python program to draw a circle of squares using Turtle
import turtle
x=turtle.Turtle()
def square(angle):
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle+10)
for i in range(36):
    square(90)
 
Output:

<img width="409" height="413" alt="Screenshot 2025-12-19 133631" src="https://github.com/user-attachments/assets/772d3bc3-41d1-4683-a5be-b593b30a9452" />
