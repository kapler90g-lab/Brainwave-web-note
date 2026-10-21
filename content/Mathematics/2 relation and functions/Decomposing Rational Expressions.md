
### **Main Concept: Decomposing Rational Expressions into Partial Fractions**

**Intuitive Understanding**:  
Decomposing a rational expression into partial fractions is the process of breaking down a complicated fraction into a sum of simpler fractions. This makes complex algebraic operations (like integration or simplification) easier to handle.  

**Why does it work?**  
A rational expression represents a fraction of two polynomials. These polynomials can be factored into smaller, simpler terms (linear or quadratic). By decomposing the fraction, we express the rational expression as a sum of terms where each term corresponds to one of these factors. This transformation is based on the **fundamental theorem of algebra**, which ensures every polynomial can be factored into linear or quadratic terms over the real or complex numbers.

---

### **Why Different Cases Exist?**  
The form of decomposition depends on the factors of the denominator. Denominators can have:  
1. Simple linear factors (e.g., $x + 1$),  
2. Repeated linear factors (e.g., $(x + 1)^2$),  
3. Irreducible quadratic factors (e.g., $x^2 + 2x + 5$),  
4. Repeated irreducible quadratic factors (e.g., $(x^2 + 2x + 5)^2$),  
5. Improper fractions (when the numerator's degree is greater than or equal to the denominator's degree).  

These cases reflect the variety of ways a polynomial can factorize, and each case requires a slightly different approach to ensure the decomposition is complete and valid.

---

### **Overview of the Five Cases**  

#### **Case 1: Simple Linear Factors**
- **When to Use**: When the denominator has distinct linear factors (e.g., $x + 1, x - 2$).
- **Decomposition Form**: Each linear factor gets a constant in the numerator (e.g., $\frac{A}{x + 1} + \frac{B}{x - 2}$).

#### **Case 2: Repeated Linear Factors**
- **When to Use**: When a linear factor appears multiple times (e.g., $(x + 1)^3$).
- **Decomposition Form**: Include terms for every power of the factor up to the highest exponent (e.g., $\frac{A}{x + 1} + \frac{B}{(x + 1)^2} + \frac{C}{(x + 1)^3}$).

#### **Case 3: Irreducible Quadratic Factors**
- **When to Use**: When the denominator contains irreducible quadratic factors (e.g., $x^2 + 2x + 5$).
- **Decomposition Form**: Each quadratic factor gets a linear numerator (e.g., $\frac{Ax + B}{x^2 + 2x + 5}$).

#### **Case 4: Repeated Irreducible Quadratic Factors**
- **When to Use**: When an irreducible quadratic factor appears multiple times (e.g., $(x^2 + 2x + 5)^3$).
- **Decomposition Form**: Include terms for every power of the quadratic factor with linear numerators (e.g., $\frac{A_1x + B_1}{x^2 + 2x + 5} + \frac{A_2x + B_2}{(x^2 + 2x + 5)^2} + \cdots$).

#### **Case 5: Improper Fractions**
- **When to Use**: When the numerator's degree is greater than or equal to the denominator's degree.
- **Decomposition Process**: Perform polynomial long division first to separate the expression into a polynomial and a proper fraction. Then apply one of the above cases to decompose the proper fraction.

---

### **Why Do These Cases Exist?**  
1. **Linear Factors**: Simple fractions like $1/(x+1)$ are the building blocks of rational expressions.  
2. **Repeated Linear Factors**: A factor raised to a power requires multiple terms to account for all possible powers.  
3. **Irreducible Quadratics**: Quadratics that cannot be factored further require a linear numerator to preserve the structure of the original fraction.  
4. **Repeated Irreducible Quadratics**: Just like repeated linear factors, these require terms for every power of the factor.  
5. **Improper Fractions**: When the numerator is "too large," we simplify it through division first, leaving a proper fraction for decomposition.

**why the denominator, why don't we factorize the numerator and set the denominator to a constant**

