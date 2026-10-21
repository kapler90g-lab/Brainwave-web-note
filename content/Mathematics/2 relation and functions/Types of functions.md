## functions
A function is a relation between a set of inputs and outputs where each input corresponds to exactly one output. The **vertical line test** helps us determine if a graph represents a function.

### Explanation
The vertical line test states that if any vertical line drawn on the graph intersects it at more than one point, the relation is **not** a function. This is because having a vertical line intersect at multiple points indicates that a single input value (an $x$-coordinate) is associated with more than one output value (a $y$-coordinate), which violates the definition of a function.
- for a relation given ${(x,y),(r,y)}$ is a function if it follows those conditions:
    - $x=r \quad and \quad y=z$
    -  $x≠r \quad and \quad y≠z$
    - $x≠r \quad and \quad y=z$
    - 
#### Example with Coordinate Values
Consider the following points on a graph:

- $(2, 3)$
- $(2, -1)$

If we draw a vertical line at $x = 2$, this line will touch the graph at both points $(2, 3)$ and $(2, -1)$. This means that the input $x = 2$ maps to two different outputs: $y = 3$ and $y = -1$.

### Why This Violates the Definition of a Function
For a graph to represent a function, each input $x$ must map to **exactly one** output $y$. In this example:

- The input $x = 2$ is associated with multiple outputs ($y = 3$ and $y = -1$), violating the condition for a function.

### Visual Representation
When plotting $(2, 3)$ and $(2, -1)$ on the coordinate plane, a vertical line drawn at $x = 2$ intersects both points. This confirms that the relation fails the vertical line test and, therefore, is **not a function**.

### Summary
- A vertical line touching the graph at more than one point implies a single input has multiple outputs.
- Such a scenario fails the vertical line test, proving the relation is **not a function**.

## **power function**

a function of a form ;$f(x)=ax^n$ where a is a non-zero real number and n is the set of real number and x is an independent variable this function is called **power function**

- *example* $f(x)=x^2$ 


### Concept of Power Functions
- **Even Exponents** (e.g., $x^2, x^4, x^6$): When the exponent is even, the function maps negative and positive input values to positive output values. This is because:
  $$
  (-x)^{2n} = x^{2n}
  $$
  For example, $(-2)^2 = 4$ and $2^2 = 4$, so negative and positive inputs result in positive outputs.

- **Odd Exponents** (e.g., $x^3, x^5, x^7$): When the exponent is odd, the function preserves the sign of the input. This means:
  $$
  (-x)^{2n+1} = -(x^{2n+1})
  $$
  For example, $(-2)^3 = -8$ and $2^3 = 8$, so the function outputs negative values for negative inputs and positive values for positive inputs.

### Relationship Between Negative Numbers and Odd Exponents
- **Sign Preservation**: The key relationship between negative numbers and odd exponents is that **odd exponents preserve the sign of the base**. This is due to the mathematical property that multiplying an odd number of negative values results in a negative product. For example:
  - $(-x) \times (-x) \times (-x) = -x^3$
  - The negative sign remains because there is an odd number of multiplications.

- **Sign Reversal with Even Exponents**: In contrast, even exponents result in positive outputs because multiplying an even number of negative values cancels out the negative signs:
  - $(-x) \times (-x) = x^2$
  - The negative signs cancel each other out, resulting in a positive product.

### Visual Interpretation
- **Even Power Functions** (e.g., $y = x^2$, $y = x^4$): These functions are symmetric about the y-axis (even functions). The graph only occupies the positive side of the y-axis for all real input values because the output is always non-negative.

- **Odd Power Functions** (e.g., $y = x^3$, $y = x^5$): These functions have origin symmetry (odd functions). The graph extends into both the positive and negative sides of the y-axis, mapping negative inputs to negative outputs and positive inputs to positive outputs.

### Intuition Behind the "Unlocking" of Negative Outputs
- **Odd Exponents "Unlock" Negative Outputs**: When the exponent is odd, negative bases remain negative because there is an unpaired multiplication that preserves the negative sign. This "unlocks" negative output values, mapping the function to both positive and negative parts of the y-axis.
- **Even Exponents "Lock" to Positive Outputs**: With even exponents, negative inputs result in positive outputs due to the even number of multiplications canceling out any negative signs, restricting the function to only the positive part of the y-axis.

