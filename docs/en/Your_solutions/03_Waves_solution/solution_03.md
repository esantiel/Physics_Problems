## 3. Superposition Principle

Given the two waves:

$$
y_1(x,t)=A\sin(kx-\omega t)
$$

$$
y_2(x,t)=A\sin(kx+\omega t)
$$

the resulting wave is found by adding them:

$$
y(x,t)=y_1+y_2
$$

Using the trigonometric identity:

$$
\sin\alpha+\sin\beta = 2\sin\left(\frac{\alpha+\beta}{2}\right)\cos\left(\frac{\alpha-\beta}{2}\right)
$$

let

$$
\alpha = kx-\omega t,\qquad \beta = kx+\omega t
$$

Then:

$$
y(x,t)=A\sin(kx-\omega t)+A\sin(kx+\omega t)
$$

$$
y(x,t)=2A\sin(kx)\cos(\omega t)
$$

### Resulting standing wave equation

$$
\boxed{y(x,t)=2A\sin(kx)\cos(\omega t)}
$$

This is the equation of a **standing wave**.

### Positions of the nodes

Nodes are the points where the displacement is always zero, so:

$$
\sin(kx)=0
$$

This happens when:

$$
kx=n\pi
$$

where \(n=0,\pm1,\pm2,\dots\)

So the node positions are:

$$
\boxed{x=\frac{n\pi}{k}}
$$

Since

$$
k=\frac{2\pi}{\lambda}
$$

we can also write:

$$
\boxed{x=\frac{n\lambda}{2}}
$$

### Final answer

- **Standing wave equation:**

$$
\boxed{y(x,t)=2A\sin(kx)\cos(\omega t)}
$$

- **Node positions:**

$$
\boxed{x=\frac{n\pi}{k}=\frac{n\lambda}{2}}, \qquad n=0,\pm1,\pm2,\dots
$$