# 3. Path Intersection

Alice moves along the path

$$
A(t) = (2+t,\; 8-3t)
$$

Bob moves along the path

$$
B(t) = (2t-1,\; 2t+2)
$$

We want to determine:

1. Whether their **paths intersect**.
2. If they collide, **when and where**.
3. If they do not collide, find the **minimum distance between them** and **when it occurs**.

---

# 1️⃣ Basic Theory

## Parametric Motion in the Plane

The motion of an object in the plane can be represented by a **vector-valued function**

$$
P(t) = (x(t), y(t))
$$

where

- $x(t)$ = horizontal position  
- $y(t)$ = vertical position  
- $t$ = time

---

## Condition for Collision

Two objects collide when **both their positions are equal at the same time**.

So we must solve

$$
A(t) = B(t)
$$

which means

$$
x_A(t) = x_B(t)
$$

and

$$
y_A(t) = y_B(t)
$$

simultaneously.

---

# 2️⃣ Write the Coordinates

Alice:

$$
A(t) = (2+t,\; 8-3t)
$$

Bob:

$$
B(t) = (2t-1,\; 2t+2)
$$

So

Alice coordinates:

$$
x_A = 2+t
$$

$$
y_A = 8-3t
$$

Bob coordinates:

$$
x_B = 2t-1
$$

$$
y_B = 2t+2
$$

---

# 3️⃣ Solve for Intersection

For a collision we require

$$
2+t = 2t-1
$$

and

$$
8-3t = 2t+2
$$

---

## Solve the First Equation

$$
2+t = 2t-1
$$

Move terms:

$$
2+1 = 2t - t
$$

$$
3 = t
$$

So from the first equation

$$
t = 3
$$

---

## Check the Second Equation

Substitute $t=3$:

$$
8 - 3(3) = 2(3) + 2
$$

Left side:

$$
8 - 9 = -1
$$

Right side:

$$
6 + 2 = 8
$$

Since

$$
-1 \ne 8
$$

the equations are **not satisfied simultaneously**.

---

# 4️⃣ Conclusion About Collision

Because there is **no single time $t$ that satisfies both equations**, Alice and Bob **do not collide**.

Their paths do **not intersect at the same time**.

---

# 5️⃣ Distance Between the Two People

The distance between two points

$$
(x_1,y_1), (x_2,y_2)
$$

is

$$
d = \sqrt{(x_1-x_2)^2 + (y_1-y_2)^2}
$$

We apply this to the positions of Alice and Bob.

---

## Difference in Coordinates

$x$ difference:

$$
(2+t) - (2t-1)
$$

$$
= 3 - t
$$

$y$ difference:

$$
(8-3t) - (2t+2)
$$

$$
= 6 - 5t
$$

---

# 6️⃣ Distance Function

The distance between Alice and Bob is

$$
d(t) =
\sqrt{(3-t)^2 + (6-5t)^2}
$$

---

# 7️⃣ Minimize the Distance

It is easier to minimize the **square of the distance**:

$$
D(t) = (3-t)^2 + (6-5t)^2
$$

---

## Expand

$$
(3-t)^2 = 9 - 6t + t^2
$$

$$
(6-5t)^2 = 36 - 60t + 25t^2
$$

Add them:

$$
D(t) = 45 - 66t + 26t^2
$$

---

# 8️⃣ Find Minimum

Take derivative:

$$
D'(t) = -66 + 52t
$$

Set equal to zero:

$$
-66 + 52t = 0
$$

$$
52t = 66
$$

$$
t = \frac{66}{52}
$$

$$
t = \frac{33}{26}
$$

---

# 9️⃣ Minimum Distance

Substitute into $D(t)$.

Compute:

$$
D_{min} = (3 - 1.269)^2 + (6 - 5(1.269))^2
$$

Approximate:

$$
D_{min} \approx 3.53
$$

Distance:

$$
d_{min} = \sqrt{3.53}
$$

$$
d_{min} \approx 1.88
$$

---

# ✅ Final Answer

**Alice and Bob do not collide.**

Minimum distance occurs at

$$
t = \frac{33}{26} \approx 1.27
$$

Minimum distance:

$$
d_{min} \approx 1.88
$$

---

# 📌 Key Idea

To determine collisions between moving objects:

1. Set their **position functions equal**.
2. Solve for **time**.
3. If no solution exists, compute the **minimum distance function**.
