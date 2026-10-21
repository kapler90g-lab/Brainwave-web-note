---
tags:
  - grade11
  - determinants_and_their_properties
  - unit4
aliases: 
theme: linear algebra
Unit: determinants and their properties
status: start
---
#grade11 #unit4 #determinants_and_their_properties


## **The Determinant of Order 2 matrices**

The determinant of a **2×2 matrix** is calculated using the following formula:

### Given a matrix:
$$A = \begin{bmatrix} a & b \\ c & d \end{bmatrix}$$

The determinant of $A$, denoted as $\det(A)$ or $|A|$, is given by:

$$\det(A) = (a \cdot d) - (b \cdot c)$$

1. **If $\det(A) \neq 0$**:
   - The matrix is **invertible** (it has an inverse).
   - The system of linear equations associated with the matrix has a **unique solution**.
   - The matrix represents a transformation that does not collapse the plane into a lower dimension.

2. **If $\det(A) = 0$**:
   - The matrix is **singular** (it does not have an inverse).
   - The system of equations associated with it has either **no solution** or **infinitely many solutions**.
   - The transformation represented by the matrix **collapses** the space into a lower dimension (e.g., maps a plane to a line or a point).

3. **Geometric Interpretation**:
   - The determinant represents the **scaling factor** of area for the transformation defined by the matrix.
   - If $\det(A) = 1$, the transformation preserves area.
   - If $|\det(A)| > 1$, the transformation enlarges the area.
   - If $0 < |\det(A)| < 1$, the transformation shrinks the area.
   - A negative determinant means the transformation **includes a reflection**.

### **Meaning of the Determinant**  
1. **Geometric Interpretation**:  
   - The **absolute value** of the determinant represents the **area scaling factor** of the linear transformation described by the matrix. For example, if the determinant is 3, areas are scaled by 3.  
   - If the determinant is **zero**, the transformation collapses space into a lower dimension (e.g., a line or point), resulting in an area of zero.  

2. **Orientation**:  
   - The **sign** of the determinant indicates whether the transformation preserves ($+$) or reverses ($−$) orientation. A negative determinant implies a reflection (e.g., flipping space).  

3. **Invertibility**:  
   - A **non-zero determinant** means the matrix is invertible (non-singular).  
   - A **zero determinant** means the matrix is singular (no inverse exists).  

4. **Systems of Equations**:  
   - In systems like $A\mathbf{x} = \mathbf{b}$, a non-zero determinant guarantees a **unique solution**. A zero determinant implies either no solution or infinitely many solutions.  

### **Example**  
For $\begin{bmatrix} 2 & 1 \\ 3 & 4 \end{bmatrix}$:  
$$\text{det} = (2)(4) - (1)(3) = 8 - 3 = 5$$  
This means:  
- Areas are scaled by 5.  
- The matrix is invertible.  
- Orientation is preserved (positive determinant).  

- **determinants are only defined for square matrices** (matrices with the same number of rows and columns). For non-square matrices (e.g., $m×nm×n$ where $m≠nm=n$), the determinant **does not exist** and cannot be computed.


## The minor and a cofactor of an Element of a Matrix 

### **Minor of a Matrix**
The **minor** of an element in a matrix is the determinant of a smaller matrix obtained by removing the row and column of that element.

#### **Definition**:
For an $n \times n$ matrix $A$, the **minor** of an element $A_{ij}$ (the element in the $i$-th row and $j$-th column) is denoted as $M_{ij}$. It is the determinant of the **submatrix** that remains after removing the $i$-th row and $j$-th column from $A$.

#### **Example (3×3 Matrix)**:
Let’s take a **3×3** matrix:

$$A = \begin{bmatrix} 
1 & 2 & 3 \\ 
4 & 5 & 6 \\ 
7 & 8 & 9 
\end{bmatrix}$$

The **minor of $A_{11}$** (element **1**, first row, first column) is found by removing the **first row** and **first column**, leaving the matrix:

