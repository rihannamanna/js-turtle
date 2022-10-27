# JS Turtle

## Background 
[Turtle graphics](https://en.wikipedia.org/wiki/Turtle_graphics) are vector graphics using a relative cursor (the "turtle") upon a Cartesian plane (x and y axis). 

This program is an environment to learn/teach programming with JavaScript language. Idea initialy comes from [Seymour Papert](http://www.papert.org/). Javascript version of turtle graphycs initialy started by  [bjpop](https://github.com/bjpop), than forked and developed and documented by [hanumanum](https://github.com/hanumanum). This version has been further modified by (philbowman)[https://github.com/philbowman]. [GitHub Repository is here](https://github.com/cs-acs/js-turtle).

The __turtle__ can move about the plane and has a few __attributes__: *location (x,y coordinates)*, *direction (angle the turtle is pointing)*, and *pen*.  

The __pen__ also has attributes: *color*, *width*, and *up/down state* (whether the pen will make a mark or not). Imagine a robot on wheels with a pen it can lift up and down.

## Getting started
Look over the [documentation](documentation.md) and try out the basic movements (`forward`, `left`, `right`, `angle`, `goto`, `colour`, `penup`, `pendown`). You can put these commands directly into the *Command* box or into the *Definitions* box. To run the demo program in the *Definitions* box, run the command `demo()`. You can also load the example scripts by copy/pasting their locations into the *Script* box, pressing *Load Script*, then *Run Script*. You can do this with your own external scripts too, but make sure that you include a function called `main()` because that is the function run when you click *Run Script*.

Play around and make some designs. Then, try these challenges:

* Draw a triangle whose vertices are in the bottom-left, bottom-right, and top-center of the canvas.
* Draw circles or other shapes of random sizes and locations all over the canvas.
* Recreate an 8-bit image like an original Mario sprite.
* Draw a snowman out of three circles: the largest circle sitting on the bottom of the canvas, and two more circles above it, each 3/4 the size of the one below it.

## Using loops
A loop in JavaScript looks like this:
```
for (var i = 0; i < num; i++)
```