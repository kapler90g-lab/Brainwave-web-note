---
tags:
  - motion_in_stright_line_and_uniformaly_accelerated_motion
  - grade10
  - unit2
aliases:
theme: kinematics
Unit: motion straight line & uniformly accelerated motion
status: done
---
#motion_in_stright_line_and_uniformaly_accelerated_motion #grade10 #unit2 

>[!Important]- **Kinematics** 
>*Kinematics* is the branch of **classical mechanics** that describes the motion of points, objects, and systems of objects **without considering the forces that cause the motion**. It focuses on the relationships between displacement, velocity, acceleration, and time.

To describe motion, we need a **frame of reference**. A frame of reference is essentially a coordinate system used to define the position of an object. When an object changes its position relative to this frame of reference over time, it is in motion.

> **Motion** is the change in *position* of an object relative to some *reference frame* over *time*.

Motion can occur in one, two, or three dimensions:

- **One-dimensional motion**: Motion along a *straight line*. Examples include a car on a straight road or an object falling vertically.
- **Two-Dimensional Motion**: Motion in a *plane*. Projectile motion, like a thrown ball, is a common example where motion occurs both horizontally and vertically.


## **Motion in straight line**

### *Position(X)*

> **Position** An object's *location* in space relative to a chosen reference point.

- **Position** tells us where an object is. However, simply stating a location isn't enough; we need a basis for that location. This basis is the **reference point**.

> **reference point** Is a fixed point or object used as a basis for measuring and describing the position or motion of another object.

 - In physics, a reference point serves the same purpose – *it's a stationary location or object that we use to define the position of something else*. The choice of a reference point is **arbitrary**, meaning you can choose almost any point you like. However, the description of the object's position will depend on the reference point you choose.

- In one-dimensional motion, we often use a **number line or an axis to represent position**. The reference point is typically set at the *origin* (the zero point) of this axis. The position of an object is then given by its coordinate on this axis, along with a sign indicating its direction from the reference point (e.g., +5 meters to the right, or -3 meters to the left).

As an object **moves**, its position relative to the reference point changes over time. This change in position is what we call **motion**.

### *Distance and displacement*

> **Distance(s)** is the *total path length* traveled by an object until it reach its final destination or position.

- Distance is all about the about the length of the path you have chosen to travel and for a given path the distance you travel is always constant. 
$$ \text{total path length}= |B-A|+|C-B|+|D-C| = \text{distance(s)}$$
> **Displacement($\Delta{x}$)** Is the change in an object's position in a specific direction; the *shortest straight-line distance* between the initial and final positions.
$$\Delta{x} = x-x_o$$
where: $x$ is your final position  $x_o$ is your initial position 

- The sign of the displacement indicates the direction. A positive displacement usually means the object moved in the positive direction of your chosen axis, while a negative displacement means it moved in the negative direction.

- displacement is all about how far and in what direction your final position is relative to your initial position.

Here's a breakdown of the crucial differences between distance and displacement:

| Feature              | Distance                   | Displacement                                     |
| -------------------- | -------------------------- | ------------------------------------------------ |
| **Definition**       | Total path length traveled | Change in position (shortest straight-line path) |
| **Type of Quantity** | Scalar (magnitude only)    | Vector (magnitude and direction)                 |
| **Value**            | Always positive or zero    | Can be positive, negative, or zero               |
| **Dependence**       | Depends on the path taken  | Depends only on initial and final positions      |
| **Direction**        | No direction associated    | Has a specific direction                         |
![[Pasted image 20251202131939.png|490]]

Distance is a **scalar quantity** because it only has magnitude (how much ground was covered). Displacement, on the other hand, is a **vector quantity** because it has both magnitude (how far the object is from its starting point) and direction (in which direction it is from the starting point).

**Distance and displacement are only the same when an object moves in a straight line without changing direction**. If an object changes direction or returns to its starting point, the distance traveled will be greater than the magnitude of its displacement. If an object returns to its starting point, its displacement is zero, but the distance traveled is not.

### *Speed and Velocity*

> **speed** Is the rate at which an object covers a given *distance*. the rate of change of distance.

- it is determines how fast or how slow an object is moving by determining how much of the distance it is covering at a given duration of time. an object covering a distance of 100m at a rate of 10m/s it would reach the 100m mark before an object covering at just 2m/s.

