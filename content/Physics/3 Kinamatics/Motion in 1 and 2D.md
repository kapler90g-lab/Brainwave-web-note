---
tags:
  - grade11
  - unit3
  - motion_in_one_and_two_dimensions
aliases:
theme: kinematics
Unit: motion in one and two dimensions
status: done
---
 #grade11 #unit3 #motion_in_one_and_two_dimensions


## **uniformly accelerated motion**

#### *Introduction*

- **Position** is the specific location of an object relative to a chosen reference point.  It identifies as a point in space where the object is located.
- **Distance** is the total path length traveled by an object between two or more positions, regardless of direction.
- **Displacement** is the shortest straight-line distance between two specific positions(initial and final positions) in a specific direction. It indicates where an object is relative to its starting position after moving.
![[Pasted image 20250218180833.png|200]]
- **Speed**: The rate at which an object covers distance over time.
- **Velocity** is similar to speed but includes direction. It is the rate of change of displacement over time, specifying both magnitude and direction.

#### *Acceleration*

- **Acceleration** is the rate of change of velocity or change in velocity per unit of time. It is a vector quantity with an SI unit of $m/s^2$.

- A negative acceleration may or may not be **deceleration**.
    - If the velocity and acceleration have the same sign (negative or positive) and are in the same direction, it is speeding up thus accelerating. But if they have different signs and directions then the object is decelerating (slowing down).
    - so an object is *accelerating* or speeding up if its **velocity is in the same direction as the acceleration** and it might be **positive or negative sign as the sign doesn't tell the magnitude** it tells the direction its moving **relative to a fixed reference frame**.
    - an object is *decelerating* or slowing down **if the velocity and the acceleration of that object are in different directions** it also might have positive or negative signs.

#### *Average acceleration*

- $\vec{a}_{\text{av}}$ is defined as the ratio of the change in velocity $\Delta \vec{V} = \vec{V_f} - \vec{V_i}$ to the time interval $\Delta t = t_2 - t_1$.
    $$\vec{a}_{\text{av}} = \frac{\vec{V_f} - \vec{V_i}}{\Delta t}$$
#### *Instantaneous acceleration*

- $\vec{a}_{\text{in}}$ is the **acceleration of an object at some instant in time.**
- that is by using the rate of change of velocity when the rate of change of time approaches zero.
    $$\vec{a}_{\text{in}} = \lim_{\Delta t \to 0} \frac{\Delta \vec{V}}{\Delta t}$$
#### *Motion with a Constant Acceleration*

- In many common types of one-dimensional motion, the acceleration is assumed to be uniform or constant.
- It means that the velocity of an object changes by an equal amount in equal time intervals and this is know as **a uniformly accelerated rectilinear motion.
     - **uniformly accelerated** meaning the velocity of an object changes by an equal amount in equal time intervals.
     - **rectilinear motion** meaning motion in a one-dimensional straight line.
- In this case, the average acceleration is equal to the instantaneous acceleration, and the average velocity is the average of the initial and final velocities.
$$ V_{av} = \frac{V_s + V_f}{2} $$
## **Equations of Uniformly Accelerated rectilinear Motion**

#### *derivations of equations of motion*
<div class="ai-divider"></div>
When an object moves in a straight line with **constant acceleration**, we can derive a set of equations that describe its motion. These equations relate four key variables:  

- $u$ (initial velocity)  
- $v$ (final velocity)  
- $a$ (acceleration)  
- $s$ (displacement)  
- $t$ (time)  

lets drive the equations:

Acceleration ($a$) is defined as the **rate of change of velocity** with respect to time:  
$$a = \frac{v - u}{t}$$
Rearranging this equation to solve for the final velocity ($v$), we multiply both sides by $t$:  
$$v = u + at$$
 **This is the first equation of motion:**  
$$\boxed{ v = u + at }$$

<div class="ai-divider"></div>


From the definition of displacement:  
$$s = v_{av} \cdot t$$
For uniformly accelerated motion, we take the average of initial and final velocities:  
$$v_{av} = \frac{u + v}{2}$$
Substituting this into the displacement equation:  

**this is the second equation:
$$s = \boxed{\left( \frac{u + v}{2} \right) t}$$
<div class="ai-divider"></div>

