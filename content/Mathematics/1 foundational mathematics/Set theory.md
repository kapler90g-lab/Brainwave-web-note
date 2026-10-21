---
tags:
  - grade9
  - sets
  - unit3
aliases:
theme: foundational mathematics
Unit: further on sets
status: done
---
#grade9 #unit3 #further_on_sets
## **Sets**

> A **set** is a **well-defined collection of distinct objects**, and these objects are called **elements** or **members** of the set. The term "*well-defined*" is crucial.  It means that for any given object, we can definitively determine whether or not it belongs to the set. There should be no ambiguity.

- **Well-Defined Example**: The *collection of even numbers between 1 and 10*. We can clearly say that 2, 4, 6, 8, and 10 are in this set, and no other numbers are. This is well-defined.

- **Not Well-Defined Example**: The *collection of "beautiful paintings."* What makes a painting "beautiful" is subjective and varies from person to person. We cannot definitively say whether a given painting belongs to this collection. This is not well-defined.

Identifying whether a collection is well-defined is the key to determining if it's a set. If the *criteria for membership* are **clear and objective**, it's a set. If they are **subjective or vague**, it is not.


### *Set Membership Notation*

In set theory, we use specific symbols to indicate whether an element belongs to a set or not. This is a fundamental part of writing and understanding mathematical statements about sets.

| Symbol | Meaning                                                                            | Example                                                     |
| ------ | ---------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| $\{\}$ | since the phrase "the set of" occurs so often, we use the symbol called **braces** | A = {1, 2, 3}                                               |
| ∈      | "is an element of" or "belongs to"                                                 | If A = {1, 2, 3}, then 2 ∈ A (2 is an element of set A)     |
| ∉      | "is not an element of" or "does not belong to"                                     | If A = {1, 2, 3}, then 4 ∉ A (4 is not an element of set A) |
We typically use **capital letters** (like A, B, C) to represent sets and **small letters** (like x, y, z) to represent elements within those sets. This is a convention that helps keep mathematical notation clear and easy to follow.

## **Description of Sets**

A set may be described in three methods:

#### *Verbal Method*

> The Verbal Method is the most straightforward way to describe a set. It involves using a simple, ordinary English language statement to define the set by clearly stating the characteristic or property that its elements must possess.

- Example 1: The set of all even natural numbers less than 10.
- Example 2: The set of all days in a week.
   
   
#### *The Listing Method (Roster or Enumeration Method)*

> As the name suggests, the Listing Method involves describing a set by **listing all of its elements** within curly braces `{}`.The elements are separated by commas.

- **List All Elements**: Every element of the set is explicitly written out.
- **Curly Braces {}** : The list of elements is enclosed within curly braces.
- **Elements Separated by Commas**: A comma is used to distinguish each element in the list.
- **Order Doesn't Matter**: The order in which the elements are listed does not change the set.
- **No Duplicates**: Each element is listed only once, even if it appears multiple times in the original collection.

	Set of the first five natural numbers -> **statement form** 
	{1, 2, 3, 4, 5} -> **listing method form**

The Listing Method is very clear and leaves no doubt about which elements are in the set. However, it's most practical for sets with a small number of elements. For sets with many elements or infinite sets, we use a variation of the listing method called **partial listing**

In partial listing, we list the first few elements to establish a clear pattern and then use an ellipsis `...` to indicate that the pattern continues.
	 Example: Set of all positive integers -> {1, 2, 3, ...}, 
	 Set of odd numbers less than 20 -> {1, 3, 5, ..., 19}


#### *set builder method( method of defining property)*

> The Set Builder Method describes a set by stating a **common property or condition** that all its members must satisfy.

The general form of set builder notation is: { $x | P(x)$}
	$x$ is A variable representing any element in the set.
	 $|$ or $:$ Read as "such that"
	 $P(x)$ is known as the **predicate** and is the one that defines the property or condition that x must satisfy to be an element of the set.

So, {$x | P(x)$} is read as "the set of all $x$ such that $x$ satisfies the property $P(x)$."

For Example: the set A containing all x such that x is all numbers between 2 and 10 is written as:

$$ A = \{ x | x \in \mathbb{N} \text{ and } 2 < x < 10 \} $$
Set of all natural numbers greater than 5:

{ $x | x ∈ ℕ, x > 5$} (Here, ∈ means "belongs to" and ℕ represents the set of natural numbers)

