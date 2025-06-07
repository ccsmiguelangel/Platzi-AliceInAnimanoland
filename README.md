# Platzi-AliceInAnimanoland

### Lesson 2 Part 1
**We will learn about:**
- transform
- transform-origin
- transform-style
- perspective
- perspective-origin
- backface-visibility

[Notion PDF](https://static.platzi.com/media/public/uploads/animaciones_5bda2325-fb2e-4060-9751-5863d226fcf1.pdf)
[Lesson 2 Part 1](https://platzi.com/cursos/transformaciones-transiciones-css/propiedades-para-crear-animaciones-con-css-y-propi/)


### Lesson 3 Part 1
**Definitions:**
- Trigger: Initiator of animations

We created the file pseudo-classes.html and pseudo-elements.html

## Lesson 4 Part 1
**Timing or easing functions**
Acceleration and Deceleration

Timing functions examples webpages:
[Easing Funcitions Cheat Sheet](https://easings.net/)
[Cubic Bezier](https://cubic-bezier.com/)

**Planes and axes**
- X-axis: Left and right
- Y-axis: Up and down
- Z-axis: Depth

**Stacking Context**
- Layers
- Hierarchy
- Z-index
- Overlap
- Order
- Depth
It's when you add a form inside another and you obtain independent movement.

## Lesson 5 and 6 Part 1
**Transform property and skew, rotate, scale values**
Transform can recive multiples values like:
transform: rotate(10deg);
transform: skew(10deg);
transform: scale(10deg)

New files are:
- transform-scale.html
- transform-skew.html
- transform-rotate.html

![Transform Examples](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExZDBuOGZnenZqdWhma2dnc2tobXQ1YWRzZ3U5cmRqOWJteGJhaWU4bCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/KRRSOKFINjskbRNENr/giphy.gif)

[UI Gradients](https://uigradients.com/)

## Lesson 7 Part 1
**Transform Origin**

This property is used to change the point of origin axes for the transformations. For example, when we use `transform-origin: left top;` the element rotates from its top-left corner insted of its center:


![Transform Origin Example](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGlyYzV0eXFobXdjeGtwMm16NWh5azd4ampnbTZ6M3J4bTIxNjlxeiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/a4fGwnTMq3MJMNZYQI/giphy.gif)

## Lesson 8 Part 1
**Transform Style and Perspective**

Introduction to 2D and 3D transformations, working with depth, planes and perspective points.

Here i add some property and values added in the course: 
- `perspective: 100px`
Adds depth of 100px to the element, creating a 3D space.
- `transform-style: preserve-3d;`
Define and maintains the 3D plane to childs elements.
- `transform: rotateX(50deg);`
Rotates the element 50° around the X-axis. Note: This transformation it's diferent in 3D plane.