> **Velocity** is the rate at which an object covers a given *displacement*. the rate of change of displacement.

- it determines how fast and in what direction an object is covering a given displacement, **it is the rate of change of position**.
- Velocity is a vector quantity and includes direction. As a car moves around a circular track, its direction of motion is continuously changing, even if its speed (the magnitude of the velocity) remains constant this is because changing direction indicates change in displacement and thus changing velocity.

The key difference between speed and velocity lies in whether or not direction is included. Speed only tells us _how fast_ an object is moving, while velocity tells us _how fast_ and _in what direction_ it is moving.

| Feature                 | Speed                      | Velocity                                           |
| ----------------------- | -------------------------- | -------------------------------------------------- |
| **Definition**          | Rate of change of position | Rate of change of position in a specific direction |
| **Type of Quantity**    | Scalar (magnitude only)    | Vector (magnitude and direction)                   |
| **Value**               | Always positive or zero    | Can be positive, negative, or zero                 |
| **Considers Direction** | No                         | Yes                                                |
| **Formula (Average)**   | $$V=\frac{S}{t}$$          | $$\overrightarrow V=\frac{\Delta x}{t}$$           |

#### *Average speed and instantaneous speed*

> **Average Speed** The total distance traveled divided by the total time taken. It gives an overall idea of how fast an object was moving over a period.
$$V_{av}=\frac{S_{tot}}{t_{tot}}$$
- average speed takes the entire distance covered by a body and the time it took to cover it to determine the general speed of the body.

> **Instantaneous speed** is the speed of an object at a specific instant in time. this tells us how fast an object was at a specific time. This is what a speedometer in a car measures.
$$V_{ins}=\frac{S}{t},\quad t \rightarrow0$$
#### *Average velocity and instantaneous velocity*

> **Average velocity** is the change in position divided by the change in time taken. It describes the overall change in position per unit time, including direction.
$$\overrightarrow V_{av}=\frac{\Delta x}{\Delta t}$$
- just like average speed, average velocity provides the over all rate of change of position but in specific direction.

> **Instantaneous velocity** The velocity of an object at a specific instant in time. It includes both the *instantaneous speed* and the direction of motion at that instant.
$$\overrightarrow V_{ins}=\frac{\Delta x}{\Delta t}, \quad \Delta t \rightarrow 0$$

For motion in a straight line in one direction without changing course, the *magnitude of average speed and average velocity will be the same*. However, if the object changes direction, the average speed will be greater than the magnitude of the average velocity because the total distance traveled per unit time will be greater than the magnitude of the displacement per unit time. but in case of instantaneous speed and velocity, *the magnitude of instantaneous velocity is always equal to the instantaneous speed*.

### *Acceleration*

let's introduce another key concept in kinematics: **acceleration**. Acceleration describes how an object's velocity is changing over time.

> **acceleration** is about *changing velocity*. This change can be in the magnitude of the velocity (speeding up or slowing down) or in the direction of the velocity (changing direction).

- *acceleration* tells us the rate at which an objects velocity changes at the first second an object might be traveling at 2m/s and then might **speed up(accelerating)** and go at 3/m/s at the fourth second or might **slow down(decelerating)** and go at 1m/s.

We can calculate the **average acceleration** of an object over a time interval using the following formula:
$$a_{av}=\frac{\Delta v}{\Delta t}=\frac{v-v_o}{t-t_o}$$
Where:

- ($a_{av}$) is the average acceleration
- ($\Delta v$) is the change in velocity
- ($\Delta t$) is the change in time (or the time interval)
- ($v$) is the final velocity
- ($v_o$) is the initial velocity
- ($t$) is the final time
- ($t_0$) is the initial time

### *Uniform rectilinear motion*

> The motion of an object in a **straight line (rectilinear)** with a **constant velocity (uniform)** is known as a **uniform rectilinear motion**.

- Such motion models describe a motion whose displacement changes at equal amounts in an equal time interval.
- the constraint of a constant velocity results in an acceleration that is zero meaning that the objects velocity doesn't change over time as by definition it is constant.
- the objects velocity at any instant in time is constant value meaning that the average velocity of the object is equal to the instantaneous.
$$\overrightarrow V_{av}=\overrightarrow V_{in}=v$$
Looking into the **position-time graph** and **the velocity time graph** which are graphs that tell us the position and the velocity of the object as a function of time.

