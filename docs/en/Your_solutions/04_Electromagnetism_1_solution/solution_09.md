# 9. Vector Lorentz Force

A proton moves with velocity:

$$
\vec v = 2\hat i - 4\hat j + \hat k
$$

in a magnetic field:

$$
\vec B = \hat i + 2\hat j - \hat k
$$

We need to find the magnitude of the magnetic force.

---

## Magnetic Lorentz Force

The magnetic force on a moving charge is:

$$
\vec F = q(\vec v \times \vec B)
$$

The magnitude is:

$$
|\vec F| = q|\vec v \times \vec B|
$$

For a proton:

$$
q = e = 1.6 \times 10^{-19} \ \text{C}
$$

---

## Step 1: Write the Vectors

$$
\vec v = (2,-4,1)
$$

$$
\vec B = (1,2,-1)
$$

---

## Step 2: Calculate the Cross Product

$$
\vec v \times \vec B =
\begin{vmatrix}
\hat i & \hat j & \hat k \\
2 & -4 & 1 \\
1 & 2 & -1
\end{vmatrix}
$$

Now calculate each component:

$$
\vec v \times \vec B
=
\hat i[(-4)(-1)-(1)(2)]
-
\hat j[(2)(-1)-(1)(1)]
+
\hat k[(2)(2)-(-4)(1)]
$$

$$
\vec v \times \vec B
=
\hat i(4-2)
-
\hat j(-2-1)
+
\hat k(4+4)
$$

$$
\vec v \times \vec B
=
2\hat i + 3\hat j + 8\hat k
$$

So:

$$
\boxed{
\vec v \times \vec B = (2,3,8)
}
$$

---

## Step 3: Find the Magnitude of the Cross Product

$$
|\vec v \times \vec B|
=
\sqrt{2^2+3^2+8^2}
$$

$$
|\vec v \times \vec B|
=
\sqrt{4+9+64}
$$

$$
|\vec v \times \vec B|
=
\sqrt{77}
$$

$$
|\vec v \times \vec B|
\approx 8.77
$$

---

## Step 4: Calculate the Magnetic Force

$$
|\vec F| = q|\vec v \times \vec B|
$$

$$
|\vec F| =
(1.6 \times 10^{-19})(8.77)
$$

$$
|\vec F| \approx 1.40 \times 10^{-18} \ \text{N}
$$

---

# Final Answer

The magnitude of the magnetic force is:

$$
\boxed{
|\vec F| \approx 1.40 \times 10^{-18} \ \text{N}
}
$$

---

## Extra: Force Vector

The force vector itself is:

$$
\vec F =
(1.6 \times 10^{-19})(2\hat i + 3\hat j + 8\hat k)
$$

$$
\vec F =
(3.2 \times 10^{-19})\hat i
+
(4.8 \times 10^{-19})\hat j
+
(1.28 \times 10^{-18})\hat k
$$

So:

$$
\boxed{
\vec F =
(3.2 \times 10^{-19},\ 4.8 \times 10^{-19},\ 1.28 \times 10^{-18})
\ \text{N}
}
$$