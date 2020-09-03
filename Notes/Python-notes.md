# Python Notes

### turtle
```
import turtle
wn = turtle.Screen()             # Set up the window and its attributes
wn.bgcolor("lightgreen")

tess = turtle.Turtle()           # create tess and set some attributes
tess.color("hotpink")
tess.pensize(5)                  # thicker

alex = turtle.Turtle()           # create alex

tess.forward(80)     
tess.pencolor("red")
tess.fillcolor("yellow")
```

### input
```
name = input("Enter your name: ")
```
## [String]
### capitalize()
```
name = 'alexander'              # 'alexander'
name.capitalize()               # 'Alexander'
```
```
x = "Alexander"
x[4]                           # 'a'
```
```
x.upper()                      # 'ALEXANDER'
x.lower()
```
```
x = "String Slicing"
x[0:6]                         #'String'
x[7:14]                        #'Slicing'
x[0:3]                         #'Str'
x[:6]                          #'String'
x[7:]                          #'Slicing'
```
```
x = "Alexander's String"
x.find("String")               #12
```