The velocity vs time graph for uniform linear motion is a horizontal line, which indicates that the velocity does not change over time:

![[Pasted image 20260331201205.png]]

This indicate that any incremental change in the velocity at any small instant in time is zero, simply indicating that the velocity of the object doesn't change.
$$\frac{dv}{dt}=0 \quad (\text{constant veclocity})$$
As the object progresses covering its displacement over time the displacement it covers becomes larger and larger, meaning that if the velocity of the object was to be 3m/s at the 1st second it would covered 3m, at the 5th second it would covered 15m at the 10th second it would cover 30m and so on, and we can see that the increase between each consecutive second is equal to the magnitude of the velocity in this case 3, so the the amount of displacement the object is covering increase(decreases) at a linear rate, hence the position time graph of the object is a steeping straight line as shown:

![[Pasted image 20260331202454.png]]

This indicates that the rate at which the position changes is constant.
$$\frac{dx}{dt}=v$$
Here we see that the final position of an object depends upon two main things:

- **The initial position**($x_o$)
- **the displacement covered as a result of the velocity the object**

Mathematically,$$x=x_o+v\Delta t \qquad (eq. 1)$$
### *Uniformly accelerated motion*

> The motion of an object in **a straight line** with a **constant acceleration** is known as a **uniformly accelerated motion**

- a **constant acceleration** means that the object's velocity changes at equal amounts in an equal time interval.
- this means that the objects velocity becomes higher (lower) over time and the displacement covered increases(decreases) even more faster as the velocity is increasing(decreasing) over time.

Now looking into the **acceleration vs time graph**, the **velocity vs time graph** and the **position vs time graph**, gives us such properties:


he acceleration vs time graph for uniformly accelerated linear motion is a **horizontal line**, which indicates that the acceleration does not change over time. This should be obvious by now that we have seen the same exact thing but with constant velocities, a constant acceleration would mean that at any instant in time the acceleration is a constant value.
$$\frac{d\overrightarrow a}{dt}=0$$
![[Pasted image 20260331210347.png]]


As we have said the velocity of an object with a constant acceleration increases in equal amounts in an equal time interval, this indicates that the objects velocity increase(decrease) over time, if for example an object has a constant acceleration of $3m/s^2$ then at the first second its velocity is 3m/s, at the 2nd second it is 6m/s then 9m/s and so on meaning that the objects velocity increases(decreases) linearly over time, hence the velocity time graph is a straight line as shown:

![[Pasted image 20260331215152.png]]

This indicates that the rate at which the velocity is changing is constant: $$\frac{dv}{dt}=\overrightarrow a$$
Here we see that the final velocity of the object depends up on two main things:

- **the initial velocity of the object**($v_o$) 
- **the velocity as a result of the acceleration by the object**

Mathematically,$$v=v_o+\overrightarrow a \Delta t \qquad (eq. 2)$$ 

Let's consider a particle that moves in a uniformly accelerated linear motion. Let's say that this particle has a position $x_o$  at an instant $t_o$ and a position $x$ at a subsequent instant $t$

Since the **velocity of the particle changes linearly with time**, the average velocity ($v_{av}$) of the object can be given as the arithmetic mean of the initial and final velocity of the object: $$V_{av}=\frac{v+v_o}{2} \qquad (eq. 3)$$
by plugging in our final velocity we get: 
$$V_{av}=\frac{(v_o+a\Delta t)+v_o}{2}= \frac{2v_o+a\Delta t}{2}=v_o+\frac{1}{2}a \Delta t$$
Multiplying all by $\Delta t$ gives us:
$$V_{av}\Delta t = \Delta x=v_o\Delta t+\frac{1}{2}a \Delta t^2 \qquad (eq. 4)$$
This equation tells us that for a uniformly accelerated motion the displacement of the object is covered quadratically with time. As the objects velocity is increasing(decreasing) over time the displacement also will increase(decrease) even faster and as equation 4 tells us it increases(decreases) quadratically with time($s\propto t^2$) so the graph of the position time graph would be a quadratic one as shown:

![[Pasted image 20260331222403.png]]