Now, using the first equation of motion, $v = u + at$, we substitute $v$ into this equation:  
$$s = \left( \frac{u + (u + at)}{2} \right) t$$
$$s = \left( \frac{2u + at}{2} \right) t$$
Expanding the expression:  
$$s = \left( u + \frac{1}{2} at \right) t$$
$$s = ut + \frac{1}{2} a t^2$$
**This is the third equation of motion:**  
$$\boxed{ s = ut + \frac{1}{2} a t^2 }$$

<div class="ai-divider"></div>


Now, let's derive another form of the displacement equation, expressing it using $v$ instead of $u$.  

From the first equation of motion:  
$$t = \frac{v - u}{a}$$
We substitute this into the equation:  
$$s = \left( \frac{u + v}{2} \right) t$$
$$s = \left( \frac{u + v}{2} \right) \left( \frac{v - u}{a} \right)$$
Expanding:  
$$s = \frac{v^2 - u^2}{2a}$$
Rearranging:  
$$v^2 = u^2 + 2as$$
 **This is the fourth equation of motion:**  
$$\boxed{ v^2 = u^2 + 2as }$$
<div class="ai-divider"></div>

We derive another equation for displacement by eliminating $u$.  

From the first equation:  
$$u = v - at$$
Substituting into the equation $s = ut + \frac{1}{2} a t^2$:  
$$s = (v - at) t + \frac{1}{2} a t^2$$
Expanding:  
$$s = vt - at^2 + \frac{1}{2} a t^2$$
$$s = vt - \frac{1}{2} a t^2$$
 **This is the fifth equation of motion:**  
$$\boxed{ s = vt - \frac{1}{2} a t^2 }$$
<div class="ai-divider"></div>


| Equation                            | Missing quantity                               |
| ----------------------------------- | ---------------------------------------------- |
| $$ V_f = V_i + a t $$               | Displacement ($\mathbf{s}$)                    |
| $$ V_{av} = \frac{V_f + V_i}{2} $$  | Displacement($\mathbf{s}$), acceleration, time |
| $$ s = \frac{(V_f + V_I)}{2} t $$   | Acceleration ($\mathbf{a}$)                    |
| $$ s = V_i t + \frac{1}{2} a t^2 $$ | Final velocity ($\mathbf{V_f}$)                |
| $$ s = V_f t - \frac{1}{2} a t^2 $$ | Initial velocity ($\mathbf{V_i}$)              |
| $$ V_f^2 = V_i^2 + 2 a s $$         | Time ($\mathbf{t}$)                            |

---

#### *Stopping Distance Equation*

> The **stopping distance** of a moving object (like a car) is the total distance it travels **from the moment a driver perceives a hazard to the moment the object comes to rest**.

It consists of two physically distinct parts:
$$
\boxed{d_{\text{stop}} = d_{\text{reaction}} + d_{\text{braking}}}
$$
---

##### *1. Reaction Distance*

This is the distance traveled **while the driver is reacting**, before braking begins.

If:

* **(v)** = initial speed
* **($t_r$)** = reaction time

Then:
$$
d_{\text{reaction}} = v , t_r
$$

No deceleration yet — the object continues at **constant velocity**.

---

##### *2. Braking Distance*

Once braking begins, the object **decelerates uniformly** until it stops.

We use the kinematic equation:
$$
v^2 = v_0^2 + 2a x
$$
At stopping:

* Final velocity ($v = 0$)
* Initial velocity ($v_0 = v$)
* Acceleration ($a = -|a|$) (negative because it slows down)

So:
$$
0 = v^2 - 2|a|, d_{\text{braking}}
$$
Solving:
$$
d_{\text{braking}} = \frac{v^2}{2|a|}
$$
---

**Full Stopping Distance Formula**
$$
\boxed{
d_{\text{stop}} = v t_r + \frac{v^2}{2|a|}
}
$$
---


* **First term (($vt_r$))** → human limitation (reaction delay)
* **Second term (($v^2/2a$))** → physics of braking

Notice:

* Reaction distance ∝ ($v$)
* Braking distance ∝ ($v^2$)

So:

> Doubling speed **doubles reaction distance** but **quadruples braking distance**

