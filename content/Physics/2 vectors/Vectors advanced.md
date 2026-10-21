---
tags:
  - grade11
  - unit2
  - vectors
aliases:
theme: vectors
Unit: vectors
status: done
---
#unit2 #grade11 #vectors  

### _Vectors and types of vectors_

> Vectors are physical quantities that can completely be described by both a magnitude and a direction with an appropriate measurement of units.

- Vectors can be represented in two ways either **algebraically** by using a bold faced letter or an arrow over the latter or **Geometrically** by using an _arrow or an arrow tipped line-segment_, the length of the arrow indicates the magnitude of the vector when drawn to scale and the head of the arrow indicates the direction of the vector.

#### _Types of vectors_

**Parallel vectors**: are vectors that have the exact same direction regardless of their magnitude.

- **Antiparallel vectors**: are types of parallel vectors but rather than having the exact same direction they have the exact opposite direction regardless of their magnitude.

both the parallel and antiparallel vectors can be described by a single equation:

$$ \overrightarrow{A}=k \overrightarrow{B} $$

where K is a non-zero constant that acts as a scaling factor in between the two vector:

- when $k > 1$ the two vectors are **parallel** and have the exact same direction.

- when $k<1$ the two vectors will eventually be **antiparallel** meaning they will have the exact opposite direction .

- when $k=1$ then a new type of vector called equal vectors will be formed

**Equal vectors**: are vectors that have the exact same direction and the exact same magnitude representing the exact same quantity.

**Collinear vectors**: are vectors that lie along the same line. when two or more vectors share the same line then they are known as **collinear vectors**

- collinear vectors are represented by the exact same equation as parallel and antiparallel vectors but what makes it different is that collinear vectors focus is not direction but the sharing of the exact same line. as we remember vectors that live on a line are $1D$ vectors and $1D$ vectors have only two possible direction either exactly to the right or exactly to the left giving them always a $180^0$ difference or a $0^0$ similarity in direction defaulting collinear vectors to be either parallel or antiparallel.

- meaning that all collinear vectors are parallel but not all parallel vectors are collinear. parallel vectors are collinear if and only if they share the same line.

**Co-planar vectors**: are vectors that lie in the same two-dimensional plane. if two vectors live on the same space but two different planes like $xy$ and $xz$ planes then this two vectors are not co-planar as they do not live on the same $2D$ plane.

**Zero vectors**: are vectors that have a magnitude of zero and no direction. this types of vectors occur when the head and the tail of the vector coincide on it self giving as a point.

**Orthogonal vector**: are vectors that are perpendicular to one another.

**Unit vectors**: are vectors that have a magnitude of 1 with some arbitrary direction. they are used when needing to focus on the direction of a vector only. Unit vectors are incredibly useful because they solely represent direction. Since their magnitude is always 1, they essentially tell you "which way" without indicating "how much." They are often used to define coordinate axes (like the i, j, and k vectors in 3D space) or to provide a direction for other vectors.

**Negative of a vector**: a vector that has the same magnitude to its counter part but exactly opposite direction then that vector is called the negative of the vector. for example the negative of a vector $\overrightarrow{A}$ is $-\overrightarrow{A}$ it has the same magnitude as $\overrightarrow{A}$ but exactly opposite direction. If a vector represents a displacement of 5 meters north, its negative represents a displacement of 5 meters south.

### _Algebraic method of addition of vectors in two dimensions_

#### _Adding two collinear vectors_

- operations like additions on scalars are as simple as adding the numbers of the same units as we are only dealing with magnitudes, but when it comes to vectors we need to account for the direction of the vector as well.

- adding two collinear vectors is the equivalent of doing operations on one dimension which opens up only to two possibilities either they are in the same direction or exactly opposite direction or the most **maximum and minimum** values of the operation.

- if we have two forces $\overrightarrow{F~1}$ and $\overrightarrow{F~2}$ acting along the same direction then the resultant vectors of those force will have a magnitude equal to the sum of the magnitude of the individual vectors and it is directed along the same direction of any one of the vectors. this is the **most maximum**

$$\overrightarrow{R}=\overrightarrow{F~1}+\overrightarrow{F~2}$$

- On the other hand, if the two vectors are acting on the opposite direction then their resultant will have a magnitude equal to the absolute value difference between the two vectors. this is the **most minimum**

#### _adding two perpendicular vectors_

- the rules of addition for vectors become more complicated when moving to planes or two dimensions the simplest of vector addition in 2D is **perpendicular vectors**.

- we need to use the acronym **GPT** to do any operation on two dimensional vectors, the G stands for **graphs** which mean we need to visualize the vectors where they are and how they are acting.

