# 6. Field at a Point from a System of Charges

Two positive point charges are given:

$$
+q \quad \text{at point } (-a,0)
$$

$$
+2q \quad \text{at point } (a,0)
$$

We need to determine the electric field at different points.

---

## Electric Field Formula

The electric field produced by a point charge is:

$$
\vec E = k \frac{q}{r^2}\hat r
$$

or in vector form:

$$
\vec E = kq \frac{\vec r}{|\vec r|^3}
$$

where:

- $k = 9.0 \times 10^9 \ \text{N m}^2/\text{C}^2$
- $q$ is the charge
- $\vec r$ is the displacement vector from the charge to the observation point

---

# 1. General Electric Field $\vec E(x,y)$

Let the observation point be:

$$
P(x,y)
$$

---

## Field from charge $+q$ at $(-a,0)$

The displacement vector from $(-a,0)$ to $(x,y)$ is:

$$
\vec r_1 = (x+a, y)
$$

The distance is:

$$
r_1 = \sqrt{(x+a)^2 + y^2}
$$

So the electric field from $+q$ is:

$$
\vec E_1 =
kq \frac{(x+a, y)}
{\left[(x+a)^2+y^2\right]^{3/2}}
$$

---

## Field from charge $+2q$ at $(a,0)$

The displacement vector from $(a,0)$ to $(x,y)$ is:

$$
\vec r_2 = (x-a, y)
$$

The distance is:

$$
r_2 = \sqrt{(x-a)^2+y^2}
$$

So the electric field from $+2q$ is:

$$
\vec E_2 =
k(2q) \frac{(x-a, y)}
{\left[(x-a)^2+y^2\right]^{3/2}}
$$

---

## Total Electric Field

The total electric field is:

$$
\vec E(x,y) = \vec E_1 + \vec E_2
$$

Therefore:

$$
\boxed{
\vec E(x,y)
=
kq
\left[
\frac{(x+a, y)}
{\left[(x+a)^2+y^2\right]^{3/2}}
+
2
\frac{(x-a, y)}
{\left[(x-a)^2+y^2\right]^{3/2}}
\right]
}
$$

---

## Components of the Field

The $x$-component is:

$$
\boxed{
E_x =
kq
\left[
\frac{x+a}
{\left[(x+a)^2+y^2\right]^{3/2}}
+
2
\frac{x-a}
{\left[(x-a)^2+y^2\right]^{3/2}}
\right]
}
$$

The $y$-component is:

$$
\boxed{
E_y =
kq
\left[
\frac{y}
{\left[(x+a)^2+y^2\right]^{3/2}}
+
2
\frac{y}
{\left[(x-a)^2+y^2\right]^{3/2}}
\right]
}
$$

or:

$$
\boxed{
E_y =
kq y
\left[
\frac{1}
{\left[(x+a)^2+y^2\right]^{3/2}}
+
\frac{2}
{\left[(x-a)^2+y^2\right]^{3/2}}
\right]
}
$$

---

# 2. Electric Field at $(0,y)$

Now set:

$$
x = 0
$$

Then:

$$
r_1 = r_2 = \sqrt{a^2+y^2}
$$

Using the general formula:

$$
\vec E(0,y)
=
kq
\left[
\frac{(a,y)}
{(a^2+y^2)^{3/2}}
+
2
\frac{(-a,y)}
{(a^2+y^2)^{3/2}}
\right]
$$

Combine the vectors:

$$
(a,y)+2(-a,y)=(-a,3y)
$$

Therefore:

$$
\boxed{
\vec E(0,y)
=
\frac{kq}{(a^2+y^2)^{3/2}}
(-a,3y)
}
$$

So:

$$
\boxed{
E_x(0,y)
=
-\frac{kqa}{(a^2+y^2)^{3/2}}
}
$$

$$
\boxed{
E_y(0,y)
=
\frac{3kqy}{(a^2+y^2)^{3/2}}
}
$$

---

# 3. Electric Field at $(x,0)$

Now set:

$$
y = 0
$$

The point is on the $x$-axis.

Since both charges are on the $x$-axis, the electric field has only an $x$-component.

Therefore:

$$
\boxed{
E_y(x,0)=0
}
$$

The $x$-component is:

$$
\boxed{
E_x(x,0)
=
kq
\left[
\frac{x+a}{|x+a|^3}
+
2\frac{x-a}{|x-a|^3}
\right]
}
$$

So:

$$
\boxed{
\vec E(x,0)
=
kq
\left[
\frac{x+a}{|x+a|^3}
+
2\frac{x-a}{|x-a|^3}
\right]\hat i
}
$$

This formula is valid for:

$$
x \neq -a, \qquad x \neq a
$$

because the field is undefined at the positions of the charges.

---

# 4. Conditions for $E_x=0$, $E_y=0$, and $\vec E=0$

## Condition for $E_x=0$

From the general formula:

$$
E_x =
kq
\left[
\frac{x+a}
{\left[(x+a)^2+y^2\right]^{3/2}}
+
2
\frac{x-a}
{\left[(x-a)^2+y^2\right]^{3/2}}
\right]
$$

For $E_x=0$:

$$
\boxed{
\frac{x+a}
{\left[(x+a)^2+y^2\right]^{3/2}}
+
2
\frac{x-a}
{\left[(x-a)^2+y^2\right]^{3/2}}
=0
}
$$

