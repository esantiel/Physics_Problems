# 📘 Dynamics with a Time-Dependent Force

We are given:

- Mass:

$$
m = 3 \ \text{kg}
$$

- Force:

$$
\vec F(t) = (15t,\ 3t - 12,\ -6t^2)
$$

- Initial conditions:

$$
\vec r(0) = (5, 2, -3), \quad \vec v(0) = (2, 0, 1)
$$

We are asked to find:
- Velocity $( \vec v(t) )$
- Position $( \vec r(t) )$

---

# 🧠 Theory

## Newton’s Second Law

$$
\vec F = m \vec a
$$

So:

$$
\vec a(t) = \frac{\vec F(t)}{m}
$$

---

## Kinematics with Time-Dependent Acceleration

- Velocity:

$$
\vec v(t) = \vec v_0 + \int_0^t \vec a(\tau)\, d\tau
$$

- Position:

$$
\vec r(t) = \vec r_0 + \int_0^t \vec v(\tau)\, d\tau
$$

---

# ✏️ Step-by-Step Solution

# 🔹 1️⃣ Find Acceleration

Divide force by mass:

$$
\vec a(t) = \frac{1}{3}(15t,\ 3t - 12,\ -6t^2)
$$

$$
\vec a(t) = (5t,\ t - 4,\ -2t^2)
$$

---

# 🔹 2️⃣ Find Velocity

Integrate each component:

---

## x-component

$$
v_x(t) = 2 + \int_0^t 5\tau \, d\tau
$$

$$
v_x(t) = 2 + \frac{5}{2}t^2
$$

---

## y-component

$$
v_y(t) = 0 + \int_0^t (\tau - 4)\, d\tau
$$

$$
v_y(t) = \frac{1}{2}t^2 - 4t
$$

---

## z-component

$$
v_z(t) = 1 + \int_0^t (-2\tau^2)\, d\tau
$$

$$
v_z(t) = 1 - \frac{2}{3}t^3
$$

---

## ✅ Final velocity

$$
\vec v(t) =
\left(
2 + \frac{5}{2}t^2,\ 
\frac{1}{2}t^2 - 4t,\ 
1 - \frac{2}{3}t^3
\right)
$$

---

# 🔹 3️⃣ Find Position

Integrate velocity:

---

## x-component

$$
x(t) = 5 + \int_0^t \left(2 + \frac{5}{2}\tau^2\right)d\tau
$$

$$
x(t) = 5 + 2t + \frac{5}{6}t^3
$$

---

## y-component

$$
y(t) = 2 + \int_0^t \left(\frac{1}{2}\tau^2 - 4\tau\right)d\tau
$$

$$
y(t) = 2 + \frac{1}{6}t^3 - 2t^2
$$

---

## z-component

$$
z(t) = -3 + \int_0^t \left(1 - \frac{2}{3}\tau^3\right)d\tau
$$

$$
z(t) = -3 + t - \frac{1}{6}t^4
$$

---

## ✅ Final position

$$
\vec r(t) =
\left(
5 + 2t + \frac{5}{6}t^3,\ 
2 + \frac{1}{6}t^3 - 2t^2,\ 
-3 + t - \frac{1}{6}t^4
\right)
$$

---

# ✅ Final Results

## Velocity

$$
\vec v(t) =
\left(
2 + \frac{5}{2}t^2,\ 
\frac{1}{2}t^2 - 4t,\ 
1 - \frac{2}{3}t^3
\right)
$$

---

## Position

$$
\vec r(t) =
\left(
5 + 2t + \frac{5}{6}t^3,\ 
2 + \frac{1}{6}t^3 - 2t^2,\ 
-3 + t - \frac{1}{6}t^4
\right)
$$

---
