## 8. Waves

We want to check which functions satisfy the wave equation:

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2}\frac{\partial^2 y}{\partial t^2}
$$

A standard result is that **any function of** $(x \pm vt)$ describes a traveling wave.

So functions of the form:

$$
y(x,t) = f(x-vt)
\quad \text{or} \quad
y(x,t) = f(x+vt)
$$

can represent traveling waves.

---

### a) 

$$
y(x,t) = A\cos(kx^2-\omega t)
$$

This is **not** a function of $(x-vt)$ or $(x+vt)$ because the argument contains:

$$
x^2
$$

instead of just $x$.

So this does **not** have the standard traveling-wave form.

$$
\text{a) Not a traveling wave}
$$

---

### b)

$$
y(x,t) = A(x-vt)^2
$$

This is clearly a function of:

$$
(x-vt)
$$

So it has the correct traveling-wave form:

$$
y(x,t) = f(x-vt)
$$

Therefore it **does** describe a traveling wave.

$$
\text{b) Traveling wave}
$$

---

### c)

$$
y(x,t) = A\log(x+vt)
$$

This is clearly a function of:

$$
(x+vt)
$$

So it also has the correct traveling-wave form:

$$
y(x,t) = f(x+vt)
$$

Therefore it **does** describe a traveling wave.

$$
\text{c) Traveling wave}
$$

---

## Final Answer

The functions that can describe a traveling wave are:

$$
\boxed{b) \; y(x,t)=A(x-vt)^2}
$$

and

$$
\boxed{c) \; y(x,t)=A\log(x+vt)}
$$

while

$$
\boxed{a) \; y(x,t)=A\cos(kx^2-\omega t)}
$$

does **not** describe a traveling wave.