### Summary
- **Even Exponents**: Always yield positive outputs for any real input, resulting in a graph that stays in the positive y-axis.
- **Odd Exponents**: Preserve the sign of the base, allowing for negative outputs for negative inputs and positive outputs for positive inputs, resulting in a graph that spans both the positive and negative y-axis.

This relationship is rooted in how multiplication works with negative numbers: even numbers of negative multiplications cancel out to positive, while odd numbers retain the negative sign.
>[!note] opperation classificaton
>- **Input-Altering Operations**: Addition, subtraction, multiplication, division.
>- **Output-Altering Operations**: Exponentiation, absolute value, negative sign $-x$.
>- **Both Input and Output-Altering Operations**: Radicals, logarithms, fractional exponents (e.g., $x^{1/n})$).


#### case 1
the domain and range of a the power function $f(x)$ given above is:
- the domain is $\mathbf R$ 
- but the range is not only a $\mathbf R$ b/c the operations we do on the impute changes the output in this case even exponentiation which cases all the negative numbers to become positive meaning the range is ${{x|x>=0}}$  
- for a a function of the form $f(x)=x^n$ where $n$ is even has the following properties:
     -  the domain is $\mathbf R$ 
     - the range is $[0,\infty)$ or $\mathbf R^+$  
     - ![[Pasted image 20241111110745.png]]
#### case 2
for a a function of the form $f(x)=x^n$ where $n$ is odd has the following properties:
     -  the domain is $\mathbf R$ 
     - the range is $\mathbf R$ 
     - ![[Pasted image 20241111112207.png]]

#### case 3
 for a a function of the form $f(x)=x^1/n$ where $n$ is even has the following properties:
     -  the domain is $\mathbf R^+$ 
     - the range is $[0,\infty)$ or $\mathbf R^+$  
     - ![[Pasted image 20241111113749.png]]
#### case 4
for a a function of the form $f(x)=x^1/n$ where $n$ is odd has the following properties:
     -  the domain is $\mathbf R$ 
     - the range is  $\mathbf R$  
     - ![[Pasted image 20241111115205.png]]
#### case 5
for a a function of the form $f(x)=x^{m/n}$ where $m$ is odd and  $n$ is even has the following properties:
     -  the domain is $\mathbf R^+$ 
     - the range is $[0,\infty)$ or $\mathbf R^+$  
     - ![[Pasted image 20241111120158.png]]
#### case 6
for a a function of the form $f(x)=x^{m/n}$ where $m$ is even and  $n$ is odd has the following properties:
     -  the domain is $\mathbf R$ 
     - the range is $[0,\infty)$ or $\mathbf R^+$
     - ![[Pasted image 20241111120900.png]]
#### case 7
for a a function of the form $f(x)=x^{-1/n}$ where $n$ is even has the following properties:
     -  the domain is $(0,\infty)$ 
     - the range is $(0,\infty)$ 
     - ![[Pasted image 20241111121926.png]]
#### case 8
for a a function of the form $f(x)=x^{-1/n}$ where $n$ is odd has the following properties:
     -  the domain is $\mathbf R/{0}$ 
     - the range is $\mathbf R/{0}$  
     - ![[Pasted image 20241111122515.png]]
#### case 9
for a a function of the form $f(x)=x^{-m/n}$ where $m$ is odd and  $n$ is even has the following properties:
     -  the domain is $(0,\infty)$ 
     - the range is $(0,\infty)$
     - ![[Pasted image 20241111123323.png]]
#### case 10
for a a function of the form $f(x)=x^{-m/n}$ where $m$ is even and  $n$ is odd has the following properties:
     -  the domain is $\mathbf R/{0}$ 
     - the range is $(0,\infty)$
     - ![[Pasted image 20241111123656.png]]
## **Modulus functions** 

### absolute values