The Set Builder Method is very precise and can describe a wide range of sets concisely. It requires understanding mathematical symbols and notation, but it's an essential tool in higher mathematics.

## **The Notion of Sets**

> **Cardinality** is an operator that provides the *number of elements a set contains*. you feed it a set and it outputs the number of elements it contains. and is written as $n(s)$.

based on the cardinality of a set we can have three main types of sets:
### *Empty set(∅)*

> The **empty set**, also known as the **null set** or **void set**, is a unique set that contains **no elements**. it is a set that has a cardinality of zero. and is denoted by {} or ∅.

Think of it as an empty container or a collection with nothing inside. Even though it has no elements, it is still considered a set because it is a well-defined collection (it's well-defined by the fact that it contains _nothing_).

**Example:** Set of all months with 32 days(There are no months with 32 days, so this set is empty.) Set of all prime numbers divisible by 6 (The only prime number divisible by 6 would have to be 6 itself, but 6 is not prime (its factors are 1, 2, 3, and 6). Thus, this set is empty.)

The empty set has a *cardinality (number of elements) of 0*. The set *{0} has a cardinality of 1* because it contains the element 0. They are not the same.

### *finite and Infinite sets*

> **Finite sets** are sets contenting a finite number of elements and contain a cardinality of some specific natural number.

> **Infinite sets** are sets contenting an infinite number of elements and thus contain a cardinality of infinity(∞)

| Feature            | *Finite Set*                                                         | *Infinite Set*          |
| ------------------ | -------------------------------------------------------------------- | ----------------------- |
| Number of Elements | Countable (a specific natural number)                                | Uncountable (limitless) |
| Cardinality        | A natural number (n(A) = n)                                          | Infinite (n(A) = ∞)     |
| Listing Elements   | Can be fully listed (or partially with ellipsis if pattern is clear) | Cannot be fully listed  |
| Endpoint           | Has a clear endpoint                                                 | Extends indefinitely    |

**Example of finite sets:** *Set of days in a week* {Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday}. There are 7 elements and thus is a finite set. *The empty set* { } or ∅. It has 0 elements, and 0 is a finite number.

**Example of infinite sets:** *Set of all natural numbers*. {1, 2, 3, ...}. The numbers continue indefinitely.

The **cardinality** of a set is the number of elements it contains.  For a finite set, the cardinality is a *natural number*.  For an infinite set, the cardinality is considered *infinite*.

### *Equal and Equivalent set*

The key difference lies in what we are comparing: the **elements** themselves or the **number of elements** 

| Feature                  | Equal Sets                         | Equivalent Sets                                         |
| ------------------------ | ---------------------------------- | ------------------------------------------------------- |
| Definition               | Contain exactly the same elements. | Contain the same number of elements (same cardinality). |
| Symbol                   | =                                  | ~ or ≡ or ≈                                             |
| Requirement for Elements | Elements must be identical.        | Elements can be different.                              |
| Relationship             | All equal sets are equivalent.     | Not all equivalent sets are equal.                      |

> **Equal Sets** are sets that contain Identical elements with the same cardinality.

- Two sets A and B are **equal** if and only if they contain **exactly the same elements**. The order in which the elements are listed does not matter, and duplicate elements in the listing are ignored.

	Set A = {1, 2, 3}, Set B = {3, 1, 2}. A = B because they have the same elements.

As stated in the table, if two sets are equal, they must also be equivalent, because having the exact same elements means they must have the same number of elements


> **Equivalent Sets** are sets that contain the same cardinality regardless of the the identity of the elements.

-  Two sets A and B are **equivalent** if and only if they have the **same number of elements**. The specific elements themselves do not need to be the same, only the count of elements.

	Set G = {a, b, c}, Set H = {x, y, z}. G is equivalent to H (G ~ H or G ≡ H) because both sets have 3 elements.

It's important to remember that equivalent sets are not necessarily equal. For example, {a, b} and {1, 2} are equivalent but not equal because their elements are different.

### *Universal set(U)*

> **Universal sets** are supersets that contain the all the elements that are being considered in a problem.

- A **universal set (U)** is a set that **contains all elements under consideration** for a particular discussion or problem. Think of it as the overarching set that encompasses all the possible elements you might be working with in a given scenario.

- **Contains All Relevant** Elements: It includes every element that could possibly be a member of any of the sets being discussed within a specific context.

- **Context-Dependent**: The universal set is not a fixed set; it depends on the problem or discussion at hand. What is considered the universal set can change depending on the context.

- **Superset of All Other Sets**: Every other set being considered within that context is a subset of the universal set.

The universal set is commonly denoted by the symbol **U** (or sometimes E or ξ).

**Example**:

**Context: Sets of even and odd numbers less than 10**
- A possible universal set could be the set of all natural numbers less than 10: U = {1, 2, 3, 4, 5, 6, 7, 8, 9}.
**Context: Sets of different types of triangles and quadrilaterals**
- A possible universal set could be the set of all polygons.

As you can see, the choice of the universal set is crucial because it defines the boundaries of your discussion. All other sets you work with in that context will be subsets of this universal set


### *Subsets and Proper subsets*

These concepts describe when one set is 'contained within' another set, either entirely or with some elements left over in the larger set.

> **Subset(⊆)** set A is a subset of set B if all of the elements in A are also in B and there exists the possibility that A is equal to B.

**Example**: Let A = {1, 2} and B = {1, 2, 3}. A ⊆ B because every element in A (1 and 2) is also in B. Let E = {a, b} and F = {a, b}. E ⊆ F. This shows that a set is always a subset of itself.

**Properties of a Subset**:

- Any set is a subset of itself.
- The empty set (∅) is a subset of every set. ∅ ⊆ A for any set A.
- The number of subsets a finite set can have is determined by its cardinality. If a set has 'n' elements, the total number of subsets is $2^n$

> **Proper Subset(⊂)**  set A is a **proper subset** of set B if **every element in A is also an element in B, AND A is not equal to B**. This means that B must contain at least one element that is not in A. A$⊆$B and A$≠$B.

**Example:** Let A = {1, 2} and B = {1, 2, 3}. A ⊂ B because all elements of A are in B, and B contains 3, which is not in A. A is not equal to B.

**Properties of a Proper subset**:

- For any set 𝐴, 𝐴 is not a proper subset of itself, as a set cannot not equal to itself.
- The number of proper subsets of set 𝐴 is $2^𝑛−1$ (we subtract 1 because the set itself is a subset but not a proper subset).
- Empty set is the proper subset of any other set than itself.
- If set 𝐴 is subset of set 𝐵(𝐴⊆𝐵),conversely 𝐵is **superset** of 𝐴 written as 𝐵⊃𝐴.

| Feature           | Subset (⊆)                          | Proper Subset (⊂)                      |
| ----------------- | ----------------------------------- | -------------------------------------- |
| Definition        | Every element of A is in B.         | Every element of A is in B, AND A ≠ B. |
| Equality Allowed? | Yes, A can be equal to B.           | No, A cannot be equal to B.            |
| Analogy           | A is part of B (could be all of B). | A is a smaller part of B.              |
Think of a subset as being 'less than or equal to' in terms of containment, while a proper subset is strictly 'less than'.

## **Operations on sets**

### *Venn Diagrams*

> A **Venn diagram** is a visual representation used to show the relationships between different sets.

- It uses overlapping circles within a rectangle, where the rectangle represents the **universal set** (U), which includes all possible elements being considered in a particular context. Each circle within the rectangle represents a specific set.

![[Pasted image 20260125123201.png]]

- **Universal Set**: The set of all possible elements under consideration.
- **Subsets**: When all elements of one set are also elements of another set.
- **Overlapping Sets**: When two or more sets share common elements.
- **Disjoint Sets**: When two sets have no elements in common.

### *Union and Intersection*

> The **union** of two sets, A and B, denoted by A ∪ B, is the set of all elements that are in A, or in B, or in both. Think of it as combining all the elements from both sets into a new set, without duplicating any elements.

In set-builder notation, the union of A and B is expressed as: $$A ∪ B = \text{ x | x ∈ A or x ∈ B}$$

![[Pasted image 20260125123228.png]]

> The **intersection** of two sets, A and B, denoted by A ∩ B, is the set of all elements that are common to both A and B. These are the elements that appear in _both_ sets

In set-builder notation, the intersection of A and B is expressed as: $$A ∩ B = \text{x | x ∈ A and x ∈ B}$$
When two sets have no elements in common, their intersection is the **empty set**, denoted by {} or ∅. These sets are called **disjoint sets**.

![[Pasted image 20260125124316.png]]

| Feature                | Union (A ∪ B)                | Intersection (A ∩ B)            |
| ---------------------- | ---------------------------- | ------------------------------- |
| Definition             | Elements in A, or B, or both | Elements common to both A and B |
| Symbol                 | ∪                            | ∩                               |
| Logical Correspondence | OR                           | AND                             |
| Venn Diagram           | Entire area of both circles  | Overlapping area of circles     |
| Set-Builder Notation   | {x \| x ∈ A or x ∈ B}        | {x \| x ∈ A and x ∈ B}          |

### *Complement of Sets*

> The **complement** of a set A, denoted by A', is the set of all elements in the **universal set** (U) that are _not_ in A. Remember, the universal set is the set containing all possible elements relevant to a particular context.

In set-builder notation, the complement of A is expressed as: $$A' = \text{x | x ∈ U and x ∉ A}$$
![[Pasted image 20260125124711.png]]

An important concept related to complements is **De Morgan's Laws**. These laws provide a way to simplify expressions involving complements, unions, and intersections. There are two main laws:

- The complement of the union of two sets is equal to the intersection of their complements: $$ (A ∪ B)' = A' ∩ B' $$
![[Pasted image 20260125130122.png]]
- The complement of the intersection of two sets is equal to the union of their complements: $$(A ∩ B)' = A' ∪ B'$$
![[Pasted image 20260125130133.png]]


### *Difference of Sets*

> The **difference** between two sets A and B, denoted by A - B or A \ B, is the set of all elements that are in set A but are _not_ in set B. It's like taking set A and removing any elements that it shares with set B.

In set-builder notation, the difference of A and B is expressed as: $$A - B = \text{x | x ∈ A and x ∉ B}$$
There's a useful relationship between the difference of sets and the intersection with the complement. The difference A - B is equivalent to the intersection of set A and the complement of set B (A'). This can be written as: $$A - B = A ∩ B'$$

