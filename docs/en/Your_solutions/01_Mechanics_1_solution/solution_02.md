# 2. Range Optimization in Projectile Motion

## Problem Statement

For projectile motion without air resistance, the range is

$$
R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}
$$

Show analytically that the maximum range occurs at:

$$
\theta = 45^\circ
$$

---

# 1️⃣ Basic Theory

## Projectile Range Formula

For a projectile launched from ground level:

- Initial speed: $$v_0$$
- Launch angle: $$\theta$$
- Gravity: $$g$$

The horizontal range is:

$$
R = \frac{v_0^2 \sin(2\theta)}{g}
$$

---

## Why Optimization is Needed

The range formula is:

$$
R(\theta) = \frac{v_0^2}{g} \sin(2\theta)
$$

For a **fixed initial velocity** and constant gravity is a constant value. $$v_0$$  $$g$$

$$
\frac{v_0^2}{g}
$$

Therefore, the only quantity that depends on the launch angle is: $\theta$

$$
\sin(2\theta)
$$

Hence, maximizing the range $$R(\theta)$$ is equivalent to maximizing:

$$
\sin(2\theta)
$$

---

# 2️⃣ Analytical Optimization Using Calculus

We treat range as a function of: 

$$\theta$$

$$
R(\theta) = \frac{v_0^2}{g} \sin(2\theta)
$$

Since: $$\frac{v_0^2}{g}$$ 

is constant, define:

$$
C = \frac{v_0^2}{g}
$$

So:

$$
R(\theta) = C \sin(2\theta)
$$

---

## Step 1: Take Derivative

Differentiate with respect to: $\theta$

$$
\frac{dR}{d\theta} = C \cdot \frac{d}{d\theta}[\sin(2\theta)]
$$

Using chain rule:

$$
\frac{d}{d\theta}[\sin(2\theta)] = 2\cos(2\theta)
$$

Thus:

$$
\frac{dR}{d\theta} = 2C \cos(2\theta)
$$

---

## Step 2: Find Critical Points

Set derivative equal to zero:

$$
2C \cos(2\theta) = 0
$$

Since $$2C \neq 0$$

 we must have:

$$
\cos(2\theta) = 0
$$

---

## Step 3: Solve Trigonometric Equation

We know:

$$
\cos(x) = 0 \quad \text{when} \quad x = 90^\circ, 270^\circ, \dots
$$

So:

$$
2\theta = 90^\circ
$$

Therefore:

$$
\theta = 45^\circ
$$

---

# 3️⃣ Confirm It Is a Maximum

Take the second derivative:

$$
\frac{d^2R}{d\theta^2} = 2C \cdot (-2\sin(2\theta))
$$

$$
= -4C \sin(2\theta)
$$

Evaluate at: 

$$
\theta = 45^\circ
$$


$$
\sin(90^\circ) = 1
$$

Thus:

$$
\frac{d^2R}{d\theta^2} = -4C
$$

Since: $$C > 0$$

$$
\frac{d^2R}{d\theta^2} < 0
$$

Therefore, the critical point is a **maximum**.

---

# 4️⃣ Alternative (Pure Trigonometric Argument)

We know mathematically:

$$
\sin(x) \leq 1
$$

Maximum occurs when:

$$
\sin(x) = 1
$$

So:

$$
\sin(2\theta) = 1
$$

This occurs when:

$$
2\theta = 90^\circ
$$

Thus:

$$
\theta = 45^\circ
$$

---

# ✅ Final Result

The maximum range occurs when:

$$
\boxed{\theta = 45^\circ}
$$

The maximum possible range is:

$$
R_{\text{max}} = \frac{v_0^2}{g}
$$

---

# 🎯 Key Insight

- Range depends on $$\sin(2\theta)$$
- Sine reaches maximum value of 1
- Therefore the optimal launch angle is $$45^\circ$$
- Complementary angles (e.g., 30° and 60°) produce the same range

---