This is why high speeds are dangerous.

## **graphical representation of uniformly accelerated rectilinear motion.**

### *Displacement-time graphs*

- A **displacement-time** graph shows how *displacement* changes with *time*.
 - Displacement-time graphs show how far an object has moved from its starting point (displacement) and the time it took to move that distance.
    - **Y-axis represents displacement**: The vertical axis shows the distance from the start point, in meters.
    - **X-axis represents time**: The horizontal axis indicates the time, usually in seconds.

#### *the slope of a displacement-graph*

- *slope(gradient)* is the measure of the **steepness** of a graph and shows by what amount is one variable changing relative to the other.
$$\text{Slope} = \frac{\text{rise}}{\text{run}} = \frac{\text{Vertical increase}}{\text{Horizontal increase}} = \frac{s - s_0}{t - t_0}$$
![[Pasted image 20250317174343.png|400]]
 
$$\text{gradient} = \frac{\Delta s}{\Delta t} = \frac{\text{change in displacement}}{\text{change in time}}=\text{velocity}$$
- **Velocity** can be calculated by dividing the change in displacement by the change in time. On a graph, this calculation is represented by the **gradient**.
- so the slope of a displacement-time graph is *velocity* of the motion.


#### **Displacement-time graph for uniform rectilinear motion**

For a body moving at **constant velocity (uniform motion**), its graph of *displacement against time is a straight line with a constant slope/gradient*. This is because **distance is directly proportional to time** ($s = Vt$)

#### **Displacement-time graph for uniformly accelerated rectilinear motion**

For a body moving at **constant acceleration**, its graph of displacement against time is a **parabola (curved upward**), This is because *distance is directly proportional to the square of time($s\propto t^2$)* In the case where the **slope is increasing** (sloping up or getting steeper),**velocity is increasing resulting in a positive acceleration**.

-  **Displacement-time graph for uniformly decelerated rectilinear motions** is the case where the velocity of an object is decreasing thus slope is decreasing, resulting to a *deceleration*.


- **Shape of the graph**: 
    - A **straight flat horizontal line** indicates **no movement(object is at rest and at the same place over time)**, 
    - a **straight sloping line** indicates **constant velocity**, 
    - and a **curve shows** **changing velocity** (acceleration or deceleration).

![[Pasted image 20250317181217.png]]


### *Velocity-time graph*

- A velocity-time graph shows how velocity changes with time. 
- velocity-time graphs show how quickly an object is travelling (velocity) against time.
- -**Y-axis represents velocity**: The vertical axis shows the velocity of the object, in meters per second.
- **X-axis represents time**: The horizontal axis indicates the time, usually in seconds.
- the slope of the velocity-time graph sows the **acceleration**.
$$\text{slope} = \frac{\text{Vertical increase}}{\text{Horizontal increase}} = \frac{\Delta v}{\Delta t}= \text{acceleration}$$
 So, the slope of a velocity-time graph represents the **acceleration** of the motion. Because the slope is the same at all points on this graph, the **acceleration is constant**.  

We can also get the **displacement** traveled from the velocity vs. time graph by finding the **area** of the region between the line and the time axis.  

- The slope of a velocity-time graph gives the **acceleration**.  
-  The area between the velocity-time graph and the **time** axis gives the **displacement** of the object.  
![[Pasted image 20250317193812.png]]

- **Shape of the graph**: 
- A straight horizontal line indicates constant velocity, 
- a straight sloping line indicates constant acceleration, 
- and a curve shows variable acceleration.

![[Pasted image 20250317193624.png]]
### *acceleration-time graph*

An acceleration-time graph shows how acceleration changes with time.

we will only deal with objects moving at a constant acceleration; thus, all acceleration-time graphs are parallel to the time axis.the figure below shows the acceleration vs. time graph of:

- (a) uniform motion
- (b) uniformly accelerated motion
- (c) uniformly decelerated motion

![[Pasted image 20250317200720.png]]


## **vertical motion**

#### *Free Fall*

 When things move **vertically either up or down** under the **force of gravity alone**, the resulting motion is called *free fall*. 
 