- the P stands for **Pythagorean**, once we know how the vectors are acting by graphing them we will need to find the magnitude of their resultant which takes us to the right angle created by the perpendicular vectors and the hypotenuse is the longest side of the triangle and it is also the resultant that is where the Pythagorean theorem comes in which says the square of the two sides of a right angled triangle is equal to the square of the longest side.

- and lastly we have the T which stands for **trigonometry**, this will help up find the direction of the vector which as we know is in terms of angles and trig deals with angles and thus will be used to find the direction of the resultant vector.

![[Pasted image 20250722142614.png|300]]

Pythagorean theorem: $$c^2=a^2+b^2$$

trigonometry: $$sin(\theta)=\frac{b}{R}$$ $$cos(\theta)=\frac{a}{R}$$ $$tan(\theta)=\frac{b}{a}$$

#### _Components of vectors_

- we have seen the way to add vectors using graphical methods(scale diagram) and using properties of right angled triangle but both of them have limits that is why we need to introduce a general and simple method to add vectors called **The component method**.

- The projection of vectors on the coordinate axes is known as **components of the vector**. the projection of vector $\overrightarrow{A}$ on x axis $\overrightarrow{A~x}$, is known as the x component of vector $\overrightarrow{A}$ and the projection of $\overrightarrow{A}$ on the y axis $\overrightarrow{A~y}$ is known as the y component of the vector $\overrightarrow{A}$.

- components $\overrightarrow{A~x}$ and $\overrightarrow{A~y}$ are not vectors but numbers but not vectors as they are the projection or shadow of the vector on the coordinate axis.

$$\overrightarrow{A} = \overrightarrow{A~x} + \overrightarrow{A~y}$$

- the magnitude of the components have a general magnitude of $\overrightarrow{A~x}=\overrightarrow{A}cos(\theta)$ and $\overrightarrow{A~y}=\overrightarrow{A}sin(\theta)$ and depending on the angle the components might be positive or negative.

- the process of breaking down a vector into its components is known as **resolution of a vector**.

- **components of a vector** are projections of vectors on the coordinate axes.

- in order to find a resultant of two or more vector acting in space using the component method we need to first break down a vector into its x and y components then we add the vector in the same x and y components which results in a massive right angle triangle created by breaking down the vector into its components then we use Pythagorean theorem and trig to find the magnitude and angle of the resultant vector.

- we use GCPT as an acronym where G stands for graphing, C stands for finding the components, P stands for Pythagorean and T stands for trignometery.

- so if we have two vectors $\overrightarrow{A}$ and $\overrightarrow{B}$ then to fins the resultant we need to first graph it correctly once that has been done we find the commponets of each of the vector:

$$\overrightarrow{A} = \overrightarrow{A~x} + \overrightarrow{A~y}$$

$$\overrightarrow{B} = \overrightarrow{B~x} + \overrightarrow{B~y}$$

- then we take each of the same components and we add then giving as the component of the resultant in that direction:

$$\overrightarrow{R~x} = \overrightarrow{A~x} + \overrightarrow{B~x}$$

$$\overrightarrow{R~y} = \overrightarrow{A~y} + \overrightarrow{B~y}$$

$$\overrightarrow{R} = \overrightarrow{R~x} + \overrightarrow{R~y}$$

- the magnitude of the resultnat R will be:

$$\overrightarrow{R} = \sqrt{\overrightarrow{R~x} + \overrightarrow{R~y}}$$

- and the direction of the vector will be:

$$tan(\theta)=\frac{\overrightarrow{R~x}}{\overrightarrow{R~y}}$$

as we said before based on the angle the components of a vector might be positive or negative:

- both the components are positive if the angle $\theta$ is above the x-axis.

- and when x component is negative but y is positive then the angle $\theta$ is above the negative x-axis.

- when both components are negative then the angle is below the negative x-axis.

- the x is positive and y is negative when both then the angle is below the positive x-axis.

### _Unit vectors_

> Unit vectors are vectors that have a magnitude of zero with some direction. this are vectors that exist for a purpose of only dealing with directions without considering the magnitude.

- on the coordinate axis we said that the components of a vector are number and not vectors well by attaching them with the corresponding unit vector we are able to provide it a direction making them a vector

- the unit vector in the direction of the x-axis is known as the i-hat and written as ($\hat{i}$) and the unit vector on the y-axis is known j-hat and is written as ($\hat{j}$).

- now for example the vector components of a vector $\overrightarrow{A}$ can be written as: $\overrightarrow{A~x}\hat{i}$ and $\overrightarrow{A~y}\hat{j}$.

$$\overrightarrow{A} = \overrightarrow{A~x}\hat{i} + \overrightarrow{A~y\hat{j}}$$

- but to find the unit vector along any direction we can use the principles of **normalization** to normalize the magnitude of the vector to one and we can do that by dividing the vector by its magnitude

$$ \overrightarrow{U}=\frac{\overrightarrow{A}}{|A|} $$

## **Products of vectors**