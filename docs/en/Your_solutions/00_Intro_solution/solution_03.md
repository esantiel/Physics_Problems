# Dot Product – Step-by-Step Solution

## Problem

Given two vectors in 3D space

$$
\vec{a} = [2,1,-3], \qquad \vec{b} = [4,-2,1]
$$

Find:

1. The **dot product** $$\vec{a}\cdot\vec{b}$$  
2. The **angle between the vectors**

---

# 1️⃣ Basic Theory

## Dot Product Definition

For two vectors

$$
\vec{a} = [a_1,a_2,a_3], \quad \vec{b} = [b_1,b_2,b_3]
$$

the **dot product** is defined as

$$
\vec{a}\cdot\vec{b} = a_1b_1 + a_2b_2 + a_3b_3
$$

The dot product produces a **scalar value**.

---

## Geometric Interpretation

The dot product is related to the **angle between two vectors**:

$$
\vec{a}\cdot\vec{b} = |\vec{a}|\,|\vec{b}|\cos\theta
$$

where

- $$|\vec{a}|$$ = magnitude of vector $$\vec{a}$$

- $$|\vec{b}|$$ = magnitude of vector $$\vec{b}$$

- $$\theta$$ = angle between the vectors


---

# 2️⃣ Magnitude of a Vector

The magnitude of a vector

$$
\vec{v} = [v_x,v_y,v_z]
$$

is

$$
|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}
$$

---

# 3️⃣ Step-by-Step Solution

## Step 1: Write the Vectors

$$
\vec{a} = [2,1,-3]
$$

$$
\vec{b} = [4,-2,1]
$$

---

# 4️⃣ Compute the Dot Product

Using

$$
\vec{a}\cdot\vec{b} = a_1b_1 + a_2b_2 + a_3b_3
$$

Substitute values:

$$
\vec{a}\cdot\vec{b} =
(2)(4) + (1)(-2) + (-3)(1)
$$

Compute each term:

$$
2\times4 = 8
$$

$$
1\times(-2) = -2
$$

$$
(-3)\times1 = -3
$$

Add them:

$$
\vec{a}\cdot\vec{b} = 8 - 2 - 3
$$

$$
\vec{a}\cdot\vec{b} = 3
$$

✅ **Dot Product Result**

$$
\vec{a}\cdot\vec{b} = 3
$$

---

# 5️⃣ Find the Angle Between the Vectors

Using

$$
\cos\theta =
\frac{\vec{a}\cdot\vec{b}}{|\vec{a}||\vec{b}|}
$$

---

## Magnitude of Vector a

$$
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2}
$$

$$
|\vec{a}| = \sqrt{4+1+9}
$$

$$
|\vec{a}| = \sqrt{14}
$$

---

## Magnitude of Vector b

$$
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2}
$$

$$
|\vec{b}| = \sqrt{16+4+1}
$$

$$
|\vec{b}| = \sqrt{21}
$$

---

## Substitute Into Formula

$$
\cos\theta =
\frac{3}{\sqrt{14}\sqrt{21}}
$$

Combine radicals:

$$
\cos\theta =
\frac{3}{\sqrt{294}}
$$

Approximate:

$$
\cos\theta \approx 0.175
$$

---

## Final Angle

$$
\theta = \cos^{-1}(0.175)
$$

$$
\theta \approx 79.9^\circ
$$

---

# ✅ Final Results

### Dot Product

$$
\vec{a}\cdot\vec{b} = 3
$$

### Angle Between Vectors

$$
\theta \approx 79.9^\circ
$$

---

# 📌 Key Insight

- If $$\vec{a}\cdot\vec{b} > 0$$ → vectors point roughly in the **same direction**
- If $$\vec{a}\cdot\vec{b} = 0$$ → vectors are **perpendicular**
- If $$\vec{a}\cdot\vec{b} < 0$$ → vectors point in **opposite directions**
