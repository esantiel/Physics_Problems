# 📘 Work of a Variable Force – Hooke’s Law

We are given a one-dimensional force:

$$
F(x) = -kx
$$

This is the **restoring force of a spring** (Hooke’s Law).

We will:
1. Solve the equation of motion  
2. Compute the work done  
3. Interpret it as potential energy  
4. Verify $(F = -\frac{dU}{dx})$  
5. Describe the graphs  

---

# 🧠 Theory

## Hooke’s Law

$$
F(x) = -kx
$$

- Force is proportional to displacement  
- Negative sign → force acts **toward equilibrium**

---

## Newton’s Second Law

$$
F = m\ddot{x}
$$

So:

$$
m\ddot{x} = -kx
$$

---

## Work by Variable Force

$$
W = \int F(x)\,dx
$$

---

## Potential Energy

For conservative forces:

$$
F = -\frac{dU}{dx}
$$

---

# ✏️ Step-by-Step Solution

# 🔹 1. Equation of Motion

From Newton’s law:

$$
m\ddot{x} = -kx
$$

Rearrange:

$$
\ddot{x} + \frac{k}{m}x = 0
$$

---

## Solution of the differential equation

This is **simple harmonic motion (SHM)**:

$$
x(t) = A\cos(\omega t) + B\sin(\omega t)
$$

Where:

$$
\omega = \sqrt{\frac{k}{m}}
$$

---

# 🔹 2. Work Done from \(0\) to \(x_0\)

$$
W = \int_0^{x_0} (-kx)\,dx
$$

Factor out constant:

$$
W = -k \int_0^{x_0} x\,dx
$$

Integrate:

$$
W = -k \left[\frac{x^2}{2}\right]_0^{x_0}
$$

$$
W = -\frac{1}{2}k x_0^2
$$

---

# 🔹 3. Interpretation as Potential Energy

We define potential energy such that:

$$
U(x) = \frac{1}{2}kx^2
$$

Then:

$$
W = -\Delta U
$$

👉 The work done by the spring **reduces potential energy**.

---

# 🔹 4. Verify $(F = -\frac{dU}{dx})$

Start with:

$$
U(x) = \frac{1}{2}kx^2
$$

Differentiate:

$$
\frac{dU}{dx} = kx
$$

So:

$$
F = -\frac{dU}{dx} = -kx
$$

✅ Verified.

---

# 🔹 5. Graphs

## Force $(F(x))$

$$
F(x) = -kx
$$

- Straight line through origin  
- Negative slope  
- Opposes displacement  

---

## Potential Energy $(U(x))$

$$
U(x) = \frac{1}{2}kx^2
$$

- Parabola opening upward  
- Minimum at $(x = 0)$  

---

# ✅ Final Results

- Equation of motion:
$$
\ddot{x} + \frac{k}{m}x = 0
$$

- Solution:

$$
x(t) = A\cos(\omega t) + B\sin(\omega t)
$$

- Work:

$$
W = -\frac{1}{2}k x_0^2
$$

- Potential energy:

$$
U(x) = \frac{1}{2}kx^2
$$

- Verified:

$$
F = -\frac{dU}{dx}
$$

---