- acceleration of a freely falling body is constant and is known as **acceleration due to gravity**, denoted by the letter **g**.

 when air resistance is negligible, all objects dropped under the influence of gravity near Earth's surface fall toward Earth with a **constant acceleration**. Near the surface of the Earth its magnitude is constant and is equal to $9.8 m/s^2$. 

-  velocity of the falling ball is increased uniformly through time and hence it is **accelerating**.

> expression freely falling object doesn't necessarily refer to an object dropped from rest. A **freely falling object** is any object moving **freely under the influence of gravity alone**, regardless of its initial motion. Objects thrown upward or downward and those released from rest are all considered **freely falling**.

- the equations of motions used to discuss about horizontal motion can also be used to describe motion in a vertical direction with just a minor and essential changes, those changes are :

     - acceleration is always a constant number and it is called **a gravity** and is equal to $9.8m/s^2$ thus, **a(acceleration)** is replaced by **g(gravity)**.
     - a **horizontal displacement** is changed by a vertical one called **height** thus, **s(displacement)** is changed by **h(height)**.
     - and depending one the direction of the velocity the gravity might be positive or negative.  
         - gravity is always directed downward towards the earth surface. if the object is going downward the gravity and the velocity are in the same direction thus, the it is positive.
         - if the object is thrown upward the direction will be opposite to gravity thus it is negative.

the table summarizing the equations of motion for a freely falling body:  

| **Equation**     | **Falling Down (Acceleration & velocity in Same Direction, $g$)** | **Moving Upward (Acceleration Opposite to velocity, $-g$)** |
| ---------------- | ----------------------------------------------------------------- | ----------------------------------------------------------- |
| **1st Equation** | $v = u + g t$                                                     | $v = u - g t$                                               |
| **2nd Equation** | $h = u t + \frac{1}{2} g t^2$                                     | $h = u t - \frac{1}{2} g t^2$                               |
| **3rd Equation** | $v^2 = u^2 + 2 g h$                                               | $v^2 = u^2 - 2 g h$                                         |
| **4th Equation** | $h = v t - \frac{1}{2} g t^2$                                     | $h = v t + \frac{1}{2} g t^2$                               |
| **5th Equation** | $h = \frac{(u+v)}{2} t$                                           | $h = \frac{(u+v)}{2} t$                                     |
those equations are vector equations and requires the consideration of direction for vector quantities such as velocity, acceleration and displacement.


### *terminal velocity*

**Friction** is a force that opposes the movement between two surfaces in contact. It comes in two forms:

- **Contact friction** – occurs between solid surfaces
- **Fluid friction or drag** – occurs between a solid object and a fluid (like liquids and gases)

When a solid body is inside a liquid or gas, its entire surface is in contact with the particles of the fluid- For this reason, during its motion in a fluid, the body experiences a **resistive force**. these resistance force which the **fluid exerted on the body** is called **fluid friction or drag force.**

when an object is falling in the air it moves under the action of two forces:
- downward **gravitational force** (its weight)
- upward **drag force(fluid friction)**

Drag, specifically, works **against the direction of an object’s motion**. Important characteristics of drag include:

- It **increases** as the object's **velocity increases**.
- It is affected by the **properties of the fluid**( thickness and viscosity)
- and also affected by the **aerodynamics of the object**(like shape and size )

![[Pasted image 20250319104422.png]]
**Terminal velocity** is achieved when an object’s **gravitational force and the opposing drag force** balance each other out, resulting in a **constant velocity**.

for a falling body to reach terminal velocity it **occurs in three stages:**

1. **Initial Acceleration:**  
   - At the start, the **gravitational force (mg) is greater** than the fluid friction (drag force) because the velocity at the starting point is smaller, $mg>{F_d}$.  
   - The object accelerates downward, increasing its velocity.  

2. **Increasing Drag Force:**  
   - As velocity increases, **drag force** also **increases** because the drag force and the velocity are directly proportional .  
   - The net force acting on the object **gradually decreases**, leading to **slower acceleration**.  

3. **Terminal Velocity:**  
   - Eventually, the **drag force equals the gravitational force**$F_d = mg$.  
   - At this point, **acceleration becomes zero**, and the object **falls at a constant velocity**, called **terminal velocity**.

