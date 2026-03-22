# 📘 Optimization Problem – Maximum Area Rectangle under a Curve

We are asked to **find the rectangle of maximum area** under the curve:
$$
y = 3 - x^2
$$
in the **first quadrant**.

---

## 🧠 Theory

To solve **optimization problems** using calculus:

1. Express the **quantity to optimize** (here, area) as a function of a single variable.
2. Take the **derivative**.
3. Find **critical points** by solving \(f'(x) = 0\).
4. Use the **second derivative test** or reasoning to identify maxima/minima.

---

## ✏️ Step-by-Step Solution

### 🔹 Step 1: Express the area as a function of \(x\)

Let the rectangle have:
- Width = \(x\) (from the y-axis to the rectangle in the first quadrant)
- Height = \(y = 3 - x^2\) (from the curve)

Then the area \(A\) is:

$$
A(x) = \text{width} \times \text{height} = x \cdot (3 - x^2)
$$

Simplify:

$$
A(x) = 3x - x^3
$$

---

### 🔹 Step 2: Take the derivative of \(A(x)\)

$$
A'(x) = \frac{d}{dx}(3x - x^3) = 3 - 3x^2
$$

---

### 🔹 Step 3: Find critical points

Set derivative equal to zero:

$$
3 - 3x^2 = 0
$$

$$
3x^2 = 3 \quad \Rightarrow \quad x^2 = 1
$$

$$
x = 1 \quad (\text{only positive in first quadrant})
$$

---

### 🔹 Step 4: Determine maximum using second derivative

$$
A''(x) = \frac{d}{dx}(3 - 3x^2) = -6x
$$

At \(x = 1\):

$$
A''(1) = -6 < 0
$$

✅ Negative second derivative → **maximum area**.

---

### 🔹 Step 5: Find corresponding height

$$
y = 3 - x^2 = 3 - 1^2 = 2
$$

---

## ✅ Final Answer

- Width: \(x = 1\)  
- Height: \(y = 2\)  

**Maximum area:** 

$$
A_\text{max} = x \cdot y = 1 \cdot 2 = 2
$$

