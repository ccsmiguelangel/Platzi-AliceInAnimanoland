# Platzi-AliceInAnimanoland

## Lesson 2 Part 1
**We will learn about:**
- transform
- transform-origin
- transform-style
- perspective
- perspective-origin
- backface-visibility

[Notion PDF](https://static.platzi.com/media/public/uploads/animaciones_5bda2325-fb2e-4060-9751-5863d226fcf1.pdf)
[Lesson 2 Part 1](https://platzi.com/cursos/transformaciones-transiciones-css/propiedades-para-crear-animaciones-con-css-y-propi/)


## Lesson 3 Part 1
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

## Lesson 9 Part 1
**Backface Visibility**
This property allows us to control the visibility of the back face of an element when it's rotated in 3D space.

It's like being able to see what's behind an element when we rotate it, similar to flipping a card to see its other side.

![Flipping a card](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExOG1jcmxjZmtkY2ZuNWs2ZGZnbnoxemRqbHBvc2czbGpsY3ZnOG93cCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Qg5PQDK1lLwMRCVGDU/giphy.gif)

## Lesson 10 and 11 Part 1
**Parallax Part 1**

Parallax is an effect where different elements or backgrounds move at different speeds, creating a sense of depth and dimension in the design.

![Parallax](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNzZrY3dqYXQwbG5nZWxoZXozZjNjYjU4OTl0dHp5c3Z3dzZ4eXEwNyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/K1F134Hj3JeQ8/giphy.gif)

**Paralax Part 2**
We implement css code to create a parallax effect. 

We use a "scale" transform to adjust the element size for transitions. The scale value is calculated using this formula:

`(Perspective (8px) - Translate (3px)) / Perspective (8px) = Scale Value (0.375) `

The teacher showed us a beautiful parallax example here:
[Beauty Parallax Blog](https://www.bustle.com/comics/why-pizza-is-your-real-bff-39351)

## Lesson 12 Part 1
**Transition Property and During**

### Properties:
- `transition-property`
Specifies which CSS property to animate.
- `transition-duration`
Defines how long the animation takes to complete
- `transition`
  Shorthand property that combines all transition properties

### Values:
Values syntax options:
- `transition: initial | inherit;`
- `transition: [property] [duration] [timing-function] [delay];`
- `transition-property: none | all | <property> | initial | inherit;`
- `transition-duration: <time> initial | inherit;`

We have added transition properties to all HTML test files in the folder.

[HTML Colors Codes](https://htmlcolorcodes.com/)

## Lesson 13 Part 1
**Timing function and delay**
`transition-timing-function`: sets timing function for transition accelerate.
- `ease`: Default value. The element accelerates gradually and decelerates.
- `ease-in`: the element starts slow but ends fast.
- `ease-out`: the element start quickly and decelerates but ends slowly.
- ease-in-out: Combines both ease-in and ease-out for a smooth transition.
- cubic-bezier: Custom timing function using two control points to create a specific acceleration curve. You can generate the formula hre: [Cubic Bezier](https://cubic-bezier.com/)

`transition-delay`: Sets the time to wait before starting the transitions after the trigger.

## Lesson 14, 15 and 16 Part 1
**UX Tips**
1. For Jump Animations (like in circle-jump file):
  - Start quickly and end slowly for a more natural feel.
  - Follows the principle of easing-out for a better user perception.
2. For Delays Timing:
  - Allow users time to understand the functionability on hover pseudo class element, for example.
  - Create a smooth user experience with appropriate waiting times.
3. Flickering on hover transitions:
  - Always wrap the animated element inside a container.
  - This prevents unwanted movement and a flickering screen.
  Example of the problem and solution: 
  [Flickering Example](https://codi.link/PGgzPk11ZXZlIGVsIGN1cnNvciBwb3IgZGViYWpvIGRlbCBwdW50bzwvaDM+DQo8ZGl2PjwvZGl2Pg==%7CZGl2IHsNCiAgd2lkdGg6IDEwMHB4Ow0KICBoZWlnaHQ6IDEwMHB4Ow0KICBiYWNrZ3JvdW5kLWNvbG9yOiBwdXJwbGU7DQogIGN1cnNvcjogcG9pbnRlcjsNCiAgb3BhY2l0eTogMC44Ow0KDQp9DQoNCmRpdjpob3ZlciB7DQogIHRyYW5zZm9ybTogdHJhbnNsYXRlWCg0NXB4KTsNCn0NCg0KaDM6OmJlZm9yZXsNCiAgY29udGVudDogIiI7DQogIGRpc3BsYXk6IGJsb2NrOw0KICB3aWR0aDogMTBweDsNCiAgaGVpZ2h0OiAxMHB4Ow0KICBiYWNrZ3JvdW5kLWNvbG9yOiByZWQ7DQogIGJvcmRlci1yYWRpdXM6IDUwJTsNCiAgcG9zaXRpb246IGFic29sdXRlOw0KICB0b3A6IDUwcHg7DQp9DQoNCg0K%7C)
  [Flickering Solution](https://codi.link/PGgzPk11ZXZlIGVsIGN1cnNvciBwb3IgZGViYWpvIGRlbCBwdW50bzwvaDM+DQo8ZGl2IGNsYXNzPSJjb250YWluZXIiPg0KICA8ZGl2IGNsYXNzPSJpdGVtIj48L2Rpdj4NCjwvZGl2Pg==%7CLyogRWxlbWVudG8gY29udGVuZWRvciAqLw0KLmNvbnRhaW5lciB7DQogIHdpZHRoOiAxMDBweDsNCiAgaGVpZ2h0OiAxMDBweDsNCiAgYm9yZGVyOiAxcHggZGFzaGVkIGJsYWNrOw0KICBjdXJzb3I6IHBvaW50ZXI7DQoNCn0NCg0KLyogRWxlbWVudG8gYSB0cmFuc2Zvcm1hciAqLw0KLml0ZW0gew0KICB3aWR0aDogMTAwcHg7DQogIGhlaWdodDogMTAwcHg7DQogIGJhY2tncm91bmQtY29sb3I6IHB1cnBsZTsNCiAgb3BhY2l0eTogMC44Ow0KfQ0KDQovKiBUcmlnZ2VyICovIA0KDQouY29udGFpbmVyOmhvdmVyIC5pdGVtIHsNCiAgdHJhbnNmb3JtOiB0cmFuc2xhdGVYKDQ1cHgpOw0KfQ0KDQpoMzo6YmVmb3Jlew0KICBjb250ZW50OiAiIjsNCiAgZGlzcGxheTogYmxvY2s7DQogIHdpZHRoOiAxMHB4Ow0KICBoZWlnaHQ6IDEwcHg7DQogIGJhY2tncm91bmQtY29sb3I6IHJlZDsNCiAgYm9yZGVyLXJhZGl1czogNTAlOw0KICBwb3NpdGlvbjogYWJzb2x1dGU7DQogIHRvcDogNTBweDsNCn0NCg0KDQo=%7C)
  ![Flickering light](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExMWFqM2p5MWhkM2pocXkxNnQyYnQwanowYmFtcmphNWdwMDVjNHp2ayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l0HlK709Xtsm3KdlS/giphy.gif)