$$M_{11} = \begin{vmatrix} 5 & 6 \\ 8 & 9 \end{vmatrix}$$

The determinant of this **2×2** matrix is:

$$\det(M_{11}) = (5 \cdot 9) - (6 \cdot 8) = 45 - 48 = -3$$

So, the **minor of $A_{11}$ is -3**.

- the *Minor of an element in a 2x2 matrix is the value of the Element itself*.

#### **Minors in Higher Order Matrices**:
For larger matrices (like $4 \times 4$ or more), the minor is always found by **removing the corresponding row and column** and calculating the determinant of the remaining submatrix.



### **Cofactor of a Matrix**  

The **cofactor** of an element in a matrix is its **minor** with an added sign based on its position in the matrix.

#### **Definition**:
For an $n \times n$ matrix $A$, the **cofactor** of an element $A_{ij}$ (the element in the $i$-th row and $j$-th column) is denoted as:

$$C_{ij} = (-1)^{i+j} M_{ij}$$

where:
- $M_{ij}$ is the **minor** of $A_{ij}$ (the determinant of the submatrix obtained by removing the $i$-th row and $j$-th column).
- $(-1)^{i+j}$ applies a **sign change** based on the position it is called **the sign factor**.

---

### **Cofactor Pattern (Sign Matrix)**
The sign pattern for cofactors follows this alternating rule:

For a **3×3 matrix**:

$$\begin{bmatrix} 
+ & - & + \\ 
- & + & - \\ 
+ & - & + 
\end{bmatrix}$$

For a **4×4 matrix**:

$$\begin{bmatrix} 
+ & - & + & - \\ 
- & + & - & + \\ 
+ & - & + & - \\ 
- & + & - & + 
\end{bmatrix}$$

---

### **Example (3×3 Matrix)**

Given:

$$A = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}$$

Let's find the **cofactor of $A_{11}$**:

1. Compute the **minor** $M_{11}$ (remove row 1, column 1):

   $$M_{11} = \begin{vmatrix} 5 & 6 \\ 8 & 9 \end{vmatrix} = (5 \cdot 9) - (6 \cdot 8) = 45 - 48 = -3$$

2. Apply the **cofactor formula**:

   $$C_{11} = (-1)^{1+1} \cdot M_{11} = (+1) \cdot (-3) = -3$$

---

### **Cofactors in Determinants**  
Cofactors are used in finding the **determinant** of a matrix using cofactor expansion (Laplace expansion). For a **3×3 matrix**, the determinant is:

$$\det(A) = a_{11} C_{11} + a_{12} C_{12} + a_{13} C_{13}$$

where each $C_{ij}$ is the cofactor of $A_{ij}$.



### **Where Does the Cofactor Come From?**
The cofactor arises naturally in the **Laplace expansion** (also called cofactor expansion) of the determinant. The Laplace expansion provides a recursive way to compute the determinant of a matrix by expanding along a row or column. The alternating sign $(-1)^{i+j}$ ensures that the contributions of minors are correctly weighted to produce the determinant.

---

### **Proof of the Laplace Expansion**
We will prove the Laplace expansion formula for the determinant of an $n \times n$ matrix $A$. The formula for expanding along the $i$-th row is:
$$\det(A) = \sum_{j=1}^n (-1)^{i+j} a_{ij} M_{ij}$$

