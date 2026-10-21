---
tags:
  - grade9
  - unit2
  - solutions_of_equations
aliases:
theme: foundational mathematics
Unit: solutions of equations
status: done
---
#grade9 #unit2 #solutions_of_equations
# Equations Involving Exponents and Radicals

Equations are qualities of expression.

When the variable in use has an exponent other than 1, it is called _Equations Involving Exponents_.

**Example:** Solve:

a. $\sqrt{x} = 3$  
b. $x^3 = 8$  
c. $2^x = 16$

**Solution a:**

$\sqrt{x} = 3$

Square both sides:

$x = 3^2$
$x = 9$

Then $x$ is 9.

**Solution b:**
To solve $x^3 = 8$ for any real number a and B, if $a^n = b$ then $a$ is the $n$th root of $b$.

$x^3 = 8$

$x = \sqrt[3]{8} = 2$

**Solution c:**
To solve $2^x = 16$: express $2^x = 16$ as $2^x = 2^4$

In $2^x = 2^4$, the bases are equal and hence the exponents must be equal.

Therefore, $x = 4$.

**Rule**: For $( a > 0 )$, $( a^x = a^y )$ if and only if $x = y$.

**Example 1**: 

Solve $( 3^{2x+1} = 3^{x-2})$.

**Solution**: 

*Rule:* Since $( 3 > 0 )$, $( 3^{2x+1} = 3^{x-2} )$, if and only if the exponent, $(2x+1 = x-2)$.

$2x + 1 = x - 2$

$x = -3$

---

**Example 2**

a. $2^{x+2} = 2^{2x+1}$

**Solution**: 

$2^{x+2} = 2^{2x+1}$

Since$(2)^{x+2} = (2)^{2x+1}$:

$x+2 = 2x+1$

$x = 1$

b. $3\left(3^{2x}\right) = 3^{2x+5}$

**Solution**: 
$3 \left( 3^{x^2} \right) = 3^{2x+5}$

$3 \cdot 3^{x^2} = 3^{2x+5}$

$3 \cdot 3^{x} = 3^{2x+5}$

$3^1 \cdot 3^{2x+5}$

So,

$x = 3 \left( 2x+5 \right)$

$x = 6x + 15$

$x - 6x = 15$

$-5x = 15$

$x = -\frac{15}{5}$

$x = -3$


# System of Linear Equation **in Two Variables**

- For a real **a** and **b**, any equation in the form of $Ax + B = 0$ where $A \neq 0$ is called a **linear equation In one variable**

## Linear Equation in two variables

- One variable **can** be reduced to the form $Ax + b = 0$. What do you think is the solution if the equation is $y = 2x + 1$?

**Example:** $y = 2x + 1$, where **y** values: 0, 1, 2.

**Solution**

  - When $y = 0$, $0 = 2x + 1 \implies x = -\frac{1}{2}$
  - When $y = 1$, $1 = 2x + 1 \implies x = 0$
  - When $y = 2$, $2 = 2x + 1 \implies x = \frac{1}{2}$

- For each value of **y** there is a corresponding value of **x**. This solution is represented by $(x, y)$:

$$
\left\{ \left( -\frac{1}{2}, 0 \right), (0, 1), \left( \frac{1}{2}, 2 \right) \right\}
$$

![[Pasted image 20240912211516.png]]

## System of *linear equations* and their **Solution**

- A set of two or more linear equations is called a **system of linear equations**.
- System of two linear equations in two variables can be represented as:

$$
\begin{cases}
  a_1 x + b_1 y = C_1 \\
  a_2 x + b_2 y = C_2
\end{cases}
$$

where $(a_1, a_2, b_1, b_2, C_1)$ and $(C_2)$ are all different from zero.

 **Example**

$$
\begin{cases}
  2x + 3y = 8 \\
  5x - 2y = 1
\end{cases}
$$

 **Solution**

The set:

$$\left\{(0, \frac{8}{3}), (1,2), (2, \frac{4}{3}), (\frac{2}{3}, \frac{2}{3}), (4,0)\right\}$$ contains solutions of $(2x + 3y = 8)$.


The set:

$$\left\{(0, -\frac{1}{2}), (1,2), (\frac{9}{2},3), (3,7), (4, \frac{19}{2})\right\}$$ contains some solutions of $(5x - 2y = 1)$.

Therefore, the solution is $((1,2))$.

**Solutions**

Solving system of linear equations through:

- **Graphical method**
- **Substitution methods**
- **Elimination methods**

