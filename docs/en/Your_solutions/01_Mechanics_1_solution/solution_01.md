# Projectile Motion – Step-by-Step Solution

## Problem Statement

A projectile is fired from the ground with:

- Initial velocity: $$v_0 = 100 \text{ m/s}$$
- Launch angle: $$\theta = 37^\circ$$
- No air resistance
- Gravity: $$g = 9.81 \text{ m/s}^2$$

We will:

1. Derive the differential equations of motion.
2. Determine the time of flight.
3. Determine the maximum height.
4. Determine the range.

---

# 1️⃣ Basic Theory

## Assumptions

- Motion in two dimensions: horizontal ($$x$$) and vertical ($$y$$)
- No air resistance
- Only force acting is gravity
- Gravity is constant and downward

---

## Newton’s Second Law

$$
\vec{F} = m \vec{a}
$$

Only force acting:

- Horizontal direction: no force
- Vertical direction: $$F_y = -mg$$

---

# 2️⃣ Differential Equations of Motion

---

## Horizontal Direction

Since no horizontal force acts:

$$
F_x = 0
$$

Using Newton’s second law:

$$
m \frac{d^2 x}{dt^2} = 0
$$

Canceling $$m$$:

$$
\frac{d^2 x}{dt^2} = 0
$$

### First Integration

$$
\frac{dx}{dt} = v_x = C_1
$$

Using the initial condition:

$$
v_x = v_0 \cos\theta
$$

### Second Integration

Assuming $$x(0)=0$$:

$$
x(t) = v_0 \cos\theta \, t
$$

---

## Vertical Direction

Gravity acts downward:

$$
F_y = -mg
$$

Newton’s second law:

$$
m \frac{d^2 y}{dt^2} = -mg
$$

Canceling $$m$$:

$$
\frac{d^2 y}{dt^2} = -g
$$

### First Integration

$$
\frac{dy}{dt} = v_y = -gt + C_2
$$

Using initial condition:

$$
v_y(0) = v_0 \sin\theta
$$

So:

$$
v_y = v_0 \sin\theta - gt
$$

### Second Integration

Assuming $$y(0)=0$$:

$$
y(t) = v_0 \sin\theta \, t - \frac{1}{2} g t^2
$$

---

# 3️⃣ Time of Flight

The projectile lands when:

$$
y(t) = 0
$$

So:

$$
v_0 \sin\theta \, t - \frac{1}{2} g t^2 = 0
$$

Factor:

$$
t \left( v_0 \sin\theta - \frac{1}{2} g t \right) = 0
$$

Ignoring $$t=0$$:

$$
t = \frac{2 v_0 \sin\theta}{g}
$$

---

### Substitute Values

$$
t = \frac{2(100)\sin(37^\circ)}{9.81}
$$

Using:

$$
\sin(37^\circ) \approx 0.601
$$

$$
t = \frac{120.2}{9.81}
$$

$$
t \approx 12.25 \text{ s}
$$

---

# 4️⃣ Maximum Height

Maximum height occurs when:

$$
v_y = 0
$$

From:

$$
v_y = v_0 \sin\theta - gt
$$

Set equal to zero:

$$
t_{max} = \frac{v_0 \sin\theta}{g}
$$

---

### Height Formula

Using position equation:

$$
H = v_0 \sin\theta \, t_{max} - \frac{1}{2} g t_{max}^2
$$

This simplifies to:

$$
H = \frac{(v_0 \sin\theta)^2}{2g}
$$

---

### Substitute Values

$$
H = \frac{(100 \times 0.601)^2}{2(9.81)}
$$

$$
H = \frac{3612}{19.62}
$$

$$
H \approx 184.1 \text{ m}
$$

---

# 5️⃣ Range

Range formula:

$$
R = \frac{v_0^2 \sin(2\theta)}{g}
$$

---

### Substitute Values

$$
R = \frac{100^2 \sin(74^\circ)}{9.81}
$$

Using:

$$
\sin(74^\circ) \approx 0.961
$$

$$
R = \frac{9610}{9.81}
$$

$$
R \approx 979.6 \text{ m}
$$

---

# ✅ Final Answers

- Differential equations:

$$
\frac{d^2 x}{dt^2} = 0
$$

$$
\frac{d^2 y}{dt^2} = -g
$$

- Time of flight:

$$
12.25 \text{ s}
$$

- Maximum height:

$$
184.1 \text{ m}
$$

- Range:

$$
979.6 \text{ m}
$$

---

# 🎯 Summary

- Horizontal motion: constant velocity  
- Vertical motion: uniformly accelerated motion  
- Trajectory: parabolic  
- Motion is symmetric (time up = time down)

---

If you'd like, I can also provide a fully LaTeX (.tex) version ready for Overleaf.