This is an insightful question! The focus on the **denominator** rather than the **numerator** when decomposing into partial fractions is based on **mathematical necessity and practicality**. Let me explain why this is the case and why factoring the denominator is key:

---

### **1. Purpose of Decomposition**  
The goal of partial fraction decomposition is to rewrite a **complex rational expression** into a sum of **simpler fractions** that are easier to work with (e.g., for integration, simplification, or solving equations).  

- The complexity of a rational expression comes from the **denominator** because it determines the restrictions on the fraction (e.g., where it is undefined or has asymptotes).  
- Factoring the denominator reveals the underlying structure of the rational expression, allowing us to simplify it.  

If we factorized the numerator instead, the resulting fractions would not simplify the problem; in fact, they could become more complicated!

---

### **2. Fundamental Role of Denominators in Fractions**  
- In a rational expression $\frac{P(x)}{Q(x)}$, the **denominator $Q(x)$** defines the **domain** and **behavior** of the fraction.  
- Decomposition splits $Q(x)$ into its simpler components (linear or quadratic factors), enabling us to express the fraction in terms of these components.  

**Why not the numerator?**  
- The numerator $P(x)$ is typically "adjusted" (using constants or smaller polynomials) to match the denominator's factors. This adjustment makes the decomposition meaningful.  
- Factoring the numerator would not help us "break apart" the fraction, as we still need to manage the denominator's behavior.

---

### **3. Consistency with Polynomial Division**  
Decomposing into partial fractions assumes that the rational expression is already in **proper form** (i.e., the degree of $P(x)$ is less than the degree of $Q(x)$).  

If the numerator is larger (improper), we perform **polynomial long division** to reduce it:
$$\frac{P(x)}{Q(x)} = H(x) + \frac{R(x)}{Q(x)},$$
where $H(x)$ is a polynomial, and $\frac{R(x)}{Q(x)}$ is the proper fraction.  

In this process, **factoring the denominator** $Q(x)$ is essential, while the numerator is adjusted to "fit" the denominator.  

---

### **4. Logical Structure of Partial Fractions**  
The structure of partial fractions is determined entirely by the factors of the denominator.  
For example:  
$$\frac{P(x)}{(x+1)(x-2)} \quad \text{decomposes to} \quad \frac{A}{x+1} + \frac{B}{x-2}.$$
- Here, the numerator constants $A, B$ are **adjusted** based on $P(x)$, but the form of the decomposition depends entirely on the denominator's factors $(x+1)$ and $(x-2)$.  
- If you instead factored the numerator $P(x)$, it would not change the structure of the denominator, so the decomposition process would remain unchanged.

---

### **5. Why Not Set the Denominator to a Constant?**  
- Setting the denominator to a constant would "lose" the essential structure of the rational expression.  
- For example, consider $\frac{x+1}{(x+1)(x-2)}$:  
  - If we replace the denominator $(x+1)(x-2)$ with a constant, we lose the ability to split the fraction into simpler parts based on its factors.  
  - We cannot identify the contributions from each denominator factor $(x+1)$ and $(x-2)$, which defeats the purpose of decomposition.  

---

### **Conclusion**  
Factoring the denominator instead of the numerator is essential because:  
1. It determines the **behavior and domain** of the rational expression.  
2. It reveals the **simpler components** (linear or quadratic factors) for decomposition.  
3. The numerator is adjusted to fit these components, ensuring simplicity and correctness.  
4. The denominator governs how the rational expression is split into simpler terms.  

### Case 1: **Simple Linear Factors**

#### **Overview**
In this case, the denominator of the rational expression consists of distinct **linear factors**—that is, factors of the form $(ax + b)$, each of which appears **only once** in the denominator.

For example:
$$\frac{P(x)}{(x+1)(x-2)}$$
Here, $x+1$ and $x-2$ are distinct **linear factors**, and each factor appears exactly once.

