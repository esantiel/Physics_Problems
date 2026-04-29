# 14. RLC Circuit

For a series RLC circuit with a voltage source $V(t)$, resistor $R$, inductor $L$, and capacitor $C$:

$$
V_L + V_R + V_C = V(t)
$$

The voltage across each element is:

$$
V_L = L\frac{dI}{dt}
$$

$$
V_R = RI
$$

$$
V_C = V_C(t)
$$

Therefore:

$$
\boxed{
L\frac{dI}{dt} + RI + V_C = V(t)
}
$$

Since:

$$
I = C\frac{dV_C}{dt}
$$

then:

$$
\frac{dI}{dt}
=
C\frac{d^2V_C}{dt^2}
$$

Substitute:

$$
LC\frac{d^2V_C}{dt^2}
+
RC\frac{dV_C}{dt}
+
V_C
=
V(t)
$$

Divide by $LC$:

$$
\boxed{
\frac{d^2V_C}{dt^2}
+
\frac{R}{L}\frac{dV_C}{dt}
+
\frac{1}{LC}V_C
=
\frac{1}{LC}V(t)
}
$$

---

## Comparison with Damped Harmonic Oscillator

The damped harmonic oscillator equation is:

$$
m\frac{d^2x}{dt^2}
+
b\frac{dx}{dt}
+
kx
=
F(t)
$$

The RLC equation in terms of charge $Q$ is:

$$
L\frac{d^2Q}{dt^2}
+
R\frac{dQ}{dt}
+
\frac{1}{C}Q
=
V(t)
$$

---

## Analogies

| Mechanical System | RLC Circuit |
|---|---|
| Displacement $x$ | Charge $Q$ |
| Velocity $\frac{dx}{dt}$ | Current $I = \frac{dQ}{dt}$ |
| Mass $m$ | Inductance $L$ |
| Damping coefficient $b$ | Resistance $R$ |
| Spring constant $k$ | $\frac{1}{C}$ |
| External force $F(t)$ | Voltage source $V(t)$ |