![[Pasted image 20260125130559.png]]

### *Symmetric Difference of Two Sets*

> The **symmetric difference** of two sets A and B, denoted by A ∆ B , is the set of all elements that are in either set A or set B, but _not_ in both.

In other words, it includes all the elements that are unique to each set, excluding the elements they have in common.

- The symmetric difference is the union of A and B minus their intersection: $A ∆ B = (A ∪ B) - (A ∩ B)$ . This means we take all elements in either set and then remove the elements that are in both.

- The symmetric difference is the union of the difference between A and B, and the difference between B and A: $A ∆ B = (A - B) ∪ (B - A)$. This means we take the elements only in A and combine them with the elements only in B.

The symmetric difference is commutative, meaning the order of the sets does not matter: $A ∆ B = B ∆ A$.

![[Pasted image 20260125131510.png]]


### *Cartesian Product of Two Sets*

> The **Cartesian product** of two sets, A and B, denoted by A × B, is the set of all possible **ordered pairs** where the first element of each pair comes from set A and the second element comes from set B.

In set-builder notation, the Cartesian product of A and B is expressed as: $$A × B = \text {(a, b) | a ∈ A and b ∈ B}$$
Unlike the previous set operations which combined elements based on their presence in the original sets, the Cartesian product creates _new_ elements which are these ordered pairs.