#### **Why This Case Exists**
The purpose of partial fraction decomposition is to express a rational expression as a sum of simpler fractions. Linear factors, being the simplest polynomial factors, allow us to write the rational expression as a sum of fractions where each term corresponds to a single linear factor in the denominator.

This decomposition is useful because integrating or simplifying fractions with linear denominators is straightforward.

---

#### **General Form**
If the denominator of the rational expression has distinct linear factors, the decomposition takes the form:
$$\frac{P(x)}{(ax+b)(cx+d)} = \frac{A}{ax+b} + \frac{B}{cx+d}$$
Here:
- $A$ and $B$ are **constants** to be determined.
- $ax+b$ and $cx+d$ are the distinct linear factors of the denominator.

---

#### **Step-by-Step Process**

**Step 1: Factorize the Denominator**
- Write the denominator as a product of its distinct linear factors, if it is not already factored.

**Example:**
For $\frac{3x+1}{(x+1)(x-2)}$, the denominator is already factored as $(x+1)(x-2)$.

---

**Step 2: Set Up the Decomposition**
- For each distinct linear factor $(ax+b)$, assign a constant $A, B, C, \dots$ to the numerator.
- Write the rational expression as:
$$\frac{P(x)}{(ax+b)(cx+d)} = \frac{A}{ax+b} + \frac{B}{cx+d}$$

---

**Step 3: Combine the Fractions**
- Rewrite the right-hand side with a common denominator:
$$\frac{A}{ax+b} + \frac{B}{cx+d} = \frac{A(cx+d) + B(ax+b)}{(ax+b)(cx+d)}$$

- Equate the numerator on the left-hand side with the numerator of the combined fraction:
$$P(x) = A(cx+d) + B(ax+b)$$

---

**Step 4: Solve for the Constants**
- Expand the right-hand side and collect like terms in $x$:
$$P(x) = A(cx) + A(d) + B(ax) + B(b)$$
$$P(x) = (Ac + Ba)x + (Ad + Bb)$$

- Match coefficients of $x$ and the constant term on both sides:
1. Coefficient of $x$: $Ac + Ba$
2. Constant term: $Ad + Bb$

- Solve the resulting system of equations to find $A$ and $B$.

---

**Step 5: Write the Decomposed Form**
- Substitute $A$ and $B$ into the partial fraction decomposition.

---

#### **Example**
Decompose:
$$\frac{3x+1}{(x+1)(x-2)}$$

1. **Set up the decomposition:**
$$\frac{3x+1}{(x+1)(x-2)} = \frac{A}{x+1} + \frac{B}{x-2}$$

2. **Combine fractions:**
$$\frac{A}{x+1} + \frac{B}{x-2} = \frac{A(x-2) + B(x+1)}{(x+1)(x-2)}$$

3. **Equate the numerators:**
$$3x + 1 = A(x-2) + B(x+1)$$

4. **Expand and collect terms:**
$$3x + 1 = Ax - 2A + Bx + B$$
$$3x + 1 = (A + B)x + (-2A + B)$$

5. **Match coefficients:**
- Coefficient of $x$: $A + B = 3$
- Constant term: $-2A + B = 1$

6. **Solve the system of equations:**
$$A + B = 3 \quad \text{(1)}$$
$$-2A + B = 1 \quad \text{(2)}$$

From (1): $B = 3 - A$.  
Substitute into (2):
$$-2A + (3 - A) = 1$$
$$-3A + 3 = 1$$
$$-3A = -2 \quad \Rightarrow \quad A = \frac{2}{3}$$

Substitute $A = \frac{2}{3}$ into (1):
$$\frac{2}{3} + B = 3 \quad \Rightarrow \quad B = 3 - \frac{2}{3} = \frac{7}{3}$$

7. **Write the final decomposition:**
$$\frac{3x+1}{(x+1)(x-2)} = \frac{\frac{2}{3}}{x+1} + \frac{\frac{7}{3}}{x-2}$$

---

