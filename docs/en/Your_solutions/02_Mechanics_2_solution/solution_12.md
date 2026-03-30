# 📘 Work & Energy with a Constant Force

We are given:

- Mass:
$$
m = 2 \ \mathrm{kg}
$$

- Force:
$$
\vec F = (6, 2)\ \mathrm{N}
$$

- Initial velocity:
$$
\vec v(0) = (1, -1)\ \mathrm{\frac{m}{s}}
$$

- Initial position:
$$
\vec r(0) = (0, 0)\ \mathrm{m}
$$

We will:
1. Find acceleration  
2. Find velocity  
3. Find position  
4. Describe trajectory  
5. Compute work at $(t=3)$  
6. Verify work-energy theorem  

---

# 🧠 Theory

## Newton’s Second Law

$$
\vec F = m \vec a
$$

So:

$$
\vec a = \frac{\vec F}{m}
$$

---

## Kinematics (constant acceleration)

- Velocity:

$$
\vec v(t) = \vec v_0 + \vec a t
$$

- Position:

$$
\vec r(t) = \vec r_0 + \vec v_0 t + \frac{1}{2}\vec a t^2
$$

---

## Work

$$
W = \vec F \cdot \vec r
$$

(dot product)

---

## Work-Energy Theorem

$$
W = \Delta K = \frac{1}{2}mv^2 - \frac{1}{2}mv_0^2
$$

---

# ✏️ Step-by-Step Solution

# 🔹 1️⃣ Acceleration

$$
\vec a = \frac{1}{2}(6,2) = (3,1)\ \mathrm{m/s^2}
$$

---

# 🔹 2️⃣ Velocity

$$
\vec v(t) = (1,-1) + (3,1)t
$$

So:

$$
\vec v(t) = (1+3t,\ -1+t)
$$

---

# 🔹 3️⃣ Position

$$
\vec r(t) = (0,0) + (1,-1)t + \frac{1}{2}(3,1)t^2
$$

$$
\vec r(t) = \left(t + \frac{3}{2}t^2,\ -t + \frac{1}{2}t^2 \right)
$$

---

# 🔹 4️⃣ Trajectory

We eliminate $(t)$:

From:

$$
x = t + \frac{3}{2}t^2
$$

$$
y = -t + \frac{1}{2}t^2
$$

👉 This represents a **parabolic trajectory** (since motion has constant acceleration).

---

# 🔹 5️⃣ Work at \(t = 3\)

## Step 1: Find position at \(t=3\)

$$
x(3) = 3 + \frac{3}{2}(9) = 3 + 13.5 = 16.5
$$

$$
y(3) = -3 + \frac{1}{2}(9) = -3 + 4.5 = 1.5
$$

So:

$$
\vec r(3) = (16.5,\ 1.5)
$$

---

## Step 2: Compute work

$$
W = \vec F \cdot \vec r
$$

$$
W = (6,2) \cdot (16.5,1.5)
$$

$$
W = 6(16.5) + 2(1.5)
$$

$$
W = 99 + 3 = 102 \ \mathrm{J}
$$

---

# 🔹 6️⃣ Work-Energy Check

## Initial kinetic energy

$$
K_0 = \frac{1}{2} \cdot 2 \cdot (1^2 + (-1)^2)
$$

$$
K_0 = 1 \cdot 2 = 2 \ \mathrm{J}
$$

---

## Final velocity at \(t=3\)

$$
\vec v(3) = (1+9,\ -1+3) = (10,2)
$$

---

## Final kinetic energy

$$
K_f = \frac{1}{2} \cdot 2 \cdot (10^2 + 2^2)
$$

$$
K_f = 1 \cdot (100 + 4) = 104 \ \mathrm{J}
$$

---

## Change in kinetic energy

$$
\Delta K = 104 - 2 = 102 \ \mathrm{J}
$$

---

# ✅ Final Results

- Acceleration:

$$
\vec a = (3,1)
$$

- Velocity:

$$
\vec v(t) = (1+3t,\ -1+t)
$$

- Position:

$$
\vec r(t) = \left(t + \frac{3}{2}t^2,\ -t + \frac{1}{2}t^2\right)
$$

- Work $(t=3)$:

$$
W = 102 \ \mathrm{J}
$$

- Work-energy theorem:
✔ Verified

---
