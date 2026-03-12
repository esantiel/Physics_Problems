# 7. Elimination of time and interpretation of acceleration

We are asked:

> The path equation is given in parametric form:
>
> $$
> x(t) = 2t^2, \qquad y(t) = 3t^3
> $$
>
> Tasks:
> 1. Eliminate the parameter $t$.
> 2. Draw the trajectory.
> 3. Calculate $\vec v(t)$, $|\vec v(t)|$, $\vec a(t)$ and $|\vec a(t)|$.
> 4. Determine whether the acceleration is constant.

---

## 📚 Theory

1. **Parametric equations**

A trajectory in 2D is often given as:

$$
x = x(t), \quad y = y(t)
$$

- To get the **trajectory in Cartesian form** $y = f(x)$, we can **eliminate $t$**.

2. **Velocity and speed**

The velocity vector is:

$$
\vec v(t) = \frac{d\vec r}{dt} = \frac{dx}{dt} \hat{i} + \frac{dy}{dt} \hat{j}
$$

- Magnitude (speed) is:

$$
|\vec v(t)| = \sqrt{\left(\frac{dx}{dt}\right)^2 + \left(\frac{dy}{dt}\right)^2}
$$

3. **Acceleration and magnitude**

The acceleration vector is:

$$
\vec a(t) = \frac{d\vec v}{dt} = \frac{d^2 x}{dt^2} \hat{i} + \frac{d^2 y}{dt^2} \hat{j}
$$

- Magnitude:

$$
|\vec a(t)| = \sqrt{\left(\frac{d^2 x}{dt^2}\right)^2 + \left(\frac{d^2 y}{dt^2}\right)^2}
$$

- If $\vec a(t)$ depends on $t$, acceleration is **not constant**; otherwise, it is constant.

---

## 📝 Given

$$
x(t) = 2t^2, \quad y(t) = 3t^3
$$

We will find:

1. Cartesian form $y(x)$
2. Trajectory plot
3. $\vec v(t)$, $|\vec v(t)|$, $\vec a(t)$, $|\vec a(t)|$
4. Determine whether acceleration is constant

---

## Step 1: Eliminate the parameter $t$

From $x(t) = 2t^2$, solve for $t$:

$$
t^2 = \frac{x}{2} \implies t = \sqrt{\frac{x}{2}}
$$

Substitute into $y(t) = 3t^3$:

$$
y = 3 \left( \sqrt{\frac{x}{2}} \right)^3 = 3 \cdot \frac{x^{3/2}}{2^{3/2}} = \frac{3}{2\sqrt{2}} x^{3/2}
$$

✅ Cartesian trajectory:

$$
\boxed{y = \frac{3}{2\sqrt{2}} x^{3/2}}
$$

---

## Step 2: Draw the trajectory

- The trajectory is **curved**, starting from $(0,0)$, increasing in $x$ and $y$.
- It's of the form $y \sim x^{3/2}$, so it grows **faster than linear**.
- In GitHub Markdown, we can describe the plot or add an image externally.

Example ASCII sketch:

The trajectory starts at the origin $(0,0)$ and grows as $y \sim x^{3/2}$. Here is an ASCII illustration of the curve:


---

## Step 3: Velocity vector $\vec v(t)$

Velocity is the derivative of position:

$$
\vec v(t) = \frac{dx}{dt} \hat{i} + \frac{dy}{dt} \hat{j}
$$

- $dx/dt = d(2t^2)/dt = 4t$  
- $dy/dt = d(3t^3)/dt = 9t^2$

So:

$$
\vec v(t) = 4t \hat{i} + 9t^2 \hat{j}
$$

---

### Speed (magnitude of velocity)

$$
|\vec v(t)| = \sqrt{(4t)^2 + (9t^2)^2} = \sqrt{16 t^2 + 81 t^4} = t \sqrt{16 + 81 t^2}
$$

✅ Magnitude:

$$
|\vec v(t)| = t \sqrt{16 + 81 t^2}
$$

---

## Step 4: Acceleration vector $\vec a(t)$

Acceleration is derivative of velocity:

$$
\vec a(t) = \frac{d\vec v}{dt} = \frac{d^2 x}{dt^2} \hat{i} + \frac{d^2 y}{dt^2} \hat{j}
$$

- $d^2 x/dt^2 = d(4t)/dt = 4$  
- $d^2 y/dt^2 = d(9t^2)/dt = 18t$

So:

$$
\vec a(t) = 4 \hat{i} + 18t \hat{j}
$$

---

### Magnitude of acceleration

$$
|\vec a(t)| = \sqrt{4^2 + (18t)^2} = \sqrt{16 + 324 t^2}
$$

---

## Step 5: Is acceleration constant?

- Acceleration vector: $\vec a(t) = 4 \hat{i} + 18t \hat{j}$  
- Magnitude: $|\vec a(t)| = \sqrt{16 + 324 t^2}$  

✅ Since both $\vec a(t)$ and $|\vec a(t)|$ **depend on $t$**, acceleration is **not constant**.

---

## ✅ Step 6: Summary

| Quantity             | Expression                               |
|---------------------|------------------------------------------|
| Trajectory $y(x)$    | $y = \frac{3}{2\sqrt{2}} x^{3/2}$       |
| Velocity $\vec v(t)$ | $\vec v(t) = 4t \hat{i} + 9t^2 \hat{j}$ |
| Speed |$\vec v(t)$|  | $|\vec v(t)| = t \sqrt{16 + 81 t^2}$    |
| Acceleration $\vec a(t)$ | $\vec a(t) = 4 \hat{i} + 18t \hat{j}$ |
| Acceleration |$\vec a(t)$| | $|\vec a(t)| = \sqrt{16 + 324 t^2}$ |
| Constant acceleration? | ❌ No                                  |