#### **Key Points**
- The decomposition is possible only when the factors in the denominator are distinct and linear.
- The constants $A, B, \dots$ are determined by solving a system of equations derived from equating the numerators.

### Case 2: **Repeated Linear Factors**

#### **Overview**
In this case, the denominator of the rational expression contains **repeated linear factors**, meaning a linear factor like $(ax + b)$ appears with an exponent $n$ greater than 1. For example, $(x-1)^3$ is a repeated linear factor.

The decomposition involves writing a separate fraction for each power of the repeated factor up to $n$.

---

#### **Why This Case Exists**
When a linear factor is repeated, the rational expression can be broken down into simpler components corresponding to **all powers** of that factor. Each power captures a piece of the behavior of the original rational expression, allowing us to express it in terms of simpler fractions.

---

#### **General Form**
For a rational expression with a repeated linear factor $(ax + b)^n$, the decomposition is:
$$\frac{P(x)}{(ax+b)^n} = \frac{A_1}{ax+b} + \frac{A_2}{(ax+b)^2} + \cdots + \frac{A_n}{(ax+b)^n}$$
Here:
- $A_1, A_2, \dots, A_n$ are **constants** to be determined.
- Each fraction corresponds to a successive power of the factor $(ax+b)$.

---

#### **Step-by-Step Process**

**Step 1: Factorize the Denominator**
- Identify and factorize the denominator to isolate the repeated linear factors.

**Example:**
For $\frac{P(x)}{(x+1)^3}$, the denominator is already factored as $(x+1)^3$.

---

**Step 2: Set Up the Decomposition**
- Write the rational expression as a sum of fractions, with one fraction for each power of the repeated factor:
$$\frac{P(x)}{(x+1)^3} = \frac{A_1}{x+1} + \frac{A_2}{(x+1)^2} + \frac{A_3}{(x+1)^3}$$

---

**Step 3: Combine the Fractions**
- Rewrite the right-hand side with a common denominator:
$$\frac{A_1}{x+1} + \frac{A_2}{(x+1)^2} + \frac{A_3}{(x+1)^3} = \frac{A_1(x+1)^2 + A_2(x+1) + A_3}{(x+1)^3}$$

---

**Step 4: Equate the Numerators**
- Match the numerator on the left-hand side with the numerator of the combined fraction:
$$P(x) = A_1(x+1)^2 + A_2(x+1) + A_3$$

---

**Step 5: Expand and Collect Like Terms**
- Expand the terms on the right-hand side and collect like terms in $x$ to match the polynomial $P(x)$.

---

**Step 6: Solve for the Constants**
- Solve for $A_1, A_2, \dots$ by matching coefficients of $x$ and the constant term from both sides.

---

#### **Example**
Decompose:
$$\frac{2x+3}{(x+1)^2}$$

1. **Set up the decomposition:**
$$\frac{2x+3}{(x+1)^2} = \frac{A_1}{x+1} + \frac{A_2}{(x+1)^2}$$

2. **Combine fractions:**
$$\frac{A_1}{x+1} + \frac{A_2}{(x+1)^2} = \frac{A_1(x+1) + A_2}{(x+1)^2}$$
Sure! Let’s walk through **step by step** how to add the two fractions:

The given expression is:  
$$\frac{A_1}{x+1} + \frac{A_2}{(x+1)^2}$$

### Step-by-Step Addition Process:

---

#### **Step 1: Identify the Least Common Denominator (LCD)**  
The denominators are $x+1$ and $(x+1)^2$.  
The **LCD** is the higher power of the denominator terms, which is:
$$(x+1)^2$$

---

#### **Step 2: Rewrite the Fractions with the LCD**  
To add these fractions, we need to rewrite them so they both have the same denominator $(x+1)^2$:  

1. The first fraction:
$$\frac{A_1}{x+1}$$
Multiply the numerator and denominator by $x+1$ to make the denominator $(x+1)^2$:
$$\frac{A_1}{x+1} = \frac{A_1(x+1)}{(x+1)^2}$$

