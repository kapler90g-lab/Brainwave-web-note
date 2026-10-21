---
tags:
  - grade11
  - unit2
  - rational_expressions_and_functions
aliases:
theme: relation and functions
Unit: rational expressions and functions
status: in-progress
---
#grade11 #unit2 #rational_expressions_and_functions
# Rational Expression and Functions (Grade 11, Unit 2)

## When
### Historical Background of Rational Expressions

- Its historical background can be traced to the Ancient Babylonians,  
  *Who developed a **positional number system**, which helped them in solving algebraic equations.*
- They were more interested in approximation values rather than the exact value.
- The idea of a **determinant** was developed by a Japanese mathematician known as **Kowa Seki** in the 17th century for the purpose of solving systems of simultaneous linear equations using matrices.

## What
### What is a Rational Expression?

### Rational Number

A **rational number** is any number that can be expressed in the form of a fraction $\frac{p}{q}$, where:
- $p$ and $q$ are integers.
- $q \neq 0$.

Examples:
- $\frac{3}{4}, -5, \frac{-7}{2}, \text{and } 0.3333... (\text{repeating decimals like } 0.\overline{3})$.

### Converting $1.12121212...$ to Fraction Form

The number $1.121212...$ is a repeating decimal ($1.12\overline{12}$). To convert it into a fraction, follow these steps:

---

#### Step 1: Let $x = 1.121212...$
We represent the repeating decimal as:
$$x = 1.121212...$$

#### Step 2: Multiply $x$ by a power of 10 to shift the repeating part
The repeating block $12$ has 2 digits, so multiply $x$ by $100$:
$$100x = 112.121212...$$

#### Step 3: Subtract the original equation from this new equation
This eliminates the repeating decimal part:
$$100x - x = 112.121212... - 1.121212...$$
$$99x = 111$$

#### Step 4: Solve for $x$
$$x = \frac{111}{99}$$

#### Step 5: Simplify the fraction
The greatest common divisor (GCD) of $111$ and $99$ is $3$. Simplify the fraction:
$$x = \frac{111 \div 3}{99 \div 3} = \frac{37}{33}$$

So, $1.121212...$ as a fraction is:
$$\boxed{\frac{37}{33}}$$

---

### Verifying the Conversion
Convert $\frac{37}{33}$ back to a decimal form:
$$\frac{37}{33} = 1.121212...$$

- **Rational Expressions** are defined as *quotients of polynomials.*

  - **Quotients of Polynomial reasoning**: It is the expression that is formed by dividing one polynomial by another.
  - **Polynomial equations**: An equation that can be written in the form:
    $$
    a_nx^n + a_{n-1}x^{n-1} + a_{n-2}x^{n-2} + \ldots + a_1x + a_0 = 0
    $$
  - Let's say there are polynomials $( P(x) ) and ( Q(x) ) with ( Q(x) \neq 0 )$, an expression that can be written as $(\frac{P(x)}{Q(x)})$ is known as a **Rational Expression**.

    **Example:**
    $$
    \frac{2x + 3}{2x^2 + 4x + 1}
    $$
    - **Note**: To identify whether an expression is a rational expression or not, see if the things you are dividing are polynomials or not.

### Properties of Rational Expressions

- A rational expression is **undefined** if the denominator is zero.
- They can be simplified by canceling the common factors.
- We can multiply them by multiplying the numerator and the denominators.
- We can add or subtract rational expressions by simply adding or subtracting the numerators.
- They have **asymptotes**, which are lines that a curve approaches as it heads towards infinity.

### Domains of Rational Expressions

- The domain of a rational expression is all real numbers except those that make the denominator zero.

  - **Notation**:
    $$
    \frac{P(x)}{Q(x)} \, : \, x \in \mathbb{R}, Q(x) \neq 0
    $$
  - **For Example**:
    $$
    \frac{x^2 + 7}{x^2 + 1}
    $$
    The domain is all real numbers except \(-1\) and \(1\), which make the denominator zero.



