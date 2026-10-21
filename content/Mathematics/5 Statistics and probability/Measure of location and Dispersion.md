---
tags:
  - grade9
  - unit6
  - statistics
aliases: 
theme: statistics and probability
Unit: statistics
status: start
---
#grade9 #statistics #unit6 
# Measure of Location

There are three rules of measuring location of data; these are:
- **Mean (arithmatic mean)**
- **Mode**
- **Median**

### Mean (arithmatic mean)
Sometimes known as *average*,
- It is the sum of all the values divided by their total number of values.

Mathematically,
$$ \frac{x_1 + x_2 + x_3 + ... + x_n}{n} = \text{mean} (\bar{x}) $$

#### Deviation of Means (one of the properties of mean)
It is the difference between the value and the mean.

1. The sum of the individual measurements from the mean $\text{ is zero}$

   **proof:**
$$
(x_1 + x_2 + x_3 + ... + x_n = \bar{x}) \\
\text{So, } x_1 + x_2 + x_3 + ... + x_n = n \bar{x}
$$

Now,
$$
(x_1 - \bar{x}) + (x_2 - \bar{x}) + ... + (x_n - \bar{x}) \\
= \frac{(x_1 + x_2 + x_3 + ... + x_n) - (\bar{x} + \bar{x} + ... + \bar{x})}{n} \\
= \frac{\textstyle\sum (x_i - \bar{x})}{n} - \frac{(\bar{x} \cdot n)}{n}
$$
$$
\therefore \textstyle\sum (x_i - \bar{x}) = 0 \text{ is prooved.}
$$

2. If a constant $\bar{K}$ is added (substracted) to the mean then the new mean is the sum of the constant and the old mean.

   **Proof:**
$$
\frac{(x_1 + K) + (x_2 + K) + (x_3 + K) + ... + (x_n + K)}{n}
$$

$$
= \frac{x_1 + x_2 + x_3 + ... + x_n}{n} + \frac{nK}{n}
$$

$$
= \frac{\bar{X} \cdot n}{n} + k \\
= \bar{X} + K \\
$$

3. The mean of the sum or the difference of two population function (from equal observation) is the sum of the difference of the two population function mean.

Let,
$$ x = \frac{x_1 + x_2 + x_3 + ... + x_n}{n} \\
\text{and } y = \frac{y_1 + y_2 + y_3 + ... + y_n}{n}
$$

Now,
$$
\text{M} ( \bar{X} + y) \\
= \frac{x_1 + x_2 + x_3 + ... + x_n + y_1 + y_2 + y_3 + ... + y_n}{n}
$$

$$
= \frac{\bar{X} \cdot n}{n} + \frac{y \cdot n}{n} \\
= {\bar{X} + y}
$$

4. The mean of a constant and a time a population function is equal to the constant times the population function.

**Proof**

$$\frac{x_1 + x_2 + x_3 + \cdots + x_n}{n} = \frac{k(1 + x_1 + x_2 + \cdots + x_n)}{n} = \overline{kX}$$

- **Mean value is unique.**
- **The mean is affected by extreme values.**

## 2. Median

- The value in the middle of a data is known as a **median**.
- There are two possibilities in median: 
  - *Odd*
  - *Even*

If odd, the last middle no. is taken.

If even, the last two *nos* mean is the median.

- Median can be obtained even if it is an *unknown value*.
- **Median is unique.**
- The **median** is not affected by *extreme values*.

## 3. Mode

The value that is repeated in data is known as **mode**.

- If there is only one mode, it is called **unimodal**. Ex. 1, 2, 1, 4, 3.
- If there are two, **bimodal**. Ex. 2, 1, 2, 4, 1.
- If there are more than two, **multimodal**. Ex. 2, 1, 2, 1, 2, 4.
- If there is no mode, then no modal. Ex. 4, 2, 3, 5.
- Mode is not **unique**.
- Mode is not affected by *extreme values*.






## Measure of Dispersion

There are three ways covered in this book to measure dispersion. These are:
1. **Range**
2. **Variance**
3. **Standard Deviation**

### 1. Range

- Is the data's highest value minus the lowest value.
$$R = h - l$$

### 2. Variance $(\sigma^2)$

- Is the mean of the squared deviation of each value from the mean.

### 3. Standard Deviation $(\sigma)$

- Is the square root of the variance.
$$\sigma = \sqrt{\sigma^2}$$

#### Steps to calculate Standard Deviation

1. Find the mean.
2. Find the deviation of each mean $(X - \overline{X})$.
3. Square each of the deviation $(X - \overline{X})^2$.
4. Find the mean of the squared deviations, which will give the value called **variance**.
5. Take the **principal square root** of $\sigma$.

   **Standard deviation**=$\sqrt{ \text{variance} } \Rightarrow \sqrt{ \sigma^2 } = \sigma$

#### 1. Add a constant $a$
If a constant $a$ is added to each value of the population, the old standard deviation is equal to the new one (the same for the variance).

**Proof:**
$$
X_1 + a, X_2 + a, X_3 + a, \ldots, X_n + a
$$

Now 
$$
\sigma^2 = \frac{ [(X_1 + a) - (\overline{X} + a)]^2 + [(X_2 + a) - (\overline{X} + a)]^2 + \ldots + [(X_n + a) - (\overline{X} + a)]^2 }{n}
$$

Simplified,
$$
= \frac{(X_1 - \overline{X})^2 + (X_2 - \overline{X})^2 + \ldots + (X_n - \overline{X})^2}{n} = \sigma^2 \Rightarrow \text{old variance}
$$

#### 2. Multiply a constant $C$  
If a constant $C$ is multiplied by a population function,

1. The new variance is $C^2$ times the old variance.
2. The new standard deviation is $|C|$ times the old standard deviation.

**Proof:**
$$
\frac{C(X_1 - \overline{X})^2 + C(X_2 - \overline{X})^2 + \ldots (Cn - \overline{C}\overline{X})^2}{n}
$$

Now 
$$
= \frac{ c^2[(X_1 - \overline{X})]^2 + [(X_2 - \overline{X})]^2 + \ldots + [(X_n - \overline{X})]^2 }{n}
$$
$$ c^2 \times old \quad variance=c^2\sigma^2$$
$$
\sigma=\sqrt{c^2.\sigma^2}=c.\sigma 
$$
standard deviation = constant $\times$ old standard deviation 