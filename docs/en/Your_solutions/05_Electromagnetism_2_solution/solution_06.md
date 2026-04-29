# 6. EM Wave Analysis

An electromagnetic wave has electric field component:

$$
E_y(x,t)=100\sin(10^7x-\omega t) \ \mathrm{V/m}
$$

We need to find:

1. Direction of propagation
2. Wavelength $\lambda$
3. Angular frequency $\omega$
4. Magnetic field component equation

---

## 1. Direction of Propagation

A traveling wave has the form:

$$
\sin(kx-\omega t)
$$

This represents a wave traveling in the **positive $x$-direction**.

Therefore:

$$
\boxed{\text{Direction of propagation: } +x \text{ direction}}
$$

---

## 2. Wave Number

The general wave form is:

$$
E_y(x,t)=E_0\sin(kx-\omega t)
$$

Comparing with:

$$
E_y(x,t)=100\sin(10^7x-\omega t)
$$

we get:

$$
k = 10^7 \ \mathrm{rad/m}
$$

---

## 3. Wavelength

The relationship between wave number and wavelength is:

$$
k = \frac{2\pi}{\lambda}
$$

So:

$$
\lambda = \frac{2\pi}{k}
$$

Substitute:

$$
\lambda = \frac{2\pi}{10^7}
$$

$$
\lambda \approx 6.28 \times 10^{-7} \ \mathrm{m}
$$

So:

$$
\boxed{\lambda \approx 6.28 \times 10^{-7} \ \mathrm{m}}
$$

or:

$$
\boxed{\lambda \approx 628 \ \mathrm{nm}}
$$

---

## 4. Angular Frequency

For an electromagnetic wave in vacuum:

$$
\omega = ck
$$

where:

$$
c = 3.0 \times 10^8 \ \mathrm{m/s}
$$

So:

$$
\omega = (3.0 \times 10^8)(10^7)
$$

$$
\omega = 3.0 \times 10^{15} \ \mathrm{rad/s}
$$

Therefore:

$$
\boxed{\omega = 3.0 \times 10^{15} \ \mathrm{rad/s}}
$$

---

## 5. Magnetic Field Component

For an electromagnetic wave:

$$
B_0 = \frac{E_0}{c}
$$

Here:

$$
E_0 = 100 \ \mathrm{V/m}
$$

So:

$$
B_0 = \frac{100}{3.0 \times 10^8}
$$

$$
B_0 \approx 3.33 \times 10^{-7} \ \mathrm{T}
$$

---

## Direction of Magnetic Field

The electric field is in the $y$-direction:

$$
\vec E \parallel \hat j
$$

The wave propagates in the $+x$-direction:

$$
\vec k \parallel \hat i
$$

For an electromagnetic wave:

$$
\vec E \times \vec B
$$

points in the direction of propagation.

We need:

$$
\hat j \times \vec B = \hat i
$$

Since:

$$
\hat j \times \hat k = \hat i
$$

the magnetic field must be in the $+z$-direction.

Therefore:

$$
\vec B \parallel \hat k
$$

---

## Magnetic Field Equation

The magnetic field has the same phase as the electric field:

$$
B_z(x,t)=B_0\sin(kx-\omega t)
$$

So:

$$
\boxed{
B_z(x,t)
=
3.33 \times 10^{-7}
\sin(10^7x - 3.0 \times 10^{15}t)
\ \mathrm{T}
}
$$

---

# Final Answers

Direction of propagation:

$$
\boxed{+x \text{ direction}}
$$

Wavelength:

$$
\boxed{\lambda = 6.28 \times 10^{-7} \ \mathrm{m} = 628 \ \mathrm{nm}}
$$

Angular frequency:

$$
\boxed{\omega = 3.0 \times 10^{15} \ \mathrm{rad/s}}
$$

Magnetic field component:

$$
\boxed{
B_z(x,t)
=
3.33 \times 10^{-7}
\sin(10^7x - 3.0 \times 10^{15}t)
\ \mathrm{T}
}
$$