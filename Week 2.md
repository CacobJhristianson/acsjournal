# Advanced Computer Journal

#### Jacob Christianson

---

## Week 2 Notes - Processing Videos

#### Video #1 - 3.1: Flow (setup and draw)

 Block of code

> {Code here}

Setup - Happens only once!

```processing
size(640, 360);
```

Draw - Forever

```processing
background(0);
rect(100, 100, 50, 20);
```



#### Video #2 - 3.2: Built-in Variables (mouseX, mouseY)

<u>Variables</u> - stores temporary data

Mouse Variables

- mouseX

- mouseY

- pmouseX

- pmouseY



#### Video #3 - 3.3: Events (mousePressed, keyPressed)

Syntax

> void <function name> () {
> 
> //Code here!!
> 
> }

Core events - `setup() `&  `draw()`

Mouse events

> void mousePressed() {}



#### Video #4 - 4.1: Variables

Circle animation

> Variables serve as a mechanism to keep track of circle position
> 
>     circleX - user defined   
> 
>     mouseX - built-in

Control flow

1. Declare the variable
   
   > type name;
   
   - Data types - int, float, etc.

2. Initialize the variable
   
   > int circleX
   
   - Use lowercase
   
   - Avoid globals - draw, setup, mousePressed, etc.

3. Use the variable!
   
   > Assignment operation
   > 
   > circleX = 50;

```processing
int circleX; //Decleration

void setup() {
    circleX = 50; //Intialization
}

void draw() {
    //Boilerplate code

    ellipse (circleX, 180, 24, 24); //Applying the variable!
}


```

#### Video #5 - 4.2: Incrementing a Variable

Coming up with an algorithm and implementing it into your code

```processing
void draw() {
    //Boilerplate code

    ellipse (circleX, 180, 24, 24); //Applying the variable!

    //circleX = circleX + 1; //1 represents speed
}
```

- Float values can be passed through functions

- Floating point allows for more precision

- Use for everything

#### Video #6 - 4.3: Using random()

`float random(int max)`

Returns a random number between 0 and the given maximum `max`
