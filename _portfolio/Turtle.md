---
title: "Turtle"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/Python_Turtle_Codes.png'>"
collection: portfolio
---

```python
import turtle

bob = turtle.Turtle(shape='turtle')
bob.speed(0)

colors = ["red", "orange", "yellow", 
              "green", "blue", "purple"]

for i in range(360):
        bob.color(colors[i % 6])
        bob.forward(i * 1.5) 
        bob.left(59)

turtle.exitonclick()