2. The second fraction already has $(x+1)^2$ as its denominator:
$$\frac{A_2}{(x+1)^2}$$

---

#### **Step 3: Combine the Fractions**  
Now, the expression becomes:
$$\frac{A_1(x+1)}{(x+1)^2} + \frac{A_2}{(x+1)^2}$$

Since the denominators are the same, you can combine the numerators over the common denominator:
$$\frac{A_1(x+1) + A_2}{(x+1)^2}$$

---

#### **Step 4: Simplify the Numerator**  
Expand the numerator $A_1(x+1) + A_2$:  
$$A_1(x+1) + A_2 = A_1x + A_1 + A_2$$

So, the expression becomes:
$$\frac{A_1x + A_1 + A_2}{(x+1)^2}$$

---

### Final Answer:
$$\frac{A_1x + A_1 + A_2}{(x+1)^2}$$


3. **Equate the numerators:**
$$2x + 3 = A_1(x+1) + A_2$$

4. **Expand and collect terms:**
$$2x + 3 = A_1x + A_1 + A_2$$
$$2x + 3 = A_1x + (A_1 + A_2)$$

5. **Match coefficients:**
- Coefficient of $x$: $A_1 = 2$
- Constant term: $A_1 + A_2 = 3$

6. **Solve for the constants:**
- From $A_1 = 2$:
$$2 + A_2 = 3 \quad \Rightarrow \quad A_2 = 1$$

7. **Write the final decomposition:**
$$\frac{2x+3}{(x+1)^2} = \frac{2}{x+1} + \frac{1}{(x+1)^2}$$

---

#### **Key Points**
- This case handles repeated linear factors by assigning a fraction for each power of the factor.
- The constants are determined by solving a system of equations derived from matching numerators.

### **Case 3: Irreducible Quadratic Factors**

---

#### **Overview of Case 3**:
In this case, the denominator has an **irreducible quadratic factor**, which means it cannot be factored further using real numbers. For example, quadratic expressions like $x^2 + bx + c$ where the discriminant $b^2 - 4ac < 0$ are irreducible over the reals.

For these factors, the numerator must be expressed as a linear polynomial $Ax + B$, rather than a constant, because a constant would be insufficient to match the degree of the numerator during decomposition.

---

#### **General Form**:
For a rational expression of the form:
$$\frac{P(x)}{(x^2 + bx + c)}$$
the decomposition is written as:
$$\frac{P(x)}{(x^2 + bx + c)} = \frac{Ax + B}{x^2 + bx + c}$$
where $A$ and $B$ are constants to be determined.

---

### **Why This Case Exists**:
1. **Irreducibility**: Since $x^2 + bx + c$ cannot be factored further, it must stay in the denominator as a single quadratic factor.
2. **Linear Numerator**: The numerator must have the form $Ax + B$, because the numerator’s degree must be **one less than** the denominator’s degree (quadratic denominator → linear numerator).

---

### **Steps to Decompose**:
1. **Write the Rational Expression**: Start with the given rational expression where the denominator has an irreducible quadratic factor.

2. **Set Up the Decomposition**: Write the numerator as $Ax + B$:
   $$\frac{P(x)}{x^2 + bx + c} = \frac{Ax + B}{x^2 + bx + c}$$

3. **Clear the Denominator**: Multiply through by the irreducible quadratic $x^2 + bx + c$ to eliminate the denominator:
   $$P(x) = (Ax + B)(x^2 + bx + c)$$

4. **Expand and Match Terms**: Expand the right-hand side, and then match the coefficients of the terms with the same powers of $x$ on both sides.

5. **Solve for $A$ and $B$**: Solve the resulting system of equations for $A$ and $B$.

---

### **Example**:

Decompose:
$$\frac{5x + 7}{x^2 + 4x + 5}$$

