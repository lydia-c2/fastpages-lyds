<DOCTYPE html>
<html> 
    <head>
        <!-- title of game -->
        <title>Etch-A-Sketch</title>
    </head>

<script>
console.log("Hello, my name is Lydia!"); 
import turtle
green = turtle.Turtle()
screen = turtle.Screen()
green.goto(0,0)
def up():
  green.forward(10)
def down():
  green.backward(10)
def right():
  green.right(5)
def left():
  green.left(5)
def penup():
  green.penup()
def pendown():
  green.pendown()
screen.onkey(up,'Up')
screen.onkey(down,'Down')
screen.onkey(right,'Right')
screen.onkey(left,'Left')
screen.onkey(penup,'u')
screen.onkey(pendown,'d')

screen.listen()
</script>
<html>
