# 1. Projectile Motion

A projectile is fired from the ground with an initial velocity of  
$v_0 = 100 \text{ m/s}$ at an angle of $\theta = 37^\circ$ above the horizontal.

Assume:

- No air resistance
- Motion occurs under constant gravitational acceleration
- $g = 9.81 \text{ m/s}^2$

We want to:

1. Derive the **differential equations of motion**
2. Determine the **time of flight**
3. Determine the **maximum height**
4. Determine the **range**

---

# 1️⃣ Basic Theory

Projectile motion is a type of **two-dimensional motion** where an object moves under the influence of gravity.

The motion can be separated into:

- **Horizontal motion ($x$ direction)**  
- **Vertical motion ($y$ direction)**

Important assumptions:

- Horizontal acceleration = **0**
- Vertical acceleration = **$-g$**

---

# 2️⃣ Initial Velocity Components

The initial velocity $v_0$ can be split into horizontal and vertical components.

$$
v_{0x} = v_0 \cos\theta
$$

$$
v_{0y} = v_0 \sin\theta
$$

Substitute values:

$$
v_{0x} = 100\cos(37^\circ)
$$

$$
v_{0y} = 100\sin(37^\circ)
$$

Using approximations:

$$
\cos(37^\circ) \approx 0.798
$$

$$
\sin(37^\circ) \approx 0.602
$$

Therefore:

$$
v_{0x} \approx 79.8 \text{ m/s}
$$

$$
v_{0y} \approx 60.2 \text{ m/s}
$$

---

# 3️⃣ Differential Equations of Motion

## Horizontal Motion

No force acts horizontally.

From Newton's second law:

$$
F_x = m\frac{d^2x}{dt^2}
$$

Since $F_x = 0$:

$$
\frac{d^2x}{dt^2} = 0
$$

Integrating once:

$$
\frac{dx}{dt} = v_{0x}
$$

Integrating again:

$$
x(t) = v_{0x}t
$$

---

## Vertical Motion

Gravity acts downward.

$$
F_y = -mg
$$

Using Newton's second law:

$$
m\frac{d^2y}{dt^2} = -mg
$$

Cancel $m$:

$$
\frac{d^2y}{dt^2} = -g
$$

Integrating once:

$$
\frac{dy}{dt} = v_{0y} - gt
$$

Integrating again:

$$
y(t) = v_{0y}t - \frac{1}{2}gt^2
$$

---

# 4️⃣ Time of Flight

The projectile lands when $y = 0$.

$$
0 = v_{0y}t - \frac{1}{2}gt^2
$$

Factor $t$:

$$
t(v_{0y} - \frac{1}{2}gt) = 0
$$

Ignoring $t=0$:

$$
t = \frac{2v_{0y}}{g}
$$

Substitute values:

$$
t = \frac{2(60.2)}{9.81}
$$

$$
t \approx 12.28 \text{ s}
$$

---

# 5️⃣ Maximum Height

Maximum height occurs when vertical velocity becomes zero.

$$
v_y = v_{0y} - gt
$$

Set $v_y = 0$:

$$
t_{max} = \frac{v_{0y}}{g}
$$

Substitute:

$$
t_{max} = \frac{60.2}{9.81}
$$

$$
t_{max} \approx 6.14 \text{ s}
$$

Now substitute into the position equation:

$$
H = v_{0y}t_{max} - \frac{1}{2}gt_{max}^2
$$

Using the simplified formula:

$$
H = \frac{v_{0y}^2}{2g}
$$

Substitute:

$$
H = \frac{(60.2)^2}{2(9.81)}
$$

$$
H \approx 184.6 \text{ m}
$$

---

# 6️⃣ Range

The range is the horizontal distance traveled.

$$
R = v_{0x} \times t
$$

Substitute values:

$$
R = 79.8 \times 12.28
$$

$$
R \approx 980 \text{ m}
$$

---

# ✅ Final Answers

### Differential Equations

Horizontal motion:

$$
\frac{d^2x}{dt^2} = 0
$$

Vertical motion:

$$
\frac{d^2y}{dt^2} = -g
$$

---

### Time of Flight

$$
t \approx 12.28 \text{ s}
$$

---

### Maximum Height

$$
H \approx 184.6 \text{ m}
$$

---

### Range

$$
R \approx 980 \text{ m}
$$

---

# 📌 Key Insight

Projectile motion can be analyzed by separating motion into:

- **Horizontal motion (constant velocity)**
- **Vertical motion (constant acceleration)**

The trajectory of the projectile forms a **parabolic path**.