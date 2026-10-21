---
tags:
  - relation_and_functions
  - grade10
  - unit1
aliases:
theme: relation and functions
Unit: relation and functions
status: done
---
#grade10 #relation_and_functions #unit1 
## Revision on Patterns

> A pattern is a sequence or an arrangement of shapes or numbers that are **predictable** because they follow a **rule**.

- In mathematics, patterns often involve numbers or shapes that change in a consistent way.

There different types of patterns that are based on the type of operations they follow:

- **Arithmetic patterns (also called arithmetic sequences)** are patterns where the difference between consecutive terms is constant. This constant difference is called the common difference.

- E.g. 2, 4, 6, 8, 10 (a common difference of 2)

- **Geometric patterns (also called geometric sequences)** are patterns where the ratio between consecutive terms is constant. This constant ratio is called the common ratio.

- E.g. 2, 4, 8, 16, 32.....

- Another type of pattern is a recursive pattern which is a pattern that depends upon the pervious two or more terms to predict the next one the initially given terms are known as the **initial condition** while the formula relating them is known as the **recursive formula**.

- the best example of this is the the Fibonacci sequence (1, 1, 2, 3, 5, 8, ...), where each number is the sum of the two preceding ones. This is a recursive pattern, not strictly arithmetic or geometric.

To create a table of values for a given algebraic expression. This is a way to represent a relationship between an input (usually denoted by 'x') and an output (usually denoted by 'y' or the expression's value) based on a rule defined by the algebraic expression.

For example, if the algebraic expression is \(y=2x+1\), we can choose some input values for x and calculate the corresponding output values for y.

- So we have the **Input** giving us the position of the term that follows a specific rule.

- **The rule** giving us that operations we apply upon the input to give us the output of it.

- The **output** gives us the corresponding term to the given position by the input.

Table of Values for y = 2x + 1

|           |            |
| --------- | ---------- |
| x (Input) | y (Output) |
| -2        | -3         |
| -1        | -1         |
| 0         | 1          |
| 1         | 3          |
| 2         | 5          |

This table shows the relationship between the input values of x and the output values of y based on the expression. This concept of input and output is fundamental to understanding relations and functions.

---

## Cartesian Coordinate System in Two Dimensions

This is a fundamental concept for understanding how to visualize relations and functions.

> The **Cartesian coordinate system**, also known as the **rectangular coordinate system**, is a way to uniquely identify every point in a plane by using two numbers, called **coordinates**. These coordinates represent the perpendicular distances of the point from two fixed perpendicular lines called the **axes**.

One of the best ways to think of the cartesian coordinate system is two number systems overlapping each other at a specific point that we call the origin, as we know the number line contains all the real numbers and hence can be thought to be as a set of all real numbers($\mathbb{R}$), Now if we were to take the cartesian product of sets containing all real numbers we would be able to get all the possible **ordered pair** of numbers($\mathbb{R} \times \mathbb{R}$) translating this into the the number lines it would mean that we would take two number lines and position them so that they can contain all the possible ordered pair of real numbers this would give up an infinite plain with the the possible ordered pair. By simply drawing a perpendicular line to a number on both lines the place where those lines meat is where you find the point of their ordered pair.

- Now we call the number lines **axes** and the based on their position the **horizontal and vertical axes** and more often the horizontal axes is known as the **x-axes** and vertical one the **y-axes** and the point where they cross each other and used as a reference is known as **The origin** and the ordered pair we can form are called the **coordinates**.

There two main use cases of the the cartesian coordinate system:

- Used as a way to map dimensions where each number line(axes) represents a dimension and the more perpendicular axes passing through the origin we add more dimension.

- Another use case is to show the relationship between dependent and independent variables, where the independent variables are represented in the x-axes while the dependent one is shown on the y-axes, which helps us map their patterns and see their relation as well.

Any point in the Cartesian plane is represented by an ordered pair of coordinates (x, y), where 'x' is the abscissa and 'y' is the ordinate. The order matters – (2, 3) is a different point than (3, 2).

To plot a point (x, y) on the Cartesian system, you start at the origin. The x-coordinate tells you how many units to move horizontally (right if positive, left if negative), and the y-coordinate tells you how many units to move vertically (up if positive, down if negative).

The two axes divide the Cartesian plane into four regions called **quadrants**. These quadrants are numbered using Roman numerals, starting from the upper right and going counter-clockwise.

Quadrants and Coordinate Signs

|              |                   |                   |
| ------------ | ----------------- | ----------------- |
| Quadrant     | x-coordinate sign | y-coordinate sign |
| Quadrant I   | +                 | +                 |
| Quadrant II  | -                 | +                 |
| Quadrant III | -                 | -                 |
| Quadrant IV  | +                 | -                 |

Identifying the quadrant of a point helps us understand the signs of its coordinates. For example, a point in Quadrant I will always have a positive x-coordinate and a positive y-coordinate.

The order of coordinates in an ordered pair (x, y) is crucial; the first value is always the x-coordinate (abscissa) and the second is always the y-coordinate (ordinate).

The Cartesian system relies on the specific order of the coordinates to accurately locate a point. Swapping the x and y values will result in a different location unless the point is on the line y = x.

---

## Basic Concepts of Relations

> In mathematics, a ==Relation== is simply a set of ordered pairs. That's it! Each ordered pair in the set shows a relationship between two elements. The first element of the ordered pair is typically an input, and the second element is the corresponding output.

- Relations(R) is the subset of the cartesian product of any two sets A and B.

$$ R ⊆ A \times B$$

- But in mathematics general ordered pairs with no discernable patterns are not that much useful so we add a predicate or a rule that shows a relation ship between the first number and the second number in the pair and thus a relation more abstractly can be defined as:

> **A relation is set containing ordered pairs that follow some specific rule.** Mathematically, $$ R = \{(a,b)| a,b ∈ A \times B| P(a)=b\} $$ Where R is a relation, A and B are any sets and P(a) is the predicate or the rule that the ordered pairs are related by.

Hence, a relation shows you the relationship between the input and the outputs held by a rule which forms a discernable pattern.

Now if we are dealing with only numbers, all the patterns possible between ordered pairs is represented by the Cartesian product of the set of all real numbers i.e. the cartesian coordinate system, hence a relation is a subset of the Cartesian product of the set of all real numbers

$$ R ⊆ \mathbb{R} \times \mathbb{R} $$

And thus, based on the rule we can activate all the possible ordered pairs(coordinates) that follow it, giving as a collection of points which we call a graph and based on the rule there can many types of graphs which we will mention as we go on.

There are different ways of representing a relation:

- Set of Ordered Pairs : Example: {(1, 2), (3, 4), (5, 6)}

- Table of Values : Like the ones we created for algebraic expressions.

- Mapping Diagram : Shows how elements from one set (inputs) are paired with elements from another set (outputs) using arrows.

- Graph : Plotting the ordered pairs on the Cartesian plane.

### the domain and range of a relation

As we said a relation is a subset of the cartesian product of any two sets, one of the sets represent the input of the rule while the other set indicates the output of the rule.

The first set is called the **Domain** of the relation and the second one is known as the **Range** of the relation. and in case of situation when both the sets are all real numbers represented by the cartesian coordinate , the set of all the inputs is the x-axis or the domain while the y-axis represents the range.

> The ==domain== of a relation is the ==set of all the first elements== (the x-values or inputs) of the ordered pairs in the relation.

> The ==range== of a relation is the ==set of all the second elements== (the y-values or outputs) of the ordered pairs in the relation.

Let's consider the relation: R = {(1, 5), (2, 10), (3, 15), (4, 20)}.

- To find the domain, we collect all the first elements from the ordered pairs: {1, 2, 3, 4}. So, the domain of R is {1, 2, 3, 4}.

- To find the range, we collect all the second elements from the ordered pairs: {5, 10, 15, 20}. So, the range of R is {5, 10, 15, 20}.

When a relation is given as an equation(rule), determining the domain and range can be a bit more involved. The domain is the set of all possible x-values for which the equation is defined, and the range is the set of all possible y-values that the equation can produce.

- For example, consider the relation given by the equation y = x + 2. Since any real number can be an input for x, the domain is all real numbers. As x can be any real number, y can also be any real number, so the range is all real numbers.

We can express domain and range using set notation and inequalities. For example, the set of all real numbers can be written in set notation as $\{x\mid x\in \mathbb{R}\}$ or in interval notation as $(-\infty ,\infty )$.

### Graphs of Relations

> The graph of a relation is simply the visual representation of the set of ordered pairs that make up the relation, plotted on the Cartesian coordinate system. Each ordered pair (x, y) corresponds to a point on the graph, where the x-coordinate is the horizontal position and the y-coordinate is the vertical position.

If a relation is given as a set of ordered pairs, like R = {(1, 2), (3, 4), (5, 6)}, we can represent it graphically by plotting each point on the coordinate plane. The graph would just be these individual points.

![[Pasted image 20260307102126.png]]

A graph of a relation can also be written terms of lines and curves as well based on what the rule is.

Now, let's consider how inequalities translate into solid or broken lines on a graph. When a relation is defined by an inequality, the graph will represent a region of the coordinate plane, not just a line or curve.

- Strict Inequalities (< or >)

- Use a broken or dashed line. This indicates that the points on the line are not included in the solution set of the inequality.

- Non-Strict Inequalities (≤ or ≥)

- Use a solid or **line**. This indicates that the points on the line are included in the solution set of the inequality.

After drawing the line, you need to shade the region of the plane that satisfies the inequality. You can pick a test point (that's not on the line) and substitute its coordinates into the inequality. If the inequality is true for that point, you shade the region containing the point. If it's false, you shade the other region.

---

## Introduction to Functions

> A **Function** in mathematics is a a **special type of relation** where the rule holding the relationship between the input and the output has an additional rule where the the **rule should always provide a unique output for every input**.

- A function is a *relation* which means a **function is a set of ordered pairs** and has in input and an output and has a rule holding the relationship between the input and the output.
- What makes a function special is that it requires the rule(pattern) between the input and the output to provide a unique output for every input.

A more formal way of defining it is:

> a **Function** $f$ is the set of ordered pairs with the property that whenever(x,y) and (x,z) belong to $f$ then z=y, hence a function is a relation in which **no two distinct outputs can have the same input**.

- So by this definition a function is always results in a unique first element or input.
- so in a set of ordered pairs if the first element any of the ordered pairs is similar with a distinct second element then that set is not a function, Example: $\{(1,2), (1,3),(3,2)\}$ this is not a function as the first and the second ordered pairs have the same first element and distinct second element.

### *Domain, Codomain and range of a function*

> As we defined it in relations, a **Domain** of a function is a set containing all the inputs, first elements or x values of that of the function.

- The domain for a function defines the set of the input values that we used or we can use for a function.

> **The codomain** of a function is the set of all the outputs that is possible for a function, it is the **Universal** set of all the possible outputs of a function.

- the codomain defines the space of outputs which we are working in, even if the function might not include all of them.

> while **the range** of a function is the set containing all the outputs of a function for the given inputs, the range is the actual outputs that we got for our inputs in all of the possible output space or codomain.

- the range of a function gives us the actual outputs we got for our inputs and it tells us the actual output space a function can contain and this is based on the operations used on the function for example, if y is defined from a domain of $\mathbb{R}$ to a codomain of $\mathbb{R}$ for $y=x^2$, this function has access to all the real numbers as a result of the codomain but because of the operations applied on it it can only have an output space ranging  (0, $\infty$) , this is the *range* of the function.
- hence the range is always a subset of the codomain.

If x is an element in the domain of the function $f$ then the element in the range that is associated to the input x is denoted by $f(x)$, This is called the **image** of x under the function $f$, hence the notation $f(x)$ signifies that the output of the function is dependent upon the input x.

To define the possible domain and codomain a function can work in we can use the notation $f:A \rightarrow B$ where A is the set containing the domain of a function and B is the set containing the codomain of the function.

There are various ways of writing a function for example a function can be written in the form of a set like $f=\{(x,f(x)): x,f(x) ∈ \mathbb{R}, f(x)=2x+1  \}$ this is familiar  because we have been using it in relations the first part tells us that this is a set containing ordered pairs and the second part tells us the possible input(*domain*) and output(*codomain*) space and the third which is the most important part is the **predicate, rule or pattern** that the input and output follow and what defines a function is the property of the rule and that is if it provides a unique output for every input that we provide, the other two parts of the function become repetitive when writing it and our major focus is the pattern or relationship between the inputs and the outputs which is the rule, so a simpler way of writing a function becomes $f:\mathbb{R} \rightarrow \mathbb{R}, f(x)=2x+1$ or just $f(x)=2x+1$ This is commonly used when the domain and codomain are understood from context.

### *Combination of functions*

Just like how real numbers can be operated upon by the four common operations of addition, subtraction, multiplication and division, a function is also closed by these four operations and can be used to create a new function.

#### **Addition of functions**

> Given two functions $f$ and $g$, for all x common for the domain of both functions the sum of $f$ and $g$ defined as follows $$(f+g)(x)=f(x)+g(x)$$

as we can infer from the definition the sum is only possible when the two functions are working on the same input and should share the same input space.


#### **Difference of functions**

> Given two functions $f$ and $g$, for all x common for the domain of both functions the difference of $f$ and $g$ defined as follows $$(f-g)(x)=f(x)-g(x)$$


#### **product of functions**

> Given two functions $f$ and $g$, for all x common for the domain of both functions the product of $f$ and $g$ defined as follows $$(f.g)(x)=f(x) . g(x)$$


#### **Quotient of functions**

> Given two functions $f$ and $g$, for all x common for the domain of both functions the product of $f$ and $g$ defined as follows $$(\frac{f}{g})(x)=\frac{f(x)}{g(x)}, g(x) \neq 0$$

- on the Quotient of functions there is an additional restriction that is we can't have the function at the denominator     to be zero this is a well known fact from arithmetic.

#### **The Domain of  combination of functions**

To combine two functions or more functions, the functions should have of the following requirement:

- **The two functions must have an overlapping domains i.e they must have at least one common input.**

> So if two or more functions fulfill the above requirement then *the domain of their addition, subtraction and multiplication is the intersection of the domain of the functions themselves*. The domain of their division is the intersection of the domain of the functions except the values that result on the denominator function being zero.

more formally, given two functions $f$ and $g$ the domain of their addition, subtraction and multiplication is: $$D=D_f ∩ D_g$$
and for the division of the two functions: 
$$D=\{x \in D_f ∩ D_g|g(x) \neq 0 \}$$
>[!note] **Vertical line test**
>Provided with a graph of a relation to check weather or not the relation is a function, we can use the *vertical line test*, draw a line of top of the graph of the relation if there are at least two points of the graph that touches the line then it is not a function otherwise it is. this works because by our definition a function cannot has two distinct outputs for any single input hence for a line passing through one x point(input) there must be a unique one point on the y axis more suggests that there is more than one output for a single input.

### **Types of Functions**

Different rules of relations that are also a function have different way of relating the input and the outputs, some might use the entire domain while others use the entire codomain. Based on this functions can be classified into two main types:

- **One-to-one function(injection)**
- **Onto function(surjection)**
- **one-to-one correspondence(bijection)**

#### *One-to-one Function(Injection)*

> This are functions where **every domain of a function is paired to at most one unique codomain**.

- This types of functions require the entire input space to have a unique output that is not repeated, is creates a truly unique relationship between the inputs and the outputs as any two distinct input do not share a similar output as well.

> More formally, A function $f:A \rightarrow B$ is called a *one-to-one* if and only if for all $x_1, x_2 \in A$,  $f(x_1)=f(x_2)$ then $x_1=x_2$ or if $f(x_1) \neq f(x_2)$ then $x_1 \neq x_2$.


#### *Onto function(surjection)*

> This are functions where **very codomain of the function is paired to at least one domain**.

- This is a shift in perspective from injective functions in the sense that now we are looking at the codomains than the domains, here the every codomain must be paired to at least one domain meaning that **all the possible outputs is attained by the function hence the set of the actual outputs which is the range is exactly equal to the set of all the possible outputs which is the codomain**.


#### *one-to-one correspondence(bijection)*

> If a function is both a one-to-one and an onto then this function is a **one-to-one correspondence** function.

- this functions now look at both of the cases simultaneously, **meaning that every domain is paired to at most one codomain and every codomain is paired to at least one domain.**

Such properties of functions show themselves even more explicitly when graphing them, for example:

- if a function is an injection it must have always a unique second element hence we can use a **horizontal line** to see if there are any two output points that are pairing to an input in which case it is not a one to one.
- if a function is an onto then we might see if it has encompassed all of the y-axis(output space) assuming the codomain is from the set real numbers if so it is a onto.
- if the graph of a function satisfies the above two simultaneously then it is a bijective function.  

### **Graphs of functions**

> *Graphs of Functions* are ways of representing the patterns the rules create on a Cartesian coordinate system where the x axis is the input space or the domain and the y-axis is the output space or the codomain.

- the graph of functions are special in that they provide us a well defined equation which shows the relation between the input and output.
- the graphs of functions are based on what the rule or now what we call the function is, different functions have different graphs showing that they have different relations between the inputs and the outputs.

To graph the function we need the domain which is the set all the possible input values call it A and the range, the set of the actual output values, $f(x)$ hence we can plot all the ordered pairs from the set $\{(x,f(x)): x \in A\}$.

We are gonna look into different functions and their graphs but we will start with simplest of functions and we are gonna progress into even more complex once each building knowledge from the pervious.


#### *Linear Functions*

> Is a function written in the form $f(x)=ax+b$ where a and b are an element of all real numbers where $a \neq 0$.

- in cases when $a =0$, then we have $f(x)=b$ this is called a **constant or horizontal function**.

A linear function is called this way because the points satisfying this in the Cartesian coordinate system when plotted provide us a **line**, thus the relationship between the input and the output is called a *linear relationship*.

Sketching the linear function with the rule $y=2x-4$ for example gives us:
![[Pasted image 20260419161041.png]]


a linear function's rule consists of two major parameters we need to understand, that all other functions in one way or another contain: **The slope and the intercept**.

The form of the rule: $$f(x)=ax+b$$
The *a* value is called the **slope** of this function, the slope of a function gives us the most critical information of the function that is ==**the rate at which the output changes with respect to the input**== 

mathematically can be represented as: $$a=\frac{\Delta y}{\Delta x}$$

- the magnitude slope is often translated in the graph as its steepness, and that makes sense because the higher the rate of change of the output per unit change in the input is the steeper the line provided by the function becomes and the opposite follows for a lower slope value.
- the sign of the slope on the other hand provide us with another critical insight into graphs of functions and relations between the x and the y. 
	- If the slope is **positive**, it means that $y$ *moves up* in the Cartesian plane and $x$ moves to the *right*. the function is said to be to be **increasing**.
	- ![[Pasted image 20260419161656.png|251]]
	- When the rate of change is **negative**, $y$ *moves down* in the Cartesian plane and  moves to the *right*.
	- ![[Pasted image 20260419162111.png|259]]

The **b** parameter in a linear function on the other hand represents an **intercept**. the intercept of a function as it name indicates is the point where the graph and the axis of the plane intersect or intercept, the point where the graph and the x-axis meet is the **x-intercept** and the point where the graph and the y-axis meet is the **y-intercept**. and the intercept provide us where each of the values become zero, the y-intercept occurs when x=0 and the x-intercept occurs when y=0. the b value in a linear function hence provide us the **y-intercept** of the linear function because when ever we have an x=0 as input we get b as an output hence (0,b) is the y-intercept.


#### *Quadratic functions*

> A function written in the form $f(x)=ax^2+bx+c$ where a,b and c are called **coefficients** and are  $\in \mathbb R$ where $a \neq 0$.

- here the *a* is the leading coefficient, *b* is the linear coefficient and *c* is the constant coefficient
- $ax^2$ is the leading term or also called the **quadratic term**  $bx$ is called the linear term and c is called the constant term.

A quadratic function has a unique **U-shape** that results from the $x^2$ term as having two inputs that can give us the same output. the name given for the u-shaped graph of a quadratic function is a **parabola**, and the line dividing the right and left leg of the parabola symmetrically is called the **line or axis of symmetry**.

- the point where the line of symmetry and the parabola meet is called the **vertex**.
- and the line perpendicular to the axis of symmetry crossing at the vertex is called **the orthogonal line**.


To understand what each of the coefficients of a quadratic function do, we will need to begin with the simplest form of a quadratic function that is $f(x)=ax^2$

![[Pasted image 20260419184020.png|293]]

The coefficient *a* of the leading term tells us two of the most important properties of the quadratic function the direction in which it opens in and the how narrow or wide is the graph, unlike a linear function, a quadratic function doesn't have a constant term instead the rate at which the output changes with respect to the input is given by $ax+b$, hence the slope of a quadratic function depends upon both the value of *a* and *b*.

- the direction of opening meaning weather it is upward or downward opening parabola depends solely on the sign of *a*, if positive it opens upwards, if negative it opens downwards.

- In the same way the magnitude of *a* tells us how wide the parabola opens, it becomes wider as *a* goes less than 1 and it goes narrower as it goes above 1.

The next term we should explore is the *constant term* in the form $f(x)=ax^2+c$, we can directly see the following from this form:

- The first being that *c* operates on the output value, it adds *c* amounts on $ax^2$, this creates a physical shift of the graph on the plane.

- The second being that the value of *c* is the y-intercept because when x=o the only value we have left is c, this means that the function is moved or shifted by c amounts up or down, up if positive and down if negative.

- the third being that this ways seems to change the *orthogonal line*, as it moves the graph up and down the line perpendicular to the axis of symmetry, changes.

If we wanna have a horizontal shift on the other hand, we will need to cause a change on the input itself, that gives us this from $f(x)=a(x-k)^2$, this first applies the k value on the input then squares it changing the value of each input by k amount this translates to the entire graph being shifted by k amount to the right or to the left, to the right if negative and to the left if positive.

- the horizontal shift results in a change on the line of symmetry.

Applying both shifts gives us this form $f(x)=a(x-k)^2 +c$ this form is called **the standard form of a quadratic function**, and this contains the value a,b and c but makes all the shifts applied on the graph explicit. 