#### **Step 1: Base Case (2×2 Matrix)**
For a $2 \times 2$ matrix:
$$A = \begin{bmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{bmatrix}$$
The determinant is:
$$\det(A) = a_{11}a_{22} - a_{12}a_{21}$$
This matches the Laplace expansion along the first row:
$$\det(A) = (-1)^{1+1} a_{11} M_{11} + (-1)^{1+2} a_{12} M_{12}$$
where:
- $M_{11} = a_{22}$ (minor of $a_{11}$),
- $M_{12} = a_{21}$ (minor of $a_{12}$).

Thus:
$$\det(A) = (1) a_{11} a_{22} + (-1) a_{12} a_{21} = a_{11}a_{22} - a_{12}a_{21}$$

#### **Step 2: Inductive Step**
Assume the Laplace expansion holds for an $(n-1) \times (n-1)$ matrix. We will show it holds for an $n \times n$ matrix.

Consider expanding along the $i$-th row of $A$. Each element $a_{ij}$ in the $i$-th row is multiplied by its cofactor $C_{ij} = (-1)^{i+j} M_{ij}$, where $M_{ij}$ is the determinant of the $(n-1) \times (n-1)$ submatrix obtained by deleting the $i$-th row and $j$-th column.

By the inductive hypothesis, the determinant of the submatrix $M_{ij}$ can be computed using the Laplace expansion. Summing these contributions over all columns $j$ gives the determinant of $A$:
$$\det(A) = \sum_{j=1}^n (-1)^{i+j} a_{ij} M_{ij}$$

#### **Step 3: Why the Alternating Sign?**
The alternating sign $(-1)^{i+j}$ ensures that the contributions of minors are correctly weighted to account for the **orientation** of the matrix. This sign alternates in a checkerboard pattern:
- If $i + j$ is even, the sign is $+1$.
- If $i + j$ is odd, the sign is $-1$.

This alternation ensures that the determinant respects the **antisymmetric property** of permutations, which is fundamental to its definition.


- The determinant is computed using a **weighted sum of minors**, where each minor is multiplied by its corresponding element and a sign factor. Simply adding all the minors without these weights does not give the determinant. The cofactor expansion formula ensures the correct computation of the determinant.

### **Determinant of a 3×3 Matrix**  

For a **3×3 matrix**:

$$A = \begin{bmatrix} 
a_{11} & a_{12} & a_{13} \\ 
a_{21} & a_{22} & a_{23} \\ 
a_{31} & a_{32} & a_{33} 
\end{bmatrix}$$

The determinant of $A$, denoted as **$\det(A)$ or $|A|$**, is calculated using the **Laplace Expansion** along any row or column.

---

### **Formula Using the First Row**:

$$\det(A) = a_{11}C_{11} + a_{12}C_{12} + a_{13}C_{13}$$

where each **cofactor** is:

$$C_{ij} = (-1)^{i+j} M_{ij}$$

and **$M_{ij}$** is the **minor determinant** (the determinant of the $2×2$ matrix obtained by removing the $i$-th row and $j$-th column).

---

### **Step-by-Step Example**
Let’s compute the determinant of:

$$A = \begin{bmatrix} 
1 & 2 & 3 \\ 
4 & 5 & 6 \\ 
7 & 8 & 9 
\end{bmatrix}$$

#### **Step 1: Compute the Minors**
1. **Minor of $A_{11}$** (remove row 1, column 1):

   $$M_{11} = \begin{vmatrix} 5 & 6 \\ 8 & 9 \end{vmatrix}$$

   $$(5 \times 9) - (6 \times 8) = 45 - 48 = -3$$

2. **Minor of $A_{12}$** (remove row 1, column 2):

   $$M_{12} = \begin{vmatrix} 4 & 6 \\ 7 & 9 \end{vmatrix}$$

   $$(4 \times 9) - (6 \times 7) = 36 - 42 = -6$$

3. **Minor of $A_{13}$** (remove row 1, column 3):

   $$M_{13} = \begin{vmatrix} 4 & 5 \\ 7 & 8 \end{vmatrix}$$

   $$(4 \times 8) - (5 \times 7) = 32 - 35 = -3$$

#### **Step 2: Compute Cofactors**
$$C_{11} = (-1)^{1+1} (-3) = (-3)$$

$$C_{12} = (-1)^{1+2} (-6) = (+6)$$

$$C_{13} = (-1)^{1+3} (-3) = (-3)$$

#### **Step 3: Compute Determinant**
$$\det(A) = (1 \times -3) + (2 \times 6) + (3 \times -3)$$

$$= -3 + 12 - 9$$

$$= 0$$

### **Conclusion**
Since $\det(A) = 0$, this matrix is **singular** (non-invertible), meaning its rows or columns are linearly dependent.


#### Rule of Sarrus
<iframe width="560" height="315" src="https://www.youtube.com/embed/x2vWqtYwZ1g?si=05y7W8glkitfRci5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


### Properties of Determinants

#### 1. **Determinants of Triangular Matrices**
Triangular matrices include upper triangular, lower triangular, and diagonal matrices. The determinant of a triangular matrix is the product of its diagonal elements.

- **Upper Triangular Matrix**: A matrix where all elements below the main diagonal are zero.
  - Example:  
    $$A = \begin{pmatrix}
    a_{11} & a_{12} & \cdots & a_{1n} \\
    0 & a_{22} & \cdots & a_{2n} \\
    \vdots & \vdots & \ddots & \vdots \\
    0 & 0 & \cdots & a_{nn}
    \end{pmatrix}$$
    The determinant is $|A| = a_{11} a_{22} \cdots a_{nn}$.

- **Lower Triangular Matrix**: A matrix where all elements above the main diagonal are zero.
  - Example:  
    $$A = \begin{pmatrix}
    a_{11} & 0 & \cdots & 0 \\
    a_{21} & a_{22} & \cdots & 0 \\
    \vdots & \vdots & \ddots & \vdots \\
    a_{n1} & a_{n2} & \cdots & a_{nn}
    \end{pmatrix}$$
    The determinant is $|A| = a_{11} a_{22} \cdots a_{nn}$.

- **Diagonal Matrix**: A special case of triangular matrices where all off-diagonal elements are zero. The determinant is still the product of the diagonal entries.

- **Identity Matrix**: The identity matrix $I_n$ is a diagonal matrix with 1s on the diagonal, so $|I_n| = 1$.

---

#### 2. **Determinant and Elementary Row Operations**
Elementary row operations affect the determinant of a matrix in specific ways:

- **Interchanging Rows**: Swapping two rows of a matrix changes the sign of the determinant.
  - If $B$ is obtained by swapping rows $i$ and $j$ of $A$, then $|B| = -|A|$.

- **Multiplying a Row by a Scalar**: Multiplying one row of a matrix by a scalar $k$ multiplies the determinant by $k$.

- **Adding a Multiple of One Row to Another**: Adding a scalar multiple of one row to another row does not change the determinant.

- If the entire matrix is multiplied by a scalar $k$, the determinant is multiplied by $k^n$, where $n$ is the order of the matrix: $|kA| = k^n |A|$.

---

#### 3. **Determinant of Product of Matrices and Determinant of a Transpose**
- **Determinant of a Transpose**: The determinant of a matrix and its transpose are equal.
  - $|A| = |A^t|$.

- **Determinant of a Product**: The determinant of the product of two matrices is the product of their determinants.
  - $|AB| = |A| |B|$.

---

#### 4. **Determinant of the Inverse of a Matrix**
- If $A$ is invertible, then $|A| \neq 0$, and the determinant of the inverse is the reciprocal of the determinant of $A$.
  - $|A^{-1}| = \frac{1}{|A|}$.

---

#### 5. **Determinant of a Singular Matrix**
- A matrix is **singular** if its determinant is zero ($|A| = 0$). This means the matrix does not have an inverse.
- If a matrix is singular, it corresponds to a system of linear equations with either no solution or infinitely many solutions.

---


### Summary of Key Properties
1. **Triangular Matrices**: The determinant is the product of the diagonal elements.
2. **Elementary Row Operations**:
   - Swapping rows: Changes the sign of the determinant.
   - Multiplying a row by a scalar: Multiplies the determinant by that scalar.
   - Adding a multiple of one row to another: Does not change the determinant.
3. **Transpose**: $|A| = |A^t|$.
4. **Product of Matrices**: $|AB| = |A| |B|$.
5. **Inverse**: If $A$ is invertible, $|A^{-1}| = \frac{1}{|A|}$.
6. **Singular Matrices**: If $|A| = 0$, the matrix is singular and non-invertible.
7. **Block Matrices**: Determinant of block diagonal matrices is the product of the determinants of the blocks.

These properties are fundamental in linear algebra and are used extensively in solving systems of equations, finding inverses, and understanding matrix transformations.


The **adjoint of a matrix** (also called the **adjugate matrix**) is a key concept in linear algebra, particularly in computing the inverse of a matrix. Below, I’ll explain its **definition**, **concept**, and the **easiest way to compute it**.

---

The **adjoint of a matrix** (also called the **adjugate matrix**) is a key concept in linear algebra, particularly in computing the inverse of a matrix. Below, I’ll explain its **definition**, **concept**, and the **easiest way to compute it**.

---
## Inverse of a square Matrix of order 2 and 3

### **Definition of the Adjoint**

For a square matrix $A$ of size $n \times n$, the **adjoint** (or adjugate) of $A$, denoted $\text{adj}(A)$, is the transpose of the **cofactor matrix** of $A$. 

- The **cofactor matrix** is formed by replacing each element $a_{ij}$ of $A$ with its corresponding **cofactor** $C_{ij}$.
- The **cofactor** $C_{ij}$ is defined as:
  $$C_{ij} = (-1)^{i+j} M_{ij},$$
  where $M_{ij}$ is the **minor** of $a_{ij}$ (the determinant of the submatrix obtained by deleting the $i$-th row and $j$-th column).

---

## **Concept of the Adjoint**
1. **Role in Matrix Inverse**:
   The adjoint is used to compute the inverse of a matrix $A$ using the formula:
   $$A^{-1} = \frac{1}{\det(A)} \cdot \text{adj}(A).$$
   This formula works only if $\det(A) \neq 0$ (i.e., $A$ is invertible).

2. **Geometric Interpretation**:
   The adjoint is related to the **scaling factor** of the linear transformation represented by $A$. It encodes information about how the transformation affects volume and orientation.

3. **Connection to Cofactors**:
   The adjoint is essentially a reorganization of the cofactors of $A$, transposed to align with the original matrix structure.

---

### **Step 1: Compute the Cofactor Matrix**
1. For each element $a_{ij}$ in $A$, compute its **minor** $M_{ij}$ (the determinant of the submatrix obtained by deleting the $i$-th row and $j$-th column).
2. Multiply the minor by $(-1)^{i+j}$ to get the cofactor $C_{ij}$.
3. Replace each element $a_{ij}$ with its cofactor $C_{ij}$ to form the **cofactor matrix**.

### **Step 2: Transpose the Cofactor Matrix**
- Take the transpose of the cofactor matrix to get the adjoint $\text{adj}(A)$.

---

### **Example**
Let’s compute the adjoint of the following $3 \times 3$ matrix:
$$A = \begin{bmatrix}
1 & 2 & 3 \\
0 & 1 & 4 \\
5 & 6 & 0
\end{bmatrix}$$

#### **Step 1: Compute the Cofactor Matrix**
1. **Cofactor $C_{11}$**:
   $$M_{11} = \det\begin{bmatrix} 1 & 4 \\ 6 & 0 \end{bmatrix} = (1)(0) - (4)(6) = -24,$$
   $$C_{11} = (-1)^{1+1} M_{11} = (-24).$$

2. **Cofactor $C_{12}$**:
   $$M_{12} = \det\begin{bmatrix} 0 & 4 \\ 5 & 0 \end{bmatrix} = (0)(0) - (4)(5) = -20,$$
   $$C_{12} = (-1)^{1+2} M_{12} = 20.$$

3. **Cofactor $C_{13}$**:
   $$M_{13} = \det\begin{bmatrix} 0 & 1 \\ 5 & 6 \end{bmatrix} = (0)(6) - (1)(5) = -5,$$
   $$C_{13} = (-1)^{1+3} M_{13} = (-5).$$

4. Repeat for all elements to get the cofactor matrix:
   $$\text{Cofactor Matrix} = \begin{bmatrix}
   -24 & 20 & -5 \\
   18 & -15 & 4 \\
   5 & -4 & 1
   \end{bmatrix}$$

#### **Step 2: Transpose the Cofactor Matrix**
$$\text{adj}(A) = \begin{bmatrix}
-24 & 18 & 5 \\
20 & -15 & -4 \\
-5 & 4 & 1
\end{bmatrix}$$

---

---

## **Key Takeaways**
1. The adjoint is the **transpose of the cofactor matrix**.
2. It is used to compute the inverse of a matrix: $A^{-1} = \frac{1}{\det(A)} \cdot \text{adj}(A)$.
3. For small matrices, compute the adjoint manually by finding cofactors and transposing. For larger matrices, use computational tools.




The relationship between the **adjugate (adjoint) matrix** and the **determinant** of a square matrix $A$ is given by the key matrix identity:

$$A \cdot \text{adj}(A) = \text{adj}(A) \cdot A = \det(A) \cdot I$$

where:
- $A$ is an $n \times n$ square matrix.
- $\text{adj}(A)$ (also called the **adjugate matrix**) is the **transpose of the cofactor matrix** of $A$.
- $\det(A)$ is the determinant of $A$.
- $I$ is the $n \times n$ identity matrix.

### **Key Observations:**
1. **If $A$ is invertible ($\det(A) \neq 0$)**, then we can use the adjugate to find the inverse:
   $$A^{-1} = \frac{\text{adj}(A)}{\det(A)}$$
   This shows that the adjugate matrix helps compute the inverse when the determinant is nonzero.

2. **If $A$ is singular ($\det(A) = 0$)**, then:
   $$A \cdot \text{adj}(A) = 0$$
   meaning $A$ has no inverse, and at least one row (or column) is dependent on another.

3. **For a $3 \times 3$ matrix example:**
   If
   $$A = \begin{bmatrix} a & b & c \\ d & e & f \\ g & h & i \end{bmatrix}$$
   then its adjugate is:
   $$\text{adj}(A) = \begin{bmatrix} C_{11} & C_{21} & C_{31} \\ C_{12} & C_{22} & C_{32} \\ C_{13} & C_{23} & C_{33} \end{bmatrix}^T$$
   where $C_{ij}$ are the cofactors of $A$.

4. **If $A$ is an identity matrix**, then:
   $$\text{adj}(I) = I \quad \text{and} \quad \det(I) = 1$$
   so the formula still holds.







### **Cramer's Rule: A Detailed Explanation**
Cramer’s Rule is a mathematical theorem used to solve systems of **linear equations** using determinants. It is particularly useful for solving small systems, though it becomes computationally expensive for larger ones.

---

## **1. Definition of Cramer's Rule**
Cramer’s Rule states that if we have a system of **n linear equations** with **n unknowns**, represented in matrix form as:

$$A \mathbf{x} = \mathbf{b}$$

where:
- $A$ is an $n \times n$ square matrix (coefficient matrix).
- $\mathbf{x}$ is the column vector of unknowns:  
  $$\mathbf{x} = \begin{bmatrix} x_1 \\ x_2 \\ \vdots \\ x_n \end{bmatrix}$$
- $\mathbf{b}$ is the column vector of constants (right-hand side values):  
  $$\mathbf{b} = \begin{bmatrix} b_1 \\ b_2 \\ \vdots \\ b_n \end{bmatrix}$$
- $\det(A)$ is the determinant of $A$, and it **must be nonzero** ($\det(A) \neq 0$) for Cramer's Rule to apply.

Then, each unknown $x_i$ is found using:

$$x_i = \frac{\det(A_i)}{\det(A)}$$

where $A_i$ is the matrix obtained by **replacing the $i$-th column** of $A$ with the column vector $\mathbf{b}$.

---

## **2. Step-by-Step Example (2 × 2 System)**
Consider the system:

$$\begin{cases}
2x + 3y = 5 \\
4x - y = 6
\end{cases}$$

### **Step 1: Write the Coefficient Matrix $A$**
$$A = \begin{bmatrix} 2 & 3 \\ 4 & -1 \end{bmatrix}$$

### **Step 2: Compute $\det(A)$**
$$\det(A) = (2 \times -1) - (3 \times 4) = -2 - 12 = -14$$

### **Step 3: Construct Matrices $A_x$ and $A_y$**
- $A_x$ (Replace the first column with $b$):  
  $$A_x = \begin{bmatrix} 5 & 3 \\ 6 & -1 \end{bmatrix}$$

- $A_y$ (Replace the second column with $b$):  
  $$A_y = \begin{bmatrix} 2 & 5 \\ 4 & 6 \end{bmatrix}$$

### **Step 4: Compute Determinants $\det(A_x)$ and $\det(A_y)$**
$$\det(A_x) = (5 \times -1) - (3 \times 6) = -5 - 18 = -23$$
$$\det(A_y) = (2 \times 6) - (5 \times 4) = 12 - 20 = -8$$

### **Step 5: Compute $x$ and $y$**
$$x = \frac{\det(A_x)}{\det(A)} = \frac{-23}{-14} = \frac{23}{14}$$
$$y = \frac{\det(A_y)}{\det(A)} = \frac{-8}{-14} = \frac{4}{7}$$

Thus, the solution is:

$$\left( x, y \right) = \left( \frac{23}{14}, \frac{4}{7} \right)$$

---

## **3. General Case for $3 \times 3$ Systems**
For a system:

$$\begin{cases}
a_1x + b_1y + c_1z = d_1 \\
a_2x + b_2y + c_2z = d_2 \\
a_3x + b_3y + c_3z = d_3
\end{cases}$$

1. Compute the determinant of the coefficient matrix $A$:

   $$A = \begin{bmatrix} 
   a_1 & b_1 & c_1 \\ 
   a_2 & b_2 & c_2 \\ 
   a_3 & b_3 & c_3
   \end{bmatrix}$$

2. Replace columns to form $A_x, A_y, A_z$:

   - $A_x$ → replace the **first column** with $\mathbf{b}$.
   - $A_y$ → replace the **second column** with $\mathbf{b}$.
   - $A_z$ → replace the **third column** with $\mathbf{b}$.

3. Compute:

   $$x = \frac{\det(A_x)}{\det(A)}, \quad y = \frac{\det(A_y)}{\det(A)}, \quad z = \frac{\det(A_z)}{\det(A)}$$

---

## **4. Conditions and Limitations**
- **Cramer’s Rule works only when $\det(A) \neq 0$** (i.e., the system has a unique solution).
- If $\det(A) = 0$:
  - **If $\det(A_x), \det(A_y), \dots$ are also 0, the system has infinitely many solutions** (dependent system).
  - **If at least one of $\det(A_x), \det(A_y), \dots$ is nonzero, the system is inconsistent** (no solution).

---

## **5. Advantages and Disadvantages**
### **Advantages**
- Provides an explicit formula for the solution.
- Conceptually easy for small systems.
- Useful for theoretical applications and proving properties.

### **Disadvantages**
- **Computationally inefficient** for large systems due to determinant calculations.
- Not practical for large-scale numerical solutions compared to **Gaussian elimination** or **LU decomposition**.

---

## **6. Summary**
- **Cramer’s Rule solves $n \times n$ linear systems using determinants**.
- It expresses each variable as a **ratio of determinants**.
- **Only applicable when $\det(A) \neq 0$ (unique solution exists).**
- More useful for **theoretical understanding** than for large-scale computation.