**terminal velocity** is defined as the point at which the velocity of a falling object is **no longer getting greater**. An object at terminal velocity has **zero acceleration** because terminal velocity is at constant velocity(uniform motion).

>Terminal velocity is the **maximum velocity** of a freely falling body where its velocity no more increases, or the acceleration of the motion is zero.


>[!important]- Galileo Galilei
>![[Generated_Image_March_19__2025_-_11_40AM.png-removebg-preview.png|400]]
>- **Aristotle’s Theory**: Ancient Greek philosopher Aristotle (384–322 B.C.) believed that heavier objects fall faster than lighter ones.
>- Galileo Galilei (1564–1642), an Italian physicist and astronomer, **disproved** this by demonstrating that **all objects fall at the same acceleration in a vacuum**, regardless of their mass or size. He showed that the force of gravity acts equally on all objects, making their acceleration independent of mass. 
>- Galileo established the correct mathematical law of acceleration, which states: $$\text{Distance fallen} \propto time^2$$ Meaning, if an object falls freely from rest, the distance it covers increases in proportion to the square of the time.
>- Galileo also investigated the motion of an object on an inclined plane, established the concept of relative motion, invented the thermometer, and discovered that the motion of a swinging pendulum could be used to measure time intervals. 
>- After designing and constructing his own telescope, he discovered four of Jupiter's moons, found that our own Moon's surface is rough, discovered sunspots and the phases of Venus, and showed that the Milky Way consists of an enormous number of stars.
>- He is also known for the assertion that the Sun is at the center of the Universe (the heliocentric system), not Earth.




## **Uniformly Circular Motion**

>a **uniform circular motion** It is a special type of **curvilinear motion** in which the object moves in a circle with a *constant speed* but **constantly changing direction**.

### *Angular and tangential displacement*

#### *angular displacement*

*angular displacement* is the measure of how much an object has **rotated** relative to its **initial orientation**.

- just like how a linear Displacement measures the **shortest Straight line distance** in between two points, **Angular displacement** measures the **shortest angular distance** in between **two Orientation**,**angular displacement** is all about **orientation change**.
- Just like linear displacement ignores the actual path taken (it only cares about the start and end points), angular displacement only cares about the **initial and final orientation**, not how it got there.

>thus, **Angular displacement** is the **shortest angular distance** between two orientations. It tells you how much an object has rotated, without worrying about the actual path taken.

- though angular displacement doesn't measure the actual path taken, You can use **the relationship between the central angle( angular displacement) and the arc length** to find the actual curved path traveled
$$ \text{arc length(s)} \propto \text{centeral angle}(\theta) $$
$$ s \propto \theta \rightarrow s=r\theta $$$$\text{Angular displacement} (\theta) = \frac{\text{arc length (s)}}{\text{radius (r)}} \quad $$
$$\boxed{ \theta = \frac{s}{r}}$$
After **one complete revolution**, the rotating object will travel a distance equal to the **circumference** of the circular path. Which is equal to $2\pi r$ where $r$ is the radius.


**Therefore,**  
$$\theta = \frac{s}{r} = \frac{2\pi r}{r} = 2\pi \text{ radians}$$
Thus, **1 rev = $2\pi$ rad = 360°**.  

![[Pasted image 20250319183650.png]]

The unit of angular displacement in the SI system is **radian**. Since angular displacement is the ratio of these two quantities(length-to-length ratio), hence it is dimensionless.

#### *Tangential displacement* 

 **Tangential displacement** is essentially the **chord length** between two points on a circular path.  If an object moves **partially around the circle**, the tangential displacement is **the straight-line distance between the start and end points**, not the curved path
 
Tangential displacement **depends on the chord length** of the circular motion, not the arc length. The formula for the **chord length** (straight-line distance between two points on a circle) is:
$$d = 2r \sin\left(\frac{\theta}{2}\right)$$
1. **If the radius $r$ increases, the tangential displacement $d$ also increases** for the same angular displacement $\theta$.  
   - This is because the chord (straight-line distance) stretches outward as the circle gets bigger.  
2. **If $\theta$ increases (larger angular displacement), the tangential displacement increases** up to a point.
   - At $\theta = 180^\circ$ (π radians), the displacement is maximum ($d = 2r$).  
   - Beyond $180^\circ$, the displacement starts decreasing again.  