This also tells us that the rate at which the displacement is covered is equal:
$$\frac{dx}{dt}=v_o+a\Delta t$$
From This graph we can see that equation 4 tells us that the final position of an object in a uniform acceleration motion depends upon this three main things:

- **the initial position of the object** ($x_o$)
- **the displacement gained as a result of the initial velocity** ($v_o\Delta t$)
- **the displacement gained as a result of the constant acceleration** ($\frac{1}{2}a\Delta t^2$)

Mathematically, $$x=x_o+v_o\Delta t +  \frac{1}{2}a\Delta t^2$$
| Symbol     | Variable          |
| ---------- | ----------------- |
| $x_o$    | Initial position  |
| $x$      | Final position    |
| $\Delta x$ | Displacement    |
| $v_o$    | Initial velocity  |
| $v$      | Final velocity    |
| $a$      | Acceleration      |

### *Equations of Uniformly accelerated motion*

This are around five sets of equations that are derived from our above discussion of Uniformly accelerated motion, the first two equations are used to drive variants of the equations that can be used when one of the variables are not known, the first two equations are the **core equations** and we have defined them our above discussion of Uniformly accelerated motion and the others are derived from these two equations and hence we can call them **derived equations**.

The two **core equations** are:

1. $$ v=v_o+\overrightarrow a \Delta t $$
2.  $$x=x_o+v_o\Delta t +  \frac{1}{2}a\Delta t^2$$
The **derived equations** on the other hand are:

3. $$ v^2=v_o^2+2a\Delta x $$
4. $$\Delta x=(\frac{v+v_0}{2})\Delta t $$
5.  $$x=x_o-v\Delta t +  \frac{1}{2}a\Delta t^2$$

###  *Relative Velocity in One Dimension (Constant Velocity)*

> Relative velocity describes **how fast and in what direction one object appears to move when observed from another moving object**.

Now rather than assuming the frame of reference is stationary we are gonna use a moving frame of reference but two things are always measured as an outside observer:

- **The velocities of the objects is measured to relative the ground**
- **The direction is already set independent of the individual objects if one is moving to the left then the velocities will have a negative indicating their direction of motion**.

assume two objects A and B with a constant velocity moving in the same direction in straight line and lets assume that A is faster than B, if we(in B) were the one measuring the velocity of A with respect to us in B then the velocity object A relative to be denoted ($v_{AB}$) is given by:

$$
v_{AB} = v_A - v_B
$$

This equation answers, “If I sit on B, how does A move relative to me?”, the equation always assumes that if we are the one measuring then we are stationary relative to the object we are measuring and the object is the one moving, and the direction in which it is matters.

#### *Case 1: Both Moving in the Same Direction*

$$
v_A > v_B > 0
$$
$$
v_{A/B} = v_A - v_B > 0
$$
* A moves **forward relative to B**
* B sees A moving **ahead**

Example:
$$
v_A = 10, \quad v_B = 7
\Rightarrow v_{A/B} = 3 \ \text{m/s}
$$
---

$$
v_B > v_A > 0
$$
$$
v_{A/B} < 0
$$
* A appears to move **backward relative to B**

 Example:
$$
v_A = 7, \quad v_B = 10
\Rightarrow v_{A/B} = -3 \ \text{m/s}
$$
---

$$
v_A = v_B
$$
$$
v_{A/B} = 0
$$
* A appears **stationary** relative to B

 Important insight:

> Same velocity → no relative motion

---

#### *Case 2: Moving in Opposite Directions*

Let:

* ($v_A > 0$)
* ($v_B < 0$)

Then:
$$
v_{A/B} = v_A - (-v_B) = v_A + |v_B|
$$
* Relative velocity becomes **sum of speeds**

 Example:
$$
v_A = 80, \quad v_B = -60
$$
$$
v_{A/B} = 140 \ \text{km/h}
$$
---


$$
v_B = 0
$$
$$
v_{A/B} = v_A
$$
* Ground observer case

$$
v_A = 0
$$
$$
v_{A/B} = -v_B
$$
* A sees B moving in **opposite direction**



The **sign** of relative velocity is crucial:

* **Positive** → A moves in the **chosen positive direction** relative to B
* **Negative** → A moves in the **opposite direction** relative to B


Switching to B’s frame:

* B becomes **stationary**
* A moves with velocity (v_A - v_B)

This is a **change of reference frame**, not a physical force.