- a distance on a number line is defined by using the operation **absolute value** 
- ### Concept of Absolute Value
The **absolute value** of a number is a measure of its magnitude without considering its sign. It represents the distance of a number from zero on the number line, regardless of direction. For any real number $x$:

- The absolute value is denoted by $|x|$.
- Mathematically, it is defined as:
  $$
  |x| = 
  \begin{cases} 
  x, & \text{if } x \geq 0 \\
  -x, & \text{if } x < 0
  \end{cases}
  $$
This means $|3| = 3$ and $|-3| = 3$, as both numbers are three units away from zero.

#### Explanation and Properties
- **Distance Interpretation**: The absolute value function interprets a number as its distance from zero on a number line. For example, both $5$ and $-5$ are 5 units from zero, so $|5| = 5$ and $|-5| = 5$.
- **Non-Negativity**: Absolute values are always non-negative, as they measure distance, which cannot be negative.
- **Key Property**: For any real number $( x )$, $( |x| \geq 0$ )

### Historical Development
The concept of absolute value has roots in early mathematics related to distance and magnitude. Here’s how it developed:

1. **Early Ideas in Geometry**: The notion of distance, which is inherently non-negative, is one of the oldest in mathematics. Ancient mathematicians understood distance as an inherently positive measure, even before formalizing negative numbers.

2. **Introduction of Negative Numbers**: By the medieval period and through the development of algebra, negative numbers began to be understood and used in equations. However, early mathematicians struggled with interpreting negative results in practical contexts, leading to the need for a concept that could express "magnitude" without sign.

3. **Formalization of Absolute Value**:
   - The symbol $|x|$ for absolute value was first introduced in the 19th century by **Karl Weierstrass**, a German mathematician, who contributed significantly to rigorous mathematical analysis.
   - The concept was formally defined to resolve ambiguities when negative numbers arose in equations and expressions where only magnitude was needed, such as in the calculation of distance, norms, and inequalities.


### Summary
The absolute value operation emerged from a need to express distances and magnitudes in a consistent, non-negative manner, especially as negative numbers became more prevalent in mathematical discourse. Over time, it became a fundamental concept with widespread applications in various fields of science and mathematics.

>[!note] there is NO operation that undoes absolute value. why?

### absolute value function
- a function $f:R \rightarrow R$ defined by $f(x)=|x|$ is called an **absolute value function**

## **Signum function**
The **signum function**, often denoted as $$ \operatorname{sgn}(x) $$, is a mathematical function that indicates the sign of a real number. It is defined as follows:

$$
\operatorname{sgn}(x) = 
\begin{cases} 
1 & \text{if } x > 0 \\ 
0 & \text{if } x = 0 \\ 
-1 & \text{if } x < 0 
\end{cases}
$$

This piecewise function categorizes any real number into one of three outputs: **+1** for positive numbers, **0** for zero, and **-1** for negative numbers. The signum function is particularly useful in various mathematical contexts, including calculus, signal processing, and analysis, as it succinctly conveys the sign of a number without providing its magnitude.

Additionally, the signum function can be generalized to complex numbers, where it is defined as:

$$
\operatorname{sgn}(z) = \frac{z}{|z|} \quad \text{for } z \neq 0
$$

This definition allows the signum function to maintain its utility in complex analysis by indicating the direction of a complex number on the unit circle in the complex plane.

## **floor function**

The floor function, denoted as $\lfloor x \rfloor$, is a mathematical function that maps a real number $x$ to the largest integer less than or equal to $x$. In other words, it "rounds down" $x$ to the nearest integer.


For any real number $x$:

$$
\lfloor x \rfloor = n \quad \text{where } n \in \mathbb{Z} \text{ and } n \leq x < n + 1
$$

Examples

$\lfloor 3.7 \rfloor = 3$
$\lfloor -2.3 \rfloor = -3$
$\lfloor 5.0 \rfloor = 5$

**Properties**

- The floor function is a step function, meaning it is constant between integers and jumps at each integer value.
- It is defined for all real numbers, including positive numbers, negative numbers, and zero.

In summary, the floor function provides the greatest integer that is less than or equal to a given real number.