3. **If $\theta = 0^\circ$ or $\theta = 360^\circ$, the tangential displacement is zero** because the object is at the same point.  

>so, **Tangential displacement** is the **straight-line distance** (chord length) between the initial and final positions of a rotating object.

but the cord length becomes the tangential displacement when it is equal to the arc length in most cases the tangential velocity is taken as the arc length of the circle.


Tangential displacement ($\Delta s$) is the **distance traveled along the circular path** by a rotating object. It is equivalent to the **arc length** ($s$) swept by a point on the rotating object.  

The arc length ($s$) is given by:  
$$s = r \theta$$
- **$s$** = Tangential displacement (arc length)  
- **$r$** = Radius of the circular path  
- **$\theta$** = Angular displacement (in radians)  


- **Tangential displacement is a linear measure** (measured in meters).  
- **It depends on angular displacement**: If an object rotates by $\theta$ radians, its **tangential displacement** is the corresponding **arc length**.  
-  **Only valid for circular motion**: If the object moves in a straight line, tangential displacement would just be regular linear displacement.


### *Angular and Tangential Velocity*

#### *angular velocity*

**Angular velocity** Denoted by $\omega$ (omega) is defined as the **rate of change of angular displacement** with respect to time. 
It describes how fast an object rotates around a specific axis. measures the rate at which an object rotates, or changes its angle, over time.
$$\omega = \frac{\Delta \theta}{\Delta t}$$
   the SI unit of angular velocity is **radian per second(rad/sec)** and It is a vector quantity.
   
The direction of angular velocity is determined by the **right-hand rule**:

 1. Point the fingers of your right hand in the direction of the rotation.
 2. Curl your fingers in the direction of rotation.
 3. Your thumb will point in the direction of the angular velocity vector.

The **direction of angular velocity** is not the direction in which the object is actually moving through space. Instead, it represents the **direction of the axis of rotation**. Specifically, the direction of the angular velocity vector indicates the axis around which the object is rotating, and its direction follows the **right-hand rule**.

#### *Tangential velocity*

**Tangential velocity** ($v_t$​) is the  **instantaneous linear velocity** of a point on a rotating object, directed **tangentially** to its circular path. It represents how fast the point is moving **along** the circle at any given moment.

> tangential velocity is the **rate of change of tangential displacement over time**.  

Since **tangential displacement** ($s$) is the **arc length** traveled by a point on the rotating object, tangential velocity is given by:  
$$v_t = \frac{\Delta s}{\Delta t}$$
This equation shows that **tangential velocity is the average rate of change of tangential displacement**.  and the SI unit is in m/s because it is the linear or translational velocity of an a rotating body

  - After one complete revolution, the **tangential displacement** is equal to the **circumference** of the circle.
  - And the **time for one complete** revolution is called the **period**, $T$.
$$ \therefore  S = 2\pi r \quad t = \Delta T \quad V_t = \frac{2\pi r}{\Delta T}$$
>**tangential velocity** is always **perpendicular** to the circles *radius*.

#### *The relationship between angular and tangential velocity*

imagine that you are on two circles; one as big as the Earth and one as small as a coin.

1. **Angular Velocity Perspective (The Circle Rotates You)**  
   - Imagine you are standing on both circles, and they both rotate at **1 revolution per minute**.  
   - No matter the size of the circle, both complete **one full rotation in the same amount of time**.  
   - This means they **have the same angular velocity** ($\omega$) since angular velocity is defined as:  
     $$\omega = \frac{\theta}{t}$$  
     where $\theta$ is angular displacement (radians) and $t$ is time.  

2. **Tangential Velocity Perspective (You Move Around the Circle)**  
   - Now, instead of thinking about the circle rotating you, imagine **you are running around the edge** of both circles, trying to complete one full revolution.  
   - On the **larger circle**, you have a much bigger distance to cover per revolution.  
   - On the **smaller circle**, the distance is shorter, so you don’t have to move as fast.  
   - This shows that **tangential velocity depends on the radius**:  
     $$v_t = r\omega$$  
   - The bigger the radius, the faster you must move to complete a revolution in the same time.  