#### **Step 1: Write the Decomposition**:
Since the denominator $x^2 + 4x + 5$ is irreducible, write:
$$\frac{5x + 7}{x^2 + 4x + 5} = \frac{Ax + B}{x^2 + 4x + 5}$$

#### **Step 2: Clear the Denominator**:
Multiply both sides by $x^2 + 4x + 5$:
$$5x + 7 = (Ax + B)(x^2 + 4x + 5)$$

#### **Step 3: Expand the Right-Hand Side**:
Expand $(Ax + B)(x^2 + 4x + 5)$:
$$5x + 7 = A(x^3 + 4x^2 + 5x) + B(x^2 + 4x + 5)$$
$$5x + 7 = Ax^3 + 4Ax^2 + 5Ax + Bx^2 + 4Bx + 5B$$

#### **Step 4: Combine Like Terms**:
Group terms by powers of $x$:
$$5x + 7 = Ax^3 + (4A + B)x^2 + (5A + 4B)x + 5B$$

#### **Step 5: Match Coefficients**:
Since there is no $x^3$ or $x^2$ term on the left-hand side, their coefficients must be zero:
- Coefficient of $x^3$: $A = 0$
- Coefficient of $x^2$: $4A + B = 0$

For the linear and constant terms:
- Coefficient of $x$: $5A + 4B = 5$
- Constant term: $5B = 7$

#### **Step 6: Solve for $A$ and $B$**:
1. From $A = 0$, substitute into $4A + B = 0$:
   $$B = 0$$
2. From $5B = 7$

Apologies for the abrupt cutoff earlier! Let's continue solving the system of equations:

---

We reached this point:
- $A = 0$  
- $5B = 7$

---

### Solving for $B$:
$$5B = 7 \implies B = \frac{7}{5}$$

---

### Substitute Back:
Now that $A = 0$ and $B = \frac{7}{5}$, the partial fraction decomposition becomes:
$$\frac{5x + 7}{x^2 + 4x + 5} = \frac{0 \cdot x + \frac{7}{5}}{x^2 + 4x + 5}$$
This simplifies to:
$$\frac{5x + 7}{x^2 + 4x + 5} = \frac{\frac{7}{5}}{x^2 + 4x + 5}$$

---

### Final Form:
$$\frac{5x + 7}{x^2 + 4x + 5} = \frac{7}{5(x^2 + 4x + 5)}$$

---

### Key Notes:
1. **Linear Numerator**: Even though the numerator started as $5x + 7$, solving the equations revealed that $A = 0$, meaning only the constant term $B$ remained relevant.
2. **Irreducible Quadratic Denominator**: The denominator stays $x^2 + 4x + 5$ because it's irreducible over real numbers.

### **Case 4: Repeated Irreducible Quadratic Factors**

---

#### **Overview of Case 4**:
This case arises when the denominator contains **repeated irreducible quadratic factors** like $(x^2 + bx + c)^n$, where $n$ is greater than 1. Since the quadratic factor cannot be factored further over real numbers, and it is repeated, the decomposition includes terms with increasing powers of the irreducible quadratic factor in the denominators.

---

#### **General Form**:
For a rational expression:
$$\frac{P(x)}{(x^2 + bx + c)^n}$$
the decomposition is written as:
$$\frac{P(x)}{(x^2 + bx + c)^n} = \frac{A_1x + B_1}{x^2 + bx + c} + \frac{A_2x + B_2}{(x^2 + bx + c)^2} + \cdots + \frac{A_nx + B_n}{(x^2 + bx + c)^n}$$
where $A_1, B_1, A_2, B_2, \dots, A_n, B_n$ are constants to be determined.

---

#### **Why This Form?**:
- **Irreducibility**: The quadratic factor $x^2 + bx + c$ cannot be factored further using real numbers.
- **Repeated Denominator**: Since the quadratic is repeated, each term must include all powers of $(x^2 + bx + c)$ from 1 to $n$.
- **Linear Numerator**: The numerators must be linear polynomials ($Ax + B$) to ensure a match for terms in the numerator during expansion.