### How (The way to simplify and solve Rational Ex.)
1. If the GCF of $\frac{a}{b}$ is 1, where $b \neq 0$, then it is in the lowest form (simplified form).

2. Given $a, b, c$ with $b \neq 0$ and $c \neq 0$, we have:

   $$\frac{ac}{bc} = \frac{a}{b}$$

---

### Example:
**Simplify** $\frac{x+1}{x-1}$

$$\rightarrow \frac{(x+1)}{(x-1)} \times \frac{1}{(x+1)(x-1)}$$

Observe that $x-1$ in the equation $\frac{1}{x-1}$ is not defined. But in the example $\frac{x+1}{x-1}$, it is defined. Why?

To simplify an expression, follow the steps:

---

### Steps to Simplify a Rational Expression
1. Find the domain of the expression.
2. (If possible) Factor both $P(x)$ and $Q(x)$.
3. Cancel out the common factors.

---

### Example:

**Simplify** $\frac{3x}{x^2+2x+4} \leq \frac{3x}{(x+2)(x+2)}$

**Find the Domain:**

$$x(x+2)(x+2) \leq 0$$

So the domain is:

$$D: \{x \in \mathbb{R} | -2 \leq x \leq \frac{-2}{3}\}$$

---

### Operations with Rational Expressions (RE)

Let $\frac{a}{b}$ and $\frac{c}{d}$ be two rational numbers with $b, d \neq 0$.

The basic operations (ASMP) on RE are given as:

i. $\frac{a}{b} + \frac{c}{d} = \frac{ad + bc}{bd}$

ii. $\frac{a}{b} - \frac{c}{d} = \frac{ad - bc}{bd}$

iii. $\frac{a}{b} \times \frac{c}{d} = \frac{ac}{bd}$

iv. $\frac{a}{b} \div \frac{c}{d} = \frac{a}{b} \times \frac{d}{c} = \frac{ad}{bc}$

(Case when $c \neq 0$)

---

### An Operation on Rational Expressions

- The operation $P(x) - Q(x)$ on RE is the same as the operation $S(x)$ on RE.

- Consider the rational expression $\frac{P(x)}{Q(x)}$ and $\frac{R(x)}{S(x)}$ with $P(x) \neq 0$ and $Q(x) \neq 0$.

Let:

a) $$\frac{P(x)}{Q(x)} + \frac{S(x)}{T(x)} = \frac{P(x)S(x) + Q(x)T(x)}{Q(x)S(x)}$$

b) $$\frac{P(x)}{Q(x)} - \frac{R(x)}{S(x)} = \frac{P(x)S(x) - Q(x)R(x)}{Q(x)S(x)}$$

---

### Example:

$$\frac{(x+1)}{(x+2)} \times \frac{(3x)}{(x+5)}$$

$$\rightarrow \frac{(x+1)(3x) + (x+2)(x+5)}{(x+2)(x+5)}$$

$$\rightarrow \frac{(x+3)(x+5) + (x+2)(x+5)}{x^3+7x^2+10x}$$

## M and D of RE

###### In the same way as previous:

- Consider two **RE**: $\frac{P(x)}{Q(x)}$ and $\frac{S(x)}{Q(x)}$ with $Q(x)$ and $S(x) \neq 0$. Then:

  1. $$\frac{P(x)}{Q(x)} ÷ \frac{P(x)}{Q(x)} = \frac{Q(x)S(x)}{p(x)S(x)}$$

  2. $$\frac{P(x)}{Q(x)} \times \frac{R(x)}{S(x)} = \frac{P(x)R(x)}{Q(x)S(x)}$$

### Example:

$$ \frac{x+1}{x-1} \times \frac{x+2}{x+3} = \frac{x^2 + 3x + 2}{x^2 + 2x - 3}$$

### Decomposition of RE into Partial Fractions

- The main objective of this is to write the **RE** as the sum of partial fractions.
- Two polynomials **P(x)** and **Q(x)** are equal if they have the same degree and coefficients in each term.

#### Example:

Given $P(x) = ax^3 + bx^2 + cx + d$ and $Q(x) = ax^3 + bx^2 + cx + e$:

