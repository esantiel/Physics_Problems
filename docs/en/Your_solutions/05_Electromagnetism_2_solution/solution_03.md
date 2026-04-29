# 3. Biot-Savart Law

A small segment of a wire has length:

$$
\Delta l = 0.1 \ \text{m}
$$

The current through the wire is:

$$
I = 3 \ \text{A}
$$

The distance from the wire segment to point $P$ is:

$$
r = 0.2 \ \text{m}
$$

The wire segment is perpendicular to the line connecting it to point $P$.

We need to calculate the magnetic field at point $P$.

---

## Biot-Savart Law

For a small current element, the magnetic field is given by:

$$
\Delta B =
\frac{\mu_0}{4\pi}
\frac{I \Delta l \sin\theta}{r^2}
$$

where:

- $\Delta B$ is the magnetic field due to the small wire segment
- $\mu_0 = 4\pi \times 10^{-7} \ \text{T m/A}$
- $I$ is the current
- $\Delta l$ is the length of the wire segment
- $r$ is the distance to the point
- $\theta$ is the angle between the wire segment and the line to point $P$

---

## Angle Information

The segment is perpendicular to the line connecting it to point $P$.

Therefore:

$$
\theta = 90^\circ
$$

and:

$$
\sin 90^\circ = 1
$$

So the formula becomes:

$$
\Delta B =
\frac{\mu_0}{4\pi}
\frac{I \Delta l}{r^2}
$$

---

## Substitute the Values

Since:

$$
\frac{\mu_0}{4\pi} = 10^{-7} \ \text{T m/A}
$$

we get:

$$
\Delta B =
(10^{-7})
\frac{(3)(0.1)}{(0.2)^2}
$$

Calculate the denominator:

$$
(0.2)^2 = 0.04
$$

Calculate the numerator:

$$
(3)(0.1)=0.3
$$

So:

$$
\Delta B =
(10^{-7})\frac{0.3}{0.04}
$$

$$
\Delta B =
(10^{-7})(7.5)
$$

$$
\Delta B =
7.5 \times 10^{-7} \ \text{T}
$$

---

# Final Answer

The magnetic field at point $P$ is:

$$
\boxed{
\Delta B = 7.5 \times 10^{-7} \ \text{T}
}
$$

or:

$$
\boxed{
\Delta B = 0.75 \ \mu\text{T}
}
$$

---

## Direction

The direction of the magnetic field is found using the **right-hand rule**:

- Point your thumb in the direction of the current.
- Point your fingers toward point $P$ from the current segment.
- The magnetic field direction is perpendicular to both.

So the magnetic field is either **into the page** or **out of the page**, depending on the direction of the current.