# 6. Variable Velocity

We are asked:

> An object's velocity is given by  
> $v(t) = t^2 + 2t - 5$.  
> If the object was at $x=4$ at $t=0$, what is its **position** and **acceleration** at time $t=3$?  

We will solve this **step by step**, starting from theory.

---

## 📚 Theory

1. **Velocity and Position Relationship**

   The velocity $v(t)$ is the **derivative** of the position $x(t)$ with respect to time $t$:

   $$
   v(t) = \frac{dx}{dt}
   $$

   To find the position $x(t)$, we **integrate** the velocity:

   $$
   x(t) = \int v(t) \, dt + C
   $$

   where $C$ is the constant of integration, determined by the initial condition $x(0)$.

2. **Acceleration**

   Acceleration $a(t)$ is the derivative of velocity with respect to time:

   $$
   a(t) = \frac{dv}{dt}
   $$

---

## 📝 Given

- Velocity: $v(t) = t^2 + 2t - 5$  
- Initial position: $x(0) = 4$  
- Time of interest: $t = 3$

We are asked to find:

1. Position $x(3)$  
2. Acceleration $a(3)$

---

## Step 1: Find the position function $x(t)$

$$
x(t) = \int v(t) \, dt = \int (t^2 + 2t - 5) \, dt
$$

Integrate term by term:

$$
\int t^2 dt = \frac{t^3}{3}, \quad
\int 2t dt = t^2, \quad
\int -5 dt = -5t
$$

So the general position function is:

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + C
$$

Use the initial condition $x(0) = 4$ to find $C$:

$$
x(0) = 0 + 0 - 0 + C = 4 \implies C = 4
$$

✅ Therefore:

$$
\boxed{x(t) = \frac{t^3}{3} + t^2 - 5t + 4}
$$

---

## Step 2: Find position at $t=3$

$$
x(3) = \frac{3^3}{3} + 3^2 - 5(3) + 4
$$

Step by step:

- $ \frac{3^3}{3} = 9 $  
- $ 3^2 = 9 $  
- $ -5 \cdot 3 = -15 $  
- Constant $+4$  

Add them:

$$
x(3) = 9 + 9 - 15 + 4 = 7
$$

✅ Position at $t = 3$ is:

$$
\boxed{x(3) = 7}
$$

---

## Step 3: Find acceleration $a(t)$

$$
v(t) = t^2 + 2t - 5
$$

Differentiate term by term:

$$
a(t) = \frac{dv}{dt} = 2t + 2
$$

---

## Step 4: Find acceleration at $t=3$

$$
a(3) = 2(3) + 2 = 6 + 2 = 8
$$

✅ Acceleration at $t=3$ is:

$$
\boxed{a(3) = 8}
$$

---

## ✅ Step 5: Summary

| Quantity     | Formula                                | Value at $t=3$ |
|-------------|----------------------------------------|----------------|
| Position    | $x(t) = \frac{t^3}{3} + t^2 - 5t + 4$ | $7$           |
| Velocity    | $v(t) = t^2 + 2t - 5$                 | $10$          |
| Acceleration | $a(t) = 2t + 2$                       | $8$           |

---

### ✅ Answer:

- **Position at $t=3$:** $\mathbf{7}$  
- **Acceleration at $t=3$:** $\mathbf{8}$