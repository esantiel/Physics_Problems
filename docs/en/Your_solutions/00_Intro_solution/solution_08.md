# 📘 Definite Integrals – Area under \(f(x) = \sin(x)\)

We are asked to **calculate the area under the curve** of the function:
$$
f(x) = \sin(x)
$$
from
$$
x = 0 \quad \text{to} \quad x = \pi
$$

---

## 🧠 Theory

The **area under a curve** \(y = f(x)\) between \(x = a\) and \(x = b\) is given by the **definite integral**:

$$
\text{Area} = \int_a^b f(x) \, dx
$$

**Key rules for integration:**

1. The integral of \(\sin(x)\) is:
$$
\int \sin(x) \, dx = -\cos(x) + C
$$
2. For definite integrals:
$$
\int_a^b f(x) \, dx = F(b) - F(a)
$$
where \(F(x)\) is the antiderivative of \(f(x)\).

---

## ✏️ Step-by-Step Solution

### 🔹 Step 1: Set up the integral

$$
\text{Area} = \int_0^\pi \sin(x) \, dx
$$

---

### 🔹 Step 2: Find the antiderivative

$$
\int \sin(x) \, dx = -\cos(x)
$$

---

### 🔹 Step 3: Apply the limits

$$
\int_0^\pi \sin(x) \, dx = \Big[-\cos(x)\Big]_0^\pi
$$

This means:

$$
\text{Area} = -\cos(\pi) + \cos(0)
$$

---

### 🔹 Step 4: Evaluate the cosines

$$
\cos(\pi) = -1, \quad \cos(0) = 1
$$

So:

$$
\text{Area} = -(-1) + 1 = 1 + 1 = 2
$$

---

## ✅ Final Answer

$$
\boxed{\text{Area} = 2}
$$