---

### **Steps to Decompose**:
1. **Write the Rational Expression**: Start with the given expression where the denominator has repeated irreducible quadratic factors.

2. **Set Up the Decomposition**: Write the numerator of each term as $Ax + B$, and include all powers of the quadratic factor from $1$ to $n$.

3. **Clear the Denominator**: Multiply through by the repeated irreducible quadratic factor to eliminate the denominator.

4. **Expand and Match Terms**: Expand the right-hand side and match coefficients of powers of $x$ on both sides of the equation.

5. **Solve for Constants**: Solve the resulting system of equations to determine $A_1, B_1, A_2, B_2, \dots$.

---

### **Example**:

Decompose:
$$\frac{2x^2 + 5x + 3}{(x^2 + 4x + 5)^2}$$

#### **Step 1: Write the Decomposition**:
The denominator $(x^2 + 4x + 5)^2$ is a repeated irreducible quadratic factor, so write:
$$\frac{2x^2 + 5x + 3}{(x^2 + 4x + 5)^2} = \frac{A_1x + B_1}{x^2 + 4x + 5} + \frac{A_2x + B_2}{(x^2 + 4x + 5)^2}$$

---

#### **Step 2: Clear the Denominator**:
Multiply through by $(x^2 + 4x + 5)^2$ to eliminate the denominators:
$$2x^2 + 5x + 3 = (A_1x + B_1)(x^2 + 4x + 5) + (A_2x + B_2)$$

---

#### **Step 3: Expand the Right-Hand Side**:
Expand $(A_1x + B_1)(x^2 + 4x + 5)$:
$$(A_1x + B_1)(x^2 + 4x + 5) = A_1x^3 + 4A_1x^2 + 5A_1x + B_1x^2 + 4B_1x + 5B_1$$
$$= A_1x^3 + (4A_1 + B_1)x^2 + (5A_1 + 4B_1)x + 5B_1$$

Add $(A_2x + B_2)$ to this:
$$2x^2 + 5x + 3 = A_1x^3 + (4A_1 + B_1)x^2 + (5A_1 + 4B_1)x + 5B_1 + A_2x + B_2$$

---

#### **Step 4: Match Coefficients**:
Match coefficients of $x^3, x^2, x^1,$ and the constant term:

1. **Coefficient of $x^3$**: $A_1 = 0$ (since there is no $x^3$ term on the left-hand side).
2. **Coefficient of $x^2$**: $4A_1 + B_1 = 2$.
3. **Coefficient of $x^1$**: $5A_1 + 4B_1 + A_2 = 5$.
4. **Constant term**: $5B_1 + B_2 = 3$.

---

#### **Step 5: Solve for Constants**:
1. From $A_1 = 0$, substitute into $4A_1 + B_1 = 2$:
   $$B_1 = 2$$

2. Substitute $A_1 = 0$ and $B_1 = 2$ into $5A_1 + 4B_1 + A_2 = 5$:
   $$4(2) + A_2 = 5 \implies 8 + A_2 = 5 \implies A_2 = -3$$

3. Substitute $B_1 = 2$ into $5B_1 + B_2 = 3$:
   $$5(2) + B_2 = 3 \implies 10 + B_2 = 3 \implies B_2 = -7$$

---

#### **Step 6: Write the Decomposition**:
Substitute $A_1 = 0, B_1 = 2, A_2 = -3, B_2 = -7$ into the decomposition:
$$\frac{2x^2 + 5x + 3}{(x^2 + 4x + 5)^2} = \frac{0x + 2}{x^2 + 4x + 5} + \frac{-3x - 7}{(x^2 + 4x + 5)^2}$$

Simplify:
$$\frac{2x^2 + 5x + 3}{(x^2 + 4x + 5)^2} = \frac{2}{x^2 + 4x + 5} - \frac{3x + 7}{(x^2 + 4x + 5)^2}$$