1. **a** must equal to 2 (so that the term in $P(x)$ is $3x^4$)
2. **b** must equal to 2 (so that the term in $P(x)$ is $3x^3$)
3. **c** must equal to 4 (so that the term in $Q(x)$ is $4x$)

- A **RE** $\frac{P(x)}{Q(x)}$ is called **proper RE** if **P(x)** has less degree than **Q(x)**.
- Otherwise, it is called **improper RE**.

### Note:

Given an improper rational expression $\frac{P(x)}{Q(x)}$, long division can be written as:

$$ \frac{P(x)}{Q(x)} = f(x) + \frac{r(x)}{Q(x)}$$

Here, **f(x)** has less degree than **Q(x)**.

#### Example:

$$ \frac{5x^3 + 7x^2 + 15x + 9}{x^2 + 1}$$ can be written as:

$$ 5x^3 + 7x^2 + 15x + 9 = (5x + 1) \cdot (5x + 1) + 2$$

So:

$$ \frac{5x^3 + 7x^2 + 15x + 9}{x^2 + 1} = (5x + 1) + \frac{2}{x^2 + 1}$$

Where:
- $r(x) = 2$
- $Q(x) = x^2 + 1$
- $P(x) = 5x^3 + 7x^2 + 15x + 9$ 
- $Q(x) = 5x + 1$


## 2.2 Rational Equations and Inequalities

### **What** is a Rational Equation?

- A rational equation is an equation (a connection of information known initially to solve relations and find the unknowns) that involves rational expressions. It is called a **rational equation**. Thus, it is an equation that can be reduced into the form:

$$ \frac{P(x)}{Q(x)} = 0 \quad \text{where} \quad Q(x) \neq 0 $$

#### Example:

$$ \frac{2x}{x^2 - 1} + \frac{x + 1}{x + 1} = 0 $$

- Multiply both sides by $(x^2 - 1)(x + 1)$:

$$ - \frac{2x(x^2 - 1)}{(x + 1)} + 2x^2 - x + 1 = 0 $$

- Simplify:

$$ -2x(x^2 - 1) + 2x^2 - x + 1 = 0 $$

- Factor:

$$ x^2 - 1 = (x + 1)(x - 1) $$

### **How** to Solve (Steps in solving REE):

**Step 1:** Reduce the given equation into the form of $P(x) = 0$.

**Step 2:** Solve the equation $Q(x) = 0$.

**Step 3:** Solve the equation $P(x) = 0$.
### Example

Solve:

$$ x - \frac{1}{2} - \frac{3}{4} = 0 $$

1. Multiply by 4 to clear the fractions:
   $$ 4x - 2 - 3 = 0 $$

2. Simplify:
   $$ 4x - 5 = 0 $$

3. Solve for $x$:
   $$ x = \frac{5}{4} $$

   This is the solution set for the given equation.

### Another Example

Solve:

$$ \frac{2}{x-9} - \frac{x}{x+3} = 0 $$

1. Multiply by $(x-9)(x+3)$ to clear the fractions:
   $$ (-2x + 6) + (x^2 - 9x) = 0 $$

2. Simplify:
   $$ x^2 - 12x + 6 = 0 $$

   The solutions are given by:

$$ x^2 - 12x + 6 = 0 $$


---

### Steps in Solving Rational Inequalities Explained with Examples

#### **Step 1: Determine the Domain of the Rational Inequality**
- The **domain** of a rational inequality excludes any values of $x$ that make the denominator $q(x)$ equal to zero, as division by zero is undefined.

**Example:**
Solve $\frac{x+1}{x-2} > 0$.
- The denominator $x-2 = 0$ when $x = 2$.
- Thus, the domain is all real numbers except $x = 2$.

---

#### **Step 2: Rewrite the Inequality in Standard Form**
- Express the inequality as $\frac{p(x)}{q(x)} > 0$, $\frac{p(x)}{q(x)} \geq 0$, $\frac{p(x)}{q(x)} < 0$, or $\frac{p(x)}{q(x)} \leq 0$.
- This step ensures clarity in identifying critical points (zeros of numerator and denominator).