When we draw the lines of each of the component equations in a system of two linear equations, we can observe three possibilities:

1. **Two lines intersect at one point**, in this case, the system has **one** solution.
2. **The two lines are parallel**, in this case, the system has **no solution**.
3. **The two lines are coincident** (fit over each other), in this case, the system has **infinite solutions**.


### Graphical Method

- We need to draw the lines of each component equation using the same coordinate system.
- If the lines **intersect**, there is **one solution**.
- If the lines are **parallel**, there is **no solution**.
- If the lines are **coincident**, there are **infinite solutions**.

Example:
$\begin{cases}2x - 2y = 4 \\3x + 4y = 6\end{cases}$

Solution:

First, draw the graph:
![[Pasted image 20240912212059.png]]

- **In the Graph**, the two lines are intersecting at **(2, 0)**. Thus, the system has one solution **(2, 0)**.

### Substitution Method

- To solve by **substitution method**, follow these steps:

  - **Step 1**: Take one of the equations from the system. Write one of the variables in terms of the other.
  - **Step 2**: Substitute your result into the other equation and solve the second variable.
  - **Step 3**: Substitute this result into one of the equations and solve the first variable.

**Example Solve**
$$
\begin{cases}
2x - 3y = 5 \\
5x + 3y = 9 
\end{cases}
$$

**Solution Step 1**: $2x - 3y = 5$ and solve $(y)$ in terms of $(x)$

$$
3y = 2x - 5 
$$

Hence $( y = \dfrac{2x - 5}{3} )$

**Step 2**: Substitute $( y = \dfrac{2x - 5}{3} )$ in $( 5x + 3y = 9 )$, solve $(x)$:

$$
5x + 3 \left(\dfrac{2x - 5}{3}\right) = 9
$$

$$
5x + 2x - 5 = 9 
$$

$$
7x - 5 = 9 
$$

$$7x = 14$$

$$x = 2$$

**Step 2**: Substitute $x=2$, and solve for the remaining $y$.
$$2(2) - 3y = 5$$
$$4 - 3y = 5$$
$$-3y = 5 - 4$$
$$-3y = 1$$
$$y = -\frac{1}{3}$$

Therefore, the solution is $\left( 2, -\frac{1}{3} \right)$.

### Elimination Method

_To solve by elimination method, follow these steps:_

**Step 1**: Select one variable, and make the coefficient of 
the selected variable equal but opposite in sign in the two equations.

**Step 2**: Add the two equations to eliminate the *selected variable* and solve for the resulting variable.

**Step 3**: Substitute this result again into one of the equations and solve for the remaining variable.

**Example**: Step 1, select one variable. Let's say $x$, and make the coefficient of $y$ opposite to the other by multiplying the first equation by 3.

