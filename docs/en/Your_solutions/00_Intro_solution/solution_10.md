# 📘 Infinite Series – Ant’s Final Position

An ant starts at the **origin** and moves according to this pattern:

1. \(1\) m east  
2. \(1/2\) m north  
3. \(1/3\) m west  
4. \(1/4\) m south  
5. \(1/5\) m east  
6. \(1/6\) m north  
… and so on.

We are asked to find its **final position**.

---

## 🧠 Theory

- The ant’s motion forms **two separate infinite series** along the x-axis (east-west) and y-axis (north-south).
- **X-axis (east-west) series**: \(+1, -1/3, +1/5, -1/7, \dots\)  
- **Y-axis (north-south) series**: \(+1/2, -1/4, +1/6, -1/8, \dots\)  

These are **alternating harmonic series**:

1. X-axis:  
$$
x_\text{total} = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots
$$
2. Y-axis:  
$$
y_\text{total} = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \dots
$$

---

## 🔹 Step 1: Recognize the series

- **X-axis series** is the **Leibniz series** for \(\pi/4\):
$$
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots = \frac{\pi}{4}
$$

- **Y-axis series** can be factored as:
$$
y_\text{total} = \frac{1}{2}\Big(1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots \Big)
$$
The term in parentheses is also an alternating harmonic series that converges to \(\ln 2\).  
So:
$$
y_\text{total} = \frac{\ln 2}{1} \cdot \frac{1}{?} 
$$

Let's carefully compute:

**Alternating harmonic series:**  
$$
1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots = \ln 2
$$  

Y-series factor:  
$$
y_\text{total} = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \dots
$$

Factor \(1/2\) out:
$$
y_\text{total} = \frac{1}{2} \left(1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots\right) = \frac{\ln 2}{2}
$$

✅ Perfect.

---

## 🔹 Step 2: Final position

- **X-coordinate**:  
$$
x_\text{final} = \frac{\pi}{4} \approx 0.785 \, \text{m}
$$

- **Y-coordinate**:  
$$
y_\text{final} = \frac{\ln 2}{2} \approx 0.347 \, \text{m}
$$

---

## ✅ Final Answer

$$
\boxed{(x, y) \approx (0.785, 0.347) \, \text{meters}}
$$