**Example:**
For $\frac{x+1}{x-2} > 0$, the inequality is already in standard form.

---

#### **Step 3: Find the Zeros of $p(x)$ and $q(x)$**
- Solve $p(x) = 0$ to find the zeros of the numerator.
- Solve $q(x) = 0$ to find the zeros of the denominator. These are the **critical points** that divide the number line into intervals.

**Example:**
For $\frac{x+1}{x-2} > 0$:
- $x+1 = 0 \implies x = -1$ (zero of the numerator).
- $x-2 = 0 \implies x = 2$ (zero of the denominator).

Critical points: $x = -1$ and $x = 2$.

---

#### **Step 4: Divide the Number Line into Intervals and Use the Sign Chart Method**
- Use the critical points to divide the number line into intervals.
- Test a sample point from each interval in $\frac{p(x)}{q(x)}$ to determine the sign of the expression in each interval.

##### **Sign Chart Method**:
1. Identify intervals based on the critical points.
2. Test the sign of $p(x)$ (numerator) and $q(x)$ (denominator) in each interval.
3. Combine the signs to determine the sign of the fraction in each interval.

**Example:**
For $\frac{x+1}{x-2} > 0$, critical points are $x = -1$ and $x = 2$. Divide the number line into intervals:
- Interval 1: $(- \infty, -1)$
- Interval 2: $(-1, 2)$
- Interval 3: $(2, \infty)$

Test points:
1. In $(- \infty, -1)$, choose $x = -2$: 
   $$\frac{-2+1}{-2-2} = \frac{-1}{-4} = +.$$
2. In $(-1, 2)$, choose $x = 0$:
   $$\frac{0+1}{0-2} = \frac{1}{-2} = -.$$
3. In $(2, \infty)$, choose $x = 3$:
   $$\frac{3+1}{3-2} = \frac{4}{1} = +.$$

Sign Chart:
- Interval $(- \infty, -1)$: Positive ($+$).
- Interval $(-1, 2)$: Negative ($-$).
- Interval $(2, \infty)$: Positive ($+$).

---

#### **Step 5: Find the Intervals that Satisfy the Inequality**
- Use the inequality's direction ($>$, $<$, $\geq$, or $\leq$) to determine which intervals to include:
  - For $>$ or $<$: Include intervals with the specified sign ($+$ or $-$) but exclude boundary points (critical points).
  - For $\geq$ or $\leq$: Include intervals with the specified sign and include boundary points where $p(x) = 0$ but not where $q(x) = 0$.

**Example:**
For $\frac{x+1}{x-2} > 0$:
- Positive intervals: $(- \infty, -1)$ and $(2, \infty)$.
- The solution is $x \in (-\infty, -1) \cup (2, \infty)$.

If the inequality were $\frac{x+1}{x-2} \geq 0$, include $x = -1$ but exclude $x = 2$ because the denominator cannot be zero:
- Solution: $x \in [-1, -1] \cup (2, \infty)$.

---

### **Why Include or Exclude Signs Depending on the Inequality?**
1. **Strict inequalities ($>$, $<$)**:
   - Critical points where $p(x) = 0$ or $q(x) = 0$ are **excluded** because the expression cannot be equal to 0.
2. **Inclusive inequalities ($\geq$, $\leq$)**:
   - Include critical points where $p(x) = 0$ because these satisfy the equality.
   - Exclude points where $q(x) = 0$ because they are undefined.

---

### Summary
1. **Domain**: Identify points where $q(x) = 0$ (excluded from the solution).
2. **Rewrite**: Express the inequality in standard form.
3. **Zeros**: Solve $p(x) = 0$ and $q(x) = 0$ to find critical points.
4. **Sign Chart**: Test signs in each interval and analyze.
5. **Solution**: Select intervals based on the inequality sign, including or excluding boundaries appropriately.

### asymptotes of a rational function

![[Rational-Functions.pdf]]
