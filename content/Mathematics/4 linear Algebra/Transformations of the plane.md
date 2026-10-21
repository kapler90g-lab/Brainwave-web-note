---
tags:
  - unit6
  - transformations_of_the_plane
  - grade11
aliases: 
theme: linear algebra
Unit: transformation of the plane
status: start
---
#unit6 #grade11 #transformations_of_the_plane 

>[!note]- rigid motion
> a motion that preserves shape, size and distance in between points on a plane is called a **rigid motion**
![[ChatGPT Image Apr 27, 2025, 12_35_57 PM.png|300]]
 > In a rigid motion a change in the position and direction of an object doesn't change the structural integrity of the object 
 > rigid motions move *plane figures* congruently; meaning the pre-image and the image of a triangle or a rectangle are congruent 
 > - there are **three** essential types of **transformation** within a rigid motion
 >    1. Translation
 >    2.  Reflection
 >    3. Rotation


## **Translation**

>  **Translation** is a transformation that occurs when every point of a plane figure is moved from one location to another location along the *along the same direction through the same distance*

### *point translation*

If point P is translated to point P', The straight path that connects **P** to **P'** showing both **direction** and **distance** — is called the **translation vector**.

- It tells you **which way** to go (direction) and **how far** to go (distance)

 **The translation vector PP'** says:

> Start at P, move exactly this far, and exactly this way, and you'll land at P'.

 And since **every point** on the figure follows the _exact same_ vector, the entire shape moves together perfectly — no bending or breaking.

---

- Let **T(a, b)** be a translation vector. Then:

    a. The origin is translated to **(a, b)** That means: **(0, 0) → (a,b)**
    b. The image of the point **P(x, y)** under the translation vector **T** will be the point **(x + a, y + b)**.
    
- For a **translation**:
    - the graph is **moved** (up or down, left or right) in the xy plane
        - Its position **changes**
        - the shape, size, and orientation of the graph remain **unchanged**

---

### *Line Translation*

Generally, a translation vector **T(a, b)** moves a point **P(x, y)** to a new point **P'(x', y')**.

The coordinates of the new point **P'(x', y')** are given by:

$$x' = x + a$$
$$y' = y + b$$

Suppose the original figure (say a line) had the equation:

$$y = mx + c$$

After a translation by **T(a, b)**:
- Every point $(x, y)$ becomes $(x', y') = (x + a, y + b)$.

Substituting $x = x' - a$ and $y = y' - b$ into the original equation:

$$y' - b = m(x' - a) + c$$

Expanding:

$$y' = m(x' - a) + c + b$$
$$y' = mx' - ma + c + b$$
$$y' = mx' + (b - ma + c)$$

**Thus,** the translated line still has **the same slope $m$**, but the y-intercept shifts by $(b - ma + c)$.

- A translation moves every point by the same horizontal and vertical shift.
- The shape and orientation stay the same — only the position changes.
- For a line, the slope remains the same, but the y-intercept adjusts according to the translation.

### *circle translation*

