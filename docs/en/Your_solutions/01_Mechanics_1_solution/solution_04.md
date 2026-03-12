# 4. Vector Calculus

The position of an object is given by

$$
\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}
$$

Find:

1. The **velocity vector**
2. The **acceleration vector**

as functions of time.

---

# 1️⃣ Basic Theory

In **vector calculus**, the motion of an object in two or three dimensions can be described using a **position vector**.

$$
\vec{r}(t) = x(t)\hat{i} + y(t)\hat{j}
$$

where

- $x(t)$ = position in the $x$ direction
- $y(t)$ = position in the $y$ direction
- $\hat{i}, \hat{j}$ = unit vectors in the coordinate directions

---

## Velocity Vector

Velocity is the **rate of change of position with respect to time**.

$$
\vec{v}(t) = \frac{d\vec{r}(t)}{dt}
$$

This means we differentiate each component of the position vector.

---

## Acceleration Vector

Acceleration is the **rate of change of velocity with respect to time**.

$$
\vec{a}(t) = \frac{d\vec{v}(t)}{dt}
$$

Equivalently,

$$
\vec{a}(t) = \frac{d^2\vec{r}(t)}{dt^2}
$$

---

# 2️⃣ Given Position Vector

The object's position is

$$
\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}
$$

So the components are

$$
x(t) = 3t^2
$$

$$
y(t) = 5t - 8t^2
$$

---

# 3️⃣ Find the Velocity Vector

Velocity is the **first derivative of the position vector**.

$$
\vec{v}(t) = \frac{d}{dt}[(3t^2)\hat{i} + (5t - 8t^2)\hat{j}]
$$

Differentiate each component separately.

---

## Differentiate the $x$ component

$$
\frac{d}{dt}(3t^2) = 6t
$$

---

## Differentiate the $y$ component

$$
\frac{d}{dt}(5t - 8t^2)
$$

Derivative of each term:

$$
\frac{d}{dt}(5t) = 5
$$

$$
\frac{d}{dt}(-8t^2) = -16t
$$

So

$$
\frac{d}{dt}(5t - 8t^2) = 5 - 16t
$$

---

## Velocity Vector

Therefore

$$
\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}
$$

---

# 4️⃣ Find the Acceleration Vector

Acceleration is the **derivative of the velocity vector**.

$$
\vec{a}(t) = \frac{d}{dt}[(6t)\hat{i} + (5 - 16t)\hat{j}]
$$

---

## Differentiate the $x$ component

$$
\frac{d}{dt}(6t) = 6
$$

---

## Differentiate the $y$ component

$$
\frac{d}{dt}(5 - 16t) = -16
$$

---

## Acceleration Vector

Thus

$$
\vec{a}(t) = 6\hat{i} - 16\hat{j}
$$

---

# ✅ Final Answers

### Velocity Vector

$$
\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}
$$

---

### Acceleration Vector

$$
\vec{a}(t) = 6\hat{i} - 16\hat{j}
$$

---

# 📌 Key Idea

- **Velocity** is the **first derivative** of the position vector.
- **Acceleration** is the **second derivative** of the position vector.

In this example:

- Velocity **changes with time**
- Acceleration is **constant**