---

### **Final Answer**:
$$\frac{2x^2 + 5x + 3}{(x^2 + 4x + 5)^2} = \frac{2}{x^2 + 4x + 5} - \frac{3x + 7}{(x^2 + 4x + 5)^2}$$

### **Summary of Partial Fraction Decomposition**

Partial fraction decomposition is a technique used to break down a rational function into a sum of simpler fractions. The approach depends on the nature of the denominator and involves several cases. Here's what we've covered so far:

---

### **General Steps for Decomposition**
1. **Check the Degree**: Ensure the degree of the numerator is less than the degree of the denominator. If not, use polynomial long division first.
2. **Factorize the Denominator**: Fully factor the denominator into linear and/or irreducible quadratic factors.
3. **Set Up Partial Fractions**: Write the decomposition based on the factors of the denominator.
4. **Clear the Denominator**: Multiply through by the denominator to eliminate fractions.
5. **Expand and Match Terms**: Expand the right-hand side and equate coefficients of powers of $x$ to form a system of equations.
6. **Solve for Constants**: Solve the system to determine the coefficients of the partial fractions.

---

### **Cases**
1. **Case 1: Distinct Linear Factors**
   - If the denominator has distinct linear factors like $(x - a)(x - b)$, write:
     $$\frac{P(x)}{(x - a)(x - b)} = \frac{A}{x - a} + \frac{B}{x - b}$$

2. **Case 2: Repeated Linear Factors**
   - If the denominator has repeated linear factors like $(x - a)^n$, write:
     $$\frac{P(x)}{(x - a)^n} = \frac{A_1}{x - a} + \frac{A_2}{(x - a)^2} + \cdots + \frac{A_n}{(x - a)^n}$$

3. **Case 3: Irreducible Quadratic Factors**
   - If the denominator has irreducible quadratic factors like $x^2 + bx + c$, write:
     $$\frac{P(x)}{(x^2 + bx + c)} = \frac{Ax + B}{x^2 + bx + c}$$

4. **Case 4: Repeated Irreducible Quadratic Factors**
   - If the denominator has repeated irreducible quadratic factors like $(x^2 + bx + c)^n$, write:
     $$\frac{P(x)}{(x^2 + bx + c)^n} = \frac{A_1x + B_1}{x^2 + bx + c} + \frac{A_2x + B_2}{(x^2 + bx + c)^2} + \cdots + \frac{A_nx + B_n}{(x^2 + bx + c)^n}$$

---

### **Key Insights**
- **Linear Factors**: Use constants ($A, B, \dots$) in the numerator.
- **Irreducible Quadratic Factors**: Use linear numerators ($Ax + B$).
- **Repeated Factors**: Include terms for every power of the repeated factor.
- **Clearing Denominators**: Multiply through by the least common denominator (LCD) to simplify the equation.
- **Solving Coefficients**: Match terms for each power of $x$ to form equations.

---

### **Example Summary**
- Distinct linear factors:
  $$\frac{3x + 5}{(x - 1)(x + 2)} = \frac{A}{x - 1} + \frac{B}{x + 2}$$
  Solve for $A$ and $B$.

- Repeated linear factors:
  $$\frac{x^2 + 3}{(x - 2)^2} = \frac{A}{x - 2} + \frac{B}{(x - 2)^2}$$

- Irreducible quadratic factors:
  $$\frac{x^2 + 4x + 5}{x^2 + x + 1} = \frac{Ax + B}{x^2 + x + 1}$$

- Repeated irreducible quadratic factors:
  $$\frac{2x^2 + 5x + 3}{(x^2 + 4x + 5)^2} = \frac{2}{x^2 + 4x + 5} - \frac{3x + 7}{(x^2 + 4x + 5)^2}$$

---

### **Why Use Partial Fractions?**
- Simplifies integration of rational functions.
- Useful in solving differential equations.
- Simplifies algebraic manipulation in applied mathematics and engineering problems.