>but  both tangential and angular velocity exist at the same time for any object rotating around a circle and the relationship can be driven as:

   - **Average tangential velocity** is defined as:  $$v_{\text{avg}} = \frac{\Delta s}{\Delta t}$$
   - Substituting $s = r\theta$:  
     $$v_{\text{avg}} = \frac{r\Delta \theta}{\Delta t}$$  
   - Since **angular velocity** is defined as:  
     $$\omega_{\text{avg}} = \frac{\Delta \theta}{\Delta t}$$  
   - We substitute this into the equation:  
     $$v_{\text{avg}} = r \omega_{\text{avg}}$$  

- **If you see the circle rotating you, you describe angular velocity ($\omega$).**  
- **If you see yourself running around the circle, you describe tangential**
- **Both exist at the same time, but the way you describe them depends on perspective.**  

>Angular velocity is like the circle moving you, while tangential velocity is like you moving around the circle. The relationship is given by $v_t = r\omega$.

-  To find the **relation** b/w angular and tangential velocity, Let us first form the **equations** of tangential velocity!
-  Note that the angular velocity is equal for all rotating objects at the same point, and the tangential velocity depends on the projection or its distance from the axis of rotation. 

  $V_t = \frac{S}{t}$  where $S = \theta \times \text{Radius}$, 

  $V_t = \frac{\theta r}{t}$  where $\frac{\theta}{t}$ = $\omega$. So,

  $V_t = \omega r$

### *Centripetal acceleration*

**Centripetal acceleration** (also called **radial acceleration**) is the acceleration of an object moving in a circular path that always points **toward the center** of the circle. It is responsible for keeping the object in circular motion.

Even if an object moves at a constant **speed**, its **velocity** is always changing direction in circular motion. Since acceleration is the **rate of change of the magnitude/direction or both of velocity**, this change in direction means the object is **always accelerating** toward the center.

The **inward (centripetal) acceleration** is caused by a **force that acts along the radius** of the circle, which is why it is also called **radial acceleration**.

>so, Acceleration of an object moving in uniform **circular motion** is known as **centripetal acceleration.** **Centripetal** means center-seeking, or towards the center.

**Centripetal acceleration is always in the direction of the change in velocity.**

   - At any instant, the tangential velocity vector ($\vec{v}$) is **tangent to the circle**.  
   - A short time later, the **tangential velocity vector** has rotated slightly.  
   - The**change in velocity** ($\Delta \vec{v}$) is found by subtracting the initial velocity from the new velocity.  
   - **This change in velocity always points inward toward the center of the circle!**  
  -  **Since Acceleration Follows the Change in Velocity** Centripetal acceleration always points toward the center, because that’s the direction of the velocity change.  

 >Centripetal acceleration is always in the direction of the change in velocity because velocity changes direction in circular motion, and acceleration is defined as the rate of change of velocity
![[Pasted image 20250326215351.png]]

so centripetal acceleration is mathematically expressed as:
$$a_c = \frac{v^2}{r} \quad \rightarrow \quad a_c = \omega^2 r$$
and has a SI unit: $\text{m/s}^2$

### *Centripetal Force*

Centripetal force is the **net force required to keep an object moving in a circular path**. It acts **toward the center** of the circle and is responsible for maintaining circular motion.  

Using Newton’s Second Law ($F = ma$), and the formula for centripetal acceleration:
$$F_c = m a_c$$
Substituting $a_c = \frac{v^2}{r}$:
$$F_c = m \frac{v^2}{r}$$
Alternatively, using $a_c = \omega^2 r$:
$$F_c = m \omega^2 r$$
![[Pasted image 20250326215200.png|300]]
Centripetal force is **not a separate force on its own** but is supplied by other forces depending on the situation:  

- **Gravity** → keeps planets in orbit around the Sun.  
- **Tension** → in a string keeps a swinging object in circular motion.  
- **Friction** → keeps a car turning on a curved road.  
- **Normal force** → in roller coasters at loops.  

If centripetal force is removed, the object will **move in a straight line** due to inertia (Newton’s First Law).  


and its SI unit is $\text{Newton (N)} = \text{kg} \cdot \text{m/s}^2$

>The force which causes **centripetal acceleration** is called a **centripetal force**. 