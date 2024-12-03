import turtle
import random

colors = ["red", "green", "blue", "orange", "purple", "pink", "yellow"]

window = turtle.Screen()
window.bgcolor("lightgreen")

painter = turtle.Turtle()
painter.pensize(3)

def draw_square(t, size):
    for _ in range(4):
        t.forward(size)
        t.left(90)

def draw_circle(t, radius):
    t.circle(radius)

for i in range(36):
    color = random.choice(colors)
    painter.pencolor(color)
    draw_square(painter, 100)
    draw_circle(painter, 50)
    painter.right(10)
    painter.forward(10)

window.mainloop()
