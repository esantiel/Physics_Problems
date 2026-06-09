# 10. Wavefunction Probability

Ground-state wavefunction:

$$
\Psi(x)=
\sqrt{\frac{2}{L}}
\sin\left(\frac{\pi x}{L}\right)
$$

Probability density:

$$
|\Psi(x)|^2=
\frac{2}{L}
\sin^2\left(\frac{\pi x}{L}\right)
$$

---

## Region 1

$$
0\le x\le\frac{L}{4}
$$

Probability:

$$
P_1=
\int_0^{L/4}
\frac{2}{L}
\sin^2
\left(
\frac{\pi x}{L}
\right)
dx
$$

Evaluating:

$$
P_1
=
\frac14-\frac1{2\pi}
$$

$$
P_1\approx0.091
$$

---

## Region 2

$$
\frac{L}{4}
\le x\le
\frac{L}{2}
$$

Probability:

$$
P_2=
\int_{L/4}^{L/2}
\frac{2}{L}
\sin^2
\left(
\frac{\pi x}{L}
\right)
dx
$$

Evaluating:

$$
P_2
=
\frac14+\frac1{2\pi}
$$

$$
P_2\approx0.409
$$

---

## Comparison

$$
P_2>P_1
$$

The particle is much more likely to be found closer to the center of the box.

## Final Answer

$$
\boxed{P_1\approx0.091}
$$

$$
\boxed{P_2\approx0.409}
$$

More likely region:

$$
\boxed{\frac{L}{4}\le x\le\frac{L}{2}}
$$