The order of the sets in the Cartesian product matters. A × B is generally not the same as B × A.

If n(A) represents the number of elements in set A and n(B) represents the number of elements in set B, then the number of elements in A × B is given by the formula:

$$n(A × B) = n(A) × n(B)$$

Determining the original sets A and B from their Cartesian product can be done by observing the first and second elements of the ordered pairs. Set A will be the set of all unique first elements in the ordered pairs, and Set B will be the set of all unique second elements.

## **Application of Set Theory**

When we want to find the number of elements in the **union** of two sets, A and B (n(A ∪ B)), we might initially think of simply adding the number of elements in A and the number of elements in B: n(A) + n(B).

However, if sets A and B have common elements (i.e., their intersection is not empty), simply adding n(A) and n(B) would result in counting the common elements twice – once as part of set A and once as part of set B.

To correct for this double-counting, we need to subtract the number of elements in the intersection of A and B (n(A ∩ B)) from the sum of n(A) and n(B)). This gives us the formula for the cardinality of the union of two finite sets:


$$n(A ∪ B) = n(A) + n(B) - n(A ∩ B)$$

In the case of **disjoint sets**, where A ∩ B = ∅ (the empty set), there are no common elements.

 The formula for the cardinality of the union of disjoint sets simplifies to:

$$n(A ∪ B) = n(A) + n(B)$$






