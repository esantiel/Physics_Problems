## 10. Kinematics: 3D Trajectory Analysis

This document provides a step-by-step derivation and analysis of a point $M$ moving in three-dimensional space according to a parametric vector equation.

## 1. Theory and Basic Formulas

### Position Vector
The position of a point in 3D space is defined by the vector:
$$\vec{r}(t) = x(t)\mathbf{i} + y(t)\mathbf{j} + z(t)\mathbf{k}$$

In this problem, the coordinates are:
* $x(t) = a \cos(\omega t)$
* $y(t) = b \sin(\omega t)$
* $z(t) = bt$

### Path Length (Arc Length)
The total distance $s$ traveled by a particle from time $0$ to $t_0$ is the integral of its speed over that interval:
$$s = \int_{0}^{t_0} |\vec{v}(t)| dt = \int_{0}^{t_0} \sqrt{\left(\frac{dx}{dt}\right)^2 + \left(\frac{dy}{dt}\right)^2 + \left(\frac{dz}{dt}\right)^2} dt$$

---

## 2. Step-by-Step Solution

### a) Finding the Trajectory Equation
The trajectory is the geometric path independent of time. We eliminate $t$ by relating the $x$ and $y$ coordinates:

1.  From $x = a \cos(\omega t)$, we get $\cos(\omega t) = \frac{x}{a}$.
2.  From $y = b \sin(\omega t)$, we get $\sin(\omega t) = \frac{y}{b}$.
3.  Using the identity $\cos^2(\theta) + \sin^2(\theta) = 1$:

$$\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2 = 1$$

**Conclusion:** The projection of the path onto the $xy$-plane is an **ellipse**. Because the $z$-coordinate increases linearly with time ($z = bt$), the 3D trajectory is an **Elliptical Helix**.

---

### b) Computing the Path Length
First, we find the velocity components by differentiating the position with respect to time:
* $v_x = \frac{dx}{dt} = -a\omega \sin(\omega t)$
* $v_y = \frac{dy}{dt} = b\omega \cos(\omega t)$
* $v_z = \frac{dz}{dt} = b$

Next, we find the magnitude of the velocity (speed):
$$|\vec{v}| = \sqrt{(-a\omega \sin \omega t)^2 + (b\omega \cos \omega t)^2 + b^2}$$
$$|\vec{v}| = \sqrt{a^2\omega^2 \sin^2 \omega t + b^2\omega^2 \cos^2 \omega t + b^2}$$

The path length $s$ is:
$$s = \int_{0}^{t_0} \sqrt{a^2\omega^2 \sin^2 \omega t + b^2\omega^2 \cos^2 \omega t + b^2} dt$$

> **Note:** If $a \neq b$, this is an elliptic integral. However, if $a = b$ (Circular Helix), the speed becomes constant: $|\vec{v}| = \sqrt{a^2\omega^2 + b^2}$.

---