---

## Condition for $E_y=0$

The $y$-component is:

$$
E_y =
kq y
\left[
\frac{1}
{\left[(x+a)^2+y^2\right]^{3/2}}
+
\frac{2}
{\left[(x-a)^2+y^2\right]^{3/2}}
\right]
$$

The bracket is always positive, so:

$$
E_y=0
$$

only when:

$$
\boxed{y=0}
$$

---

## Condition for Zero Field $\vec E=0$

For the total electric field to be zero:

$$
E_x=0
$$

and:

$$
E_y=0
$$

Since $E_y=0$ requires:

$$
y=0
$$

the zero field point must lie on the $x$-axis.

Between the two charges:

$$
-a < x < a
$$

The fields point in opposite directions.

For $y=0$, the condition becomes:

$$
\frac{1}{(x+a)^2}
=
\frac{2}{(a-x)^2}
$$

Taking the square root:

$$
\frac{1}{x+a}
=
\frac{\sqrt{2}}{a-x}
$$

So:

$$
a-x=\sqrt{2}(x+a)
$$

Solve for $x$:

$$
a-x=\sqrt{2}x+\sqrt{2}a
$$

$$
a-\sqrt{2}a=x+\sqrt{2}x
$$

$$
a(1-\sqrt{2})=x(1+\sqrt{2})
$$

Therefore:

$$
\boxed{
x =
a\frac{1-\sqrt{2}}{1+\sqrt{2}}
}
$$

This can also be written as:

$$
\boxed{
x = a(3-2\sqrt{2})
}
$$

Since:

$$
3-2\sqrt{2} \approx 0.1716
$$

and the point must be closer to the smaller charge, the zero field point is:

$$
\boxed{
x \approx -0.1716a
}
$$

So the zero field point is:

$$
\boxed{
(x,y)=(-0.1716a,0)
}
$$

---

# 5. Numerical Calculation

Given:

$$
a = 0.2 \ \text{m}
$$

$$
y = 0.3 \ \text{m}
$$

$$
q = 2 \ \mu\text{C} = 2 \times 10^{-6} \ \text{C}
$$

We calculate the field at:

$$
(0,y) = (0,0.3)
$$

Using:

$$
\vec E(0,y)
=
\frac{kq}{(a^2+y^2)^{3/2}}
(-a,3y)
$$

First calculate:

$$
a^2+y^2=(0.2)^2+(0.3)^2
$$

$$
a^2+y^2=0.04+0.09=0.13
$$

So:

$$
(a^2+y^2)^{3/2}
=
(0.13)^{3/2}
\approx 0.0469
$$

Now:

$$
\frac{kq}{(a^2+y^2)^{3/2}}
=
\frac{(9.0 \times 10^9)(2 \times 10^{-6})}{0.0469}
$$

$$
\frac{kq}{(a^2+y^2)^{3/2}}
\approx 3.84 \times 10^5
$$

Therefore:

$$
E_x =
(3.84 \times 10^5)(-0.2)
$$

$$
E_x \approx -7.68 \times 10^4 \ \text{N/C}
$$

and:

$$
E_y =
(3.84 \times 10^5)(3 \times 0.3)
$$

$$
E_y \approx 3.46 \times 10^5 \ \text{N/C}
$$

So:

$$
\boxed{
\vec E(0,0.3)
\approx
(-7.68 \times 10^4,\ 3.46 \times 10^5)
\ \text{N/C}
}
$$

The magnitude is:

$$
|\vec E|
=
\sqrt{E_x^2+E_y^2}
$$

$$
|\vec E|
=
\sqrt{(-7.68 \times 10^4)^2+(3.46 \times 10^5)^2}
$$

$$
\boxed{
|\vec E| \approx 3.54 \times 10^5 \ \text{N/C}
}
$$

---

# 6. Limit for $y \gg a$

For the point $(0,y)$, we have:

$$
\vec E(0,y)
=
\frac{kq}{(a^2+y^2)^{3/2}}
(-a,3y)
$$

If:

$$
y \gg a
$$

then:

$$
a^2+y^2 \approx y^2
$$

and:

$$
(a^2+y^2)^{3/2} \approx y^3
$$

So:

$$
\vec E(0,y)
\approx
\frac{kq}{y^3}(-a,3y)
$$

Therefore:

$$
\boxed{
E_x \approx -\frac{kqa}{y^3}
}
$$

and:

$$
\boxed{
E_y \approx \frac{3kq}{y^2}
}
$$

So for very large $y$:

$$
\boxed{
\vec E(0,y)
\approx
-\frac{kqa}{y^3}\hat i
+
\frac{3kq}{y^2}\hat j
}
$$

---

## Interpretation of the Limit

When $y \gg a$, the point is very far away compared with the separation of the charges.

The system behaves approximately like a single charge:

$$
q_{\text{total}} = q + 2q = 3q
$$

located near the origin.

Therefore, the dominant field is:

$$
\boxed{
E_y \approx \frac{3kq}{y^2}
}
$$

The horizontal component is much smaller:

$$
\boxed{
E_x \approx -\frac{kqa}{y^3}
}
$$

Also:

$$
\frac{|E_x|}{|E_y|}
\approx
\frac{a}{3y}
$$

Since:

$$
y \gg a
$$

we get:

$$
|E_x| \ll |E_y|
$$

So the field is almost vertical upward.