$$\left\{
\begin{array}{l}
3(2x - y = 5) \\
2x + 3y = 9
\end{array}
\right.$$

Becomes:

$$\left\{
\begin{array}{l}
6x - 3y = 15 \\
2x + 3y = 9
\end{array}
\right.$$

**Step 2:** _Add two equations in the system._

$$
\left\{
\begin{array}{l}
6x - 3y = 15 \\
2x + 3y = 9 \\
\end{array}
\right.
$$

$$
\frac{8x}{8} = \frac{24}{8} \Rightarrow \underline{x = 3}
$$

**Step 3:** _Substitute to solve for $y$._

$$
2x - 3y = 5
$$

$$
2(3) - 3y = 5
$$

$$
-3y = 5 - 6
$$

$$
-3y = -1
$$

$$
\frac{-3y}{-3} = \frac{-1}{-3} \Rightarrow y = \frac{1}{3}
$$

_Therefore, the solution is $(3, \frac{1}{3})$._

# Solutions of a system of linear equations in two variables and systems of coefficients


1. if $\frac{a_1}{a_2} = \frac{b_1}{b_2} = \frac{c_1}{c_2}$ _this has infinite solutions._

    - Every ordered pair that satisfies one consistent equation also satisfies the second, the such system is said to be **dependent**.

2. if $\frac{a_1}{a_2} = \frac{b_1}{b_2} \neq \frac{c_1}{c_2}$  _This has no solution._

    - This means the two concurrent equations do not have a common solution. It is said to be **inconsistent**.

3. if $\frac{a_1}{a_2} \neq \frac{b_1}{b_2}$ _This has one solution._

 - This means there is one ordered pair that satisfies both equations. This is said to be **independent**.
   
   **Example:**
   $$
   a,\begin{cases} 
   2x + 3y = 1 \\ 
   x - 2y = 3 
   \end{cases}
   \quad \quad
   b,\begin{cases} 
   3x - 2y = 2 \\ 
   x-6y = 3 
   \end{cases}
   \quad \quad
   c,\begin{cases} 
   x + y = 3 \\ 
   2x + 2y = 6 
   \end{cases}
   $$

**A Solution**
- The ratio of coefficients gives:
  $$
  \frac{2}{1} = \frac{3}{2}, \text{ therefore, one solution}.
  $$

**B Solution**
- The ratio of coefficients gives:
  $$
  \frac{3}{1} = \frac{-2}{-6} \neq \frac{2}{3}, \text{ therefore, no solution}.
  $$

**C Solution**
- The ratio of coefficients gives:
  $$
  \frac{1}{2} = \frac{1}{2} = \frac{3}{6}, \text{ therefore, infinite solutions}.
  $$



### *Equations Involving Absolute Value*

- If $( x)$ is a point on a number line with coordinate $( a )$, then the distance of $( x )$ from the origin is called the **absolute value** of $( x )$, denoted by $|x|$
- **Example** the numbers $(2)$ and $(-2)$ are located on the number line at equal distance from the origin. Hence, $(|2| = |-2| = 2)$.

    $\begin{align*}a. & -5 \\b. & 7 \\c. & -0.5 \end{align*}$

**Solution**:

$\begin{align*}A. & | -5 | = 5 \\B. & | 7 | = \quad 7 \\C. & |-0.5| = 0.5 \end{align*}$

- The absolute value of $x$ denoted by $|x|$ is defined as:

$$
|x| =
\begin{cases} 
x \text{ if } x \ge 0 \\
-x \text{ if } x < 0 
\end{cases}
$$

- **Example** \(3, -2\)

**Solution**:
$\begin{align*}A. & \text{ Since } 3 \ge 0, |3| = 3 \\B. & \text{ Since } -2 < 0,|-2| = -(-2) = 2 \\C. & -0.4 < 0, |-0.4| = 0.4 \end{align*}$

- For any **real** number $( x )$, $(|x| = |-x|)$
- For any **real** number $( x )$, $(|x|)$ is **always** **non-negative**
- **Distance** is **always non-negative**

- The distance $( D )$ in the location of any **two** real $( x )$ and $( y )$ is $|x - y|$ or $|y - x|$

    **Example**: $|3 - 9| = | -6 | = 6)\quad  or \quad(|9 - 3| = | 6 | = 6$

- For any **non-negative** number $( a )$

    $|x| = a \text{ means } x = a \text{ or } x = -a$

 Example

a. $|x-2|=3$ means $x-2=3$ or $x-2=-3$.

- $x=5$ or $x=-1$.

b. $|x+4|=5$ means $x+4=5$ or $x+4=-5$.

- $x=1$ or $x=-9$.


**example**

- Solve: $|2x-3|=5$ means $2x-3=5$ or $2x-3=-5$.

  $x=4$                               $x=-1$

- $|2(4)-3|=5$                   $|2(-1)-3|=5$

- $|5|=5$                               $|-5|=5$

- $5=5$                                  $5=5$

- Since $|x|$ is always non-negative, $|x|=5$ has no solution.

- Since $|x|$ is always non-negative, $|2x+3|=-3$ has no solution.


 **For any real number $a$, $|x|=|a|$ means $x=a$ or $x=-a$.**

**example**

a. $|x-1|=|2x+1|$

**Solution:**

- $|x-1|=|2x+1|$ means $x-1=2x+1$ or $x-1=-(2x+1)$.

- $x-2x=1$ or $x+2x=1$.

- $-x=2$ or $3x=0$.

- $x=-2$ or $x=0$.


### Properties of Absolute Value

For any real number $x$ and $y$:

1. $|x| \leq |x|$

2. $|x|y| = |x||y|$

3. $\sqrt{x^2} = |x|$

4. $|x+y| \leq |x| + |y|$ **(Triangle Inequality)**

    A. If $x$ and $y$ are both non-negative or negative: $|x+y| = |x| + |y|$

    B. If one of $x$ or $y$ is positive, the other is negative: $|y| < |x| + |y|$

5. If $y \neq 0$, then $\left| \frac{x}{y} \right|=\left| \frac{y}{x} \right|$

6. $-|x| \leq x \leq |x|$



# Quadratic equations

>[!note] For $a, b,$ and $c$ any equation that can be related to the form:$$ ax^2 + bx + c = 0 $$where $a \neq 0$ is called a **quadratic equation**.

**Example:** 

$$ x^2 + 3x - 2 = 0, \quad 3x^2 + 2x - 1 = 0, \quad (x+3)(x+2) = 7, \text{ etc.} $$

- We will discuss these major quadratic equations solving methods:
  - **Method of Factorization**
  - **Method of Completing the Square**
  - **General Formula**


> [!Expressions]- expressions are One combination of various terms that can be represented as a product of variables, or numbers and variables.

**Example:** $$ x^2, \ 2x^2, \ 2x^2 + 4x \cdot 2, \ (x-1)^2 + 6x, \text{ etc.} $$


## Factorizing Expression

- Is expressing as a product of its simplest form.
**For Example:**

Factorize $2x^2 - 9x$
**Solution:** 

The two terms, $2x^2$ and $-9x$, have $x$ as a common factor. Hence, 
$2x^2 - 9x$

can be factored as $$x(2x - 9)$$

**Factoring the Binomials of Two Squares**

*If you multiply* $(x + 2)$ *and* $(x - 2)$, *we see that* 
$$(x + 2)(x - 2) = x^2 - 4$$

- In general, $$x^2 - a^2 = (x - a)(x + a)$$
Example: 
$$x^2 - 9 = x^2 - 3^2 = (x - 3)(x + 3)$$


**Factoring Trinomials**

To factorize a trinomial: $$ax^2 + bx + c$$ by grouping terms. *If you are able to find two numbers, $p$ and $q$, such that* $p + q = b$ *and* $pq = ac$

Example: 
$$x^2 + 5x + 6$$

**Solution:** Find two numbers whose sum is $5$ and the product is $6$, which are $2$ and $3$. So, the equation can be rewritten as:

$$x^2 + (2x + 3x) + 6$$  
$$= (x^2 + 2x) + (3x + 6)$$  
$$= x(x + 2) + 3(x + 2)$$
$$= (x + 2)(x + 3)$$

**Example 1:** $$ x^2 + 4x + 4 $$
$$ = x^2 + (2x + 2x) + 4 $$

$$ = (x^2 + 2x) + (2x + 4) $$

$$ = (x + 2) + 2(x + 2) $$

$$ = (x + 2)^2 $$

Such expression are called **perfect Square**.

#### **Solving Quadratic Equations Using Methods of Factorization**

Let $ax^2 + bx + c$ be expressible as a product of two linear factors, say $(dx + e)$ and $(fx + g)$ where $d, e, f, g$ are real numbers.

Such that $d ≠ 0$ and $f ≠ 0$.

Then $$ ax^2 + bx + c = 0 $$ becomes:

$$ (dx)(fx + g) = 0 $$

So, $dx = 0$ or $fx + g = 0$ which gives:

$$ x = -\frac{g}{f} $$

**For Example:** 

$x^2 - 5x + 6$ 

can be expressed as:

$$ (x - 2)(x - 3) = 0 $$

Thus, 

$$x - 2 = 0 \quad or \quad x - 3 = 0$$

So,

$$ x = 2 \quad or\quad x = 3 $$ are the two solutions.


**In order to solve this kind of factorization, follow these steps:**

i. clear all Square Roots (if any)
ii. Write the equation in standard form of $p(x) = 0$
iii. Factorize the left-hand side into products of two linear factors.
IV. Use the 'Zero-product Rule' to solve the equation.

>[!Note] : *Zero-product Rule*:
> If $( A )$ and $(B)$ are two proper options and if $( A.B = 0 )$, then either $( A = 0 )$ or $( B = 0 )$ or both $( A = 0 )$ and $( B = 0 )$.

**Example**:  
$4x^2 - 16 = 0$

$-4x^2 - 16 = 0$ is the same as $$( 2x - 4)(2x + 4) = 0 )$$
$$
(2x - 4)(2x + 4) = 0
$$

$$( 2x - 4 = 0 )\quad or \quad ( 2x + 4 = 0)$$

$$x = 2 \quad \text{or} \quad x = -2$$

## **completing the Square Method**

It is not **convenient** to solve a quadratic equation by **factorization method**.

**For example:**

$$ x^2 + 8x + 20 = 0 $$

The left-hand side of the equation means $$x^{2} + 8x + 4 = 0$$
You need to find two factors whose sum is 8 and product is -4. But that is not possible in this case.

$$x^{2} + 8x + 4 = 0$$  
$$x^{2} + 8x = -4$$
 
$$\left( \frac{3}{2} \right)^{2} = 16 \text{ on both sides}$$  $$x^{2} + 8x + 16 = -4 + 16$$
  $$(x + 4)^{2} = -4 + 16 = 12$$
  $$\sqrt{12} = 2\sqrt{3}$$

Then, from $$x = -4 \pm \sqrt{12} \quad or \quad x = -4 \pm 2\sqrt{3}$$this is known as **completing the square method**



**Common Steps**

1. In Common, go through the following steps:
   - **Write** the equation in standard form.
   - **Make** the coefficient of $x^{2}$ unity, if it is not.
   - **Shift** the constant term to H.S. (Right Hand Side).
   - Add $\left(\frac{1}{2} \cdot \text{coefficient of } x\right)^{2}$ on both sides.
   - Express **LHS** as a perfect square of suitable binomials (i.e., use the reverse method) and simplify the **RHS**.
   - take square root on both sides.
   - Obtain the value of $( x )$ by shifting the constant term from $LHS$ to $RHS$.

Thus we need to add (or subtract) a perfect square, which is determined by using the following product formulas:

$$
x^2 + 2ax + a^2 = (x + a)^2
$$

$$
x^2 - 2ax + a^2 = (x - a)^2
$$

**Example:**

$$
3x^2 + 12x + 16 = 0
$$

We have:

$$
x^2 + 4x = -\frac{16}{3} \quad ( \text{Divide both sides by } 3)
$$

$$
x^2 + 4x + 4 = 0
$$

Thus:

$$
(x + 2)^2 = 2
$$

 *Then:*

$$
x + 2 = \pm \sqrt{2}
$$

Thus:

$$
x = -2 \pm \sqrt{2}
$$


### **Solving Quadratic Equations Using the Quadratic Formula**

To solve any quadratic equation of the form $( ax^2 + bx + c = 0 )$ (where $( a \neq 0 )$), by applying the methods of completing squares, you can conclude that:

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

 *If* $( b^2 - 4ac = 0 )$ *then it has one solution:*
$$ x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$

*If* $( b^2 - 4ac < 0 )$ *then i$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$ has no real s solutions:*


 If $b^2 - 4ac >0$ then  $x^2 = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$ represents two solutions 

   namely, $$x_1 = \frac{-b - \sqrt{b^2 - 4ac}}{2a}) \quad and \quad ( x_2 = \frac{-b + \sqrt{b^2 - 4ac}}{2a}$$
**How are there no real solutions?**

### Example 1:

   Solve  $3x^2 - 5x + 2 = 0$

   Let $( a = 3 ), ( b = -5 ), ( c = 2 )$

   $b^2 - 4ac$

   $= (-5)^2 - 4(3)(2)$

   $= 25 - 24$

   **Result:** $1 > 0$

   Therefore:

   $$ x = \frac{-(-5) \pm \sqrt{1}}{6} $$

   $$ = \frac{5 \pm 1}{6} $$

   Hence 

   $$ = \frac{5 + 1}{6} \quad \text{or} \quad \frac{5 - 1}{6} $$

   $$ = \frac{6}{6} \quad \text{or} \quad \frac{4}{6} $$

   $$ = 1 \quad \text{or} \quad \frac{2}{3} $$

### Example 2:
   Solve $x^2 - 8x - 16 = 0$

   So $b^2 - 4ac = (-8)^2 - 4(1)(-16) = 0$

   has only one solution because $( = 0 )$

### Example 3:
   Solve $-2x^2 - 4x - 92 = 0$

   So $-(1 - 4)^2 - 4(-2)(-9) = -56<0$

   Therefore, does not have real solutions.

## The relationship between The Coefficients of a Quadratic Equation and Its Roots

- the solution to a quadratic equation is sometimes called **roots**.

- The relationship between The sum and the product of those roots is called **Vieta's Theorem**.

>[!note] **Vieta's Theorem** 
>If the roots of $ax^2 + bx + c = 0, a \neq 0$ are 
$$x_1 = -\frac{b - \sqrt{b^2 - 4ac}}{2a}\quad and \quad x_2 = -\frac{b + \sqrt{b^2 - 4ac}}{2a}$$
then $x_1 + x_2 = -\frac{b}{a}$ and $x_1 \cdot x_2 = \frac{c}{a}$

### Example
 $-3x^2 + 8x + 5 = 0 \quad (A = 3, B = 8, C = 5)$

The sum is 
$$
-\frac{2}{3} = -\frac{b}{a} 
$$ 
and the product is 
$$
\frac{5}{3} = \frac{C}{a} 
$$