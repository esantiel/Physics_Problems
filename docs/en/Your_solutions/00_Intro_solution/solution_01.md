# 1. Vector Algebra – Step-by-Step Solution

## Problem

Given two vectors in 3D space

$$
\vec{a} = [2,\,1,\,-3], \qquad \vec{b} = [4,\,-2,\,1]
$$

Calculate:

a) The magnitude of each vector  
b) The dot product \( \vec{a}\cdot\vec{b} \)  
c) The cross product \( \vec{a}\times\vec{b} \)  
d) The angle between the vectors  

---

# 1️⃣ Basic Theory and Formulas

## Vector in 3D

A vector in three-dimensional space can be written as

$$
\vec{v} = [v_x, v_y, v_z]
$$

where

- \(v_x\) is the x-component  
- \(v_y\) is the y-component  
- \(v_z\) is the z-component  

---

# 2️⃣ Magnitude of a Vector

## Formula

The magnitude (or length) of a vector

$$
\vec{v} = [v_x, v_y, v_z]
$$

is

$$
|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}
$$

This comes from the **3D Pythagorean theorem**.

---

# 3️⃣ Dot Product

## Formula

For two vectors

$$
\vec{a} = [a_1,a_2,a_3], \quad \vec{b} = [b_1,b_2,b_3]
$$

the dot product is

$$
\vec{a}\cdot\vec{b} = a_1b_1 + a_2b_2 + a_3b_3
$$

Another important relationship:

$$
\vec{a}\cdot\vec{b} = |\vec{a}|\,|\vec{b}| \cos\theta
$$

where \( \theta \) is the angle between the vectors.

---

# 4️⃣ Cross Product

## Formula

The cross product of two vectors in 3D is

$$
\vec{a}\times\vec{b}
=
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
a_1 & a_2 & a_3 \\
b_1 & b_2 & b_3
\end{vmatrix}
$$

Expanding the determinant:

$$
\vec{a}\times\vec{b} =
(a_2b_3 - a_3b_2)\mathbf{i}
-
(a_1b_3 - a_3b_1)\mathbf{j}
+
(a_1b_2 - a_2b_1)\mathbf{k}
$$

---

# 5️⃣ Angle Between Two Vectors

Using the dot product identity:

$$
\cos\theta = \frac{\vec{a}\cdot\vec{b}}{|\vec{a}|\,|\vec{b}|}
$$

Thus

$$
\theta = \cos^{-1}\left(\frac{\vec{a}\cdot\vec{b}}{|\vec{a}|\,|\vec{b}|}\right)
$$

---

# 6️⃣ Solve the Problem

---

# a) Magnitude of Each Vector

## Magnitude of \( \vec{a} \)

Vector:

$$
\vec{a} = [2,1,-3]
$$

Apply the magnitude formula:

$$
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2}
$$

Step-by-step:

$$
|\vec{a}| = \sqrt{4 + 1 + 9}
$$

$$
|\vec{a}| = \sqrt{14}
$$

Approximation:

$$
|\vec{a}| \approx 3.742
$$

---

## Magnitude of \( \vec{b} \)

Vector:

$$
\vec{b} = [4,-2,1]
$$

$$
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2}
$$

Step-by-step:

$$
|\vec{b}| = \sqrt{16 + 4 + 1}
$$

$$
|\vec{b}| = \sqrt{21}
$$

Approximation:

$$
|\vec{b}| \approx 4.583
$$

---

# b) Dot Product

Using

$$
\vec{a}\cdot\vec{b} = a_1b_1 + a_2b_2 + a_3b_3
$$

Substitute values:

$$
\vec{a}\cdot\vec{b} =
(2)(4) + (1)(-2) + (-3)(1)
$$

Step-by-step:

$$
= 8 - 2 - 3
$$

$$
= 3
$$

Thus

$$
\vec{a}\cdot\vec{b} = 3
$$

---

# c) Cross Product

Using the determinant formula

$$
\vec{a}\times\vec{b}
=
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
2 & 1 & -3 \\
4 & -2 & 1
\end{vmatrix}
$$

---

## Compute Each Component

### i-component

$$
(1)(1) - (-3)(-2)
$$

$$
= 1 - 6
$$

$$
= -5
$$

---

### j-component

$$
(2)(1) - (-3)(4)
$$

$$
= 2 + 12
$$

$$
= 14
$$

Remember the negative sign:

$$
-14
$$

---

### k-component

$$
(2)(-2) - (1)(4)
$$

$$
= -4 - 4
$$

$$
= -8
$$

---

## Final Cross Product

$$
\vec{a}\times\vec{b} = [-5,-14,-8]
$$

or

$$
-5\mathbf{i} -14\mathbf{j} -8\mathbf{k}
$$

---

# d) Angle Between the Vectors

Using

$$
\cos\theta = \frac{\vec{a}\cdot\vec{b}}{|\vec{a}|\,|\vec{b}|}
$$

Substitute known values:

$$
\cos\theta =
\frac{3}{\sqrt{14}\sqrt{21}}
$$

Combine radicals:

$$
\cos\theta =
\frac{3}{\sqrt{294}}
$$

Approximate denominator:

$$
\sqrt{294} \approx 17.146
$$

Thus

$$
\cos\theta \approx 0.175
$$

Finally

$$
\theta = \cos^{-1}(0.175)
$$

$$
\theta \approx 79.9^\circ
$$

---

# ✅ Final Answers

### Magnitudes

$$
|\vec{a}| = \sqrt{14} \approx 3.742
$$

$$
|\vec{b}| = \sqrt{21} \approx 4.583
$$

---

### Dot Product

$$
\vec{a}\cdot\vec{b} = 3
$$

---

### Cross Product

$$
\vec{a}\times\vec{b} = [-5,-14,-8]
$$

---

### Angle Between Vectors

$$
\theta \approx 79.9^\circ
$$

---

# 🎯 Key Takeaways

- **Magnitude** measures vector length.
- **Dot product** measures similarity in direction.
- **Cross product** produces a vector perpendicular to both vectors.
- **Angle between vectors** comes from the dot-product identity.