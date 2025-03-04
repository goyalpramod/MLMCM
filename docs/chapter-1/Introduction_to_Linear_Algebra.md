---
title: Introduction to Linear Algebra
parent: Chapter 1
nav_order: 2
---

Let us begin our journey of understanding Linear Algebra by first understanding what Linear Algebra means. 

Linear comes from the latin word *Linea* which means a line, in our case a straight line. Linear is nothing more than a straight line. 

Algebra is a complex word that simply means, we use different equations, operations, formulas to build relationship between different variables. 

So linear algebra boils down to building relationships between different lines using different equations, operations and formulas.

[IMAGE](Lines being added together)

Now that we understand what linear algebra means, how do we use it? First we need a place to draw our lines right. That's the coordinate system.  (Catesian plane)

It is a 2d grid. With an origin on which we can draw straight lines. 

[IMAGE](Coordinate system)

Now lets draw a line on it, and name it x.

[IMAGE](A line on coordinate system)

But how do we define our straight line x? Right now it's just a straight line, my friend can come along and draw another straight line and call it x. 

[IMAGE](Draw multiple x)

That is where we introduce coordinate points. These are like addresses, which define where does a straight line begin and where it ends. 

[IMAGE](Draw coordinates)

if we assume x and y axis are always fixed, we can see that. We have defined a fixed length for x. This is called the magnitude and if we take the angle x forms with the x axis, we can see that we have defined a direction as well. 

This is what is called a geometric vector. 

Different disciplines, call different things vectors and have different definitions. But I believe it all boils down to this simple definition. A vector is a straight line with defined magnitude and direction. And by the end of this chapter I will convince you to see it in the same light. 

[IMAGE](CS/physics/maths definition of vectors)

Even though we are more aligned to the mathematical and cs discipline. The physics definitions helps us connect vectors to the real world, and that is essentially what we want to do at the end of the day. Connect real world to mathematical abstractions. 

TALK ABOUT THE DIFFERENCE OF GEOMETRIC VECTOR AND CS/ML vectors 


We will jump between Geometric vectors and vectors throughtout the book and I will explicitly mention which one is being used at any given moment. There are rules that either of them need to maintain to be called by their names 

Geometric vector -> Must have a direction and a magnitude, Must follow the rule of triangle addition (or whatever it is called)
Vector -> Can be multiplied by a scalar

in code we can represent a vector as 

```python

```

