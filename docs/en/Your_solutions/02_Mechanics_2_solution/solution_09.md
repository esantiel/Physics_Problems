# 📘 Vertical Throw with Linear Drag

We are given the equation:

$$
m\frac{dv}{dt} = -mg - kv
$$

with initial conditions:

$$
v(0) = v_0, \quad x(0) = 10
$$

We will:
1. Solve the equation analytically  
2. Find the maximum height  
3. Compare with the no-drag case  

---

# 🧠 Theory

## Linear Drag Force

The force is:

$$
F = -mg - kv
$$

- Gravity: constant downward force  
- Drag: proportional to velocity  

---

## Standard Form

Divide by \(m\):

$$
\frac{dv}{dt} = -g - \frac{k}{m}v
$$

Define:

$$
\gamma = \frac{k}{m}
$$

Then:

$$
\frac{dv}{dt} + \gamma v = -g
$$

This is a **first-order linear differential equation**.

---

# ✏️ 1️⃣ Solve for Velocity \(v(t)\)

## 🔹 Step 1: Solve homogeneous equation

$$
\frac{dv}{dt} + \gamma v = 0
$$

Solution:

$$
v_h = Ce^{-\gamma t}
$$

---

## 🔹 Step 2: Find particular solution

Assume constant:

$$
v_p = A
$$

Substitute:

$$
\gamma A = -g \Rightarrow A = -\frac{g}{\gamma}
$$

---

## 🔹 Step 3: General solution

$$
v(t) = Ce^{-\gamma t} - \frac{g}{\gamma}
$$

---

## 🔹 Step 4: Apply initial condition

$$
v(0) = v_0 = C - \frac{g}{\gamma}
$$

So:

$$
C = v_0 + \frac{g}{\gamma}
$$

---

## ✅ Final velocity

$$
v(t) = \left(v_0 + \frac{g}{\gamma}\right)e^{-\gamma t} - \frac{g}{\gamma}
$$

---

# ✏️ 2️⃣ Position Function \(x(t)\)

Integrate velocity:

$$
x(t) = \int v(t)\,dt
$$

Result:

$$
x(t) = 10 + \frac{1}{\gamma}\left(v_0 + \frac{g}{\gamma}\right)(1 - e^{-\gamma t}) - \frac{g}{\gamma}t
$$

---

# ✏️ 3️⃣ Maximum Height

Maximum height occurs when:

$$
v(t) = 0
$$

---

## 🔹 Step 1: Set velocity to zero

$$
\left(v_0 + \frac{g}{\gamma}\right)e^{-\gamma t} - \frac{g}{\gamma} = 0
$$

---

## 🔹 Step 2: Solve for time

$$
e^{-\gamma t} = \frac{g}{\gamma v_0 + g}
$$

Take logarithm:

$$
t_{\text{max}} = \frac{1}{\gamma} \ln\left(\frac{\gamma v_0 + g}{g}\right)
$$

---

## 🔹 Step 3: Substitute into position

Maximum height:

$$
x_{\text{max}} = x(t_{\text{max}})
$$

(Use the position formula above)

---

# ✏️ 4️⃣ Comparison: No Drag Case

Without air resistance:

$$
\frac{dv}{dt} = -g
$$

---

## Velocity

$$
v(t) = v_0 - gt
$$

---

## Maximum height

Occurs when $(v = 0)$:

$$
t = \frac{v_0}{g}
$$

Height:

$$
h = \frac{v_0^2}{2g}
$$

---

# 🔍 Comparison Summary

| Case | Behavior |
|------|--------|
| With drag | Exponential decay, slower ascent |
| Without drag | Linear velocity decrease |
| Max height | Smaller with drag |
| Symmetry | Broken with drag |

---

# ✅ Final Results

- Velocity:
$$
v(t) = \left(v_0 + \frac{g}{\gamma}\right)e^{-\gamma t} - \frac{g}{\gamma}
$$

- Time to max height:
$$
t_{\text{max}} = \frac{1}{\gamma} \ln\left(\frac{\gamma v_0 + g}{g}\right)
$$

- Height: obtained from $(x(t))$

---

# 🎯 Key Insights

- Drag introduces **exponential behavior**
- Motion is no longer symmetric
- Maximum height is reduced
- Terminal velocity appears for long time