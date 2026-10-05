---
title: "Turtle"
excerpt: >
  <strong>Python Turtle Graphics</strong><br/>
  <em>Using Python Turtle to create geometric patterns through loops, colors, and movement commands.</em><br/>
  <img src='/images/Python_Turtle_Codes.png'>
collection: portfolio
---

**Python Turtle Graphics**

*Using Python Turtle to create geometric patterns through loops, colors, and movement commands.*

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
