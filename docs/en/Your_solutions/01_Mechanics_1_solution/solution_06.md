# 📈 Kinematics Problem — Velocity Function

## 📘 Problem

An object's velocity is given by:

$$
v(t) = t^2 + 2t - 5
$$

The object is at:

$$
x = 4 \quad \text{at} \quad t = 0
$$

Find:

1. Position at \( t = 3 \)
2. Acceleration at \( t = 3 \)

---

# 🧠 Step 1 — Recall Relationships

Velocity is derivative of position:

$$
v(t) = \frac{dx}{dt}
$$

Acceleration is derivative of velocity:

$$
a(t) = \frac{dv}{dt}
$$

So we must:

1. Integrate velocity → position  
2. Differentiate velocity → acceleration  

---

# 🚀 Step 2 — Find Position Function

Given:

$$
v(t) = t^2 + 2t - 5
$$

Since:

$$
v(t) = \frac{dx}{dt}
$$

Integrate both sides:

$$
x(t) = \int (t^2 + 2t - 5) dt
$$

Integrate term by term:

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + C
$$

---

# 🧩 Step 3 — Use Initial Condition

Given:

$$
x(0) = 4
$$

Substitute:

$$
4 = 0 + 0 - 0 + C
$$

$$
C = 4
$$

---

# ✅ Position Function

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + 4
$$

---

# 📍 Step 4 — Position at t = 3

Substitute \( t = 3 \):

$$
x(3) = \frac{3^3}{3} + 3^2 - 5(3) + 4
$$

$$
x(3) = \frac{27}{3} + 9 - 15 + 4
$$

$$
x(3) = 9 + 9 - 15 + 4
$$

$$
x(3) = 7
$$

---

# 🎯 Position Answer

$$
x(3) = 7
$$

---

# ⚡ Step 5 — Find Acceleration

Acceleration is derivative of velocity:

$$
a(t) = \frac{dv}{dt}
$$

Differentiate:

$$
v(t) = t^2 + 2t - 5
$$

$$
a(t) = 2t + 2
$$

---

# 📍 Step 6 — Acceleration at t = 3

$$
a(3) = 2(3) + 2
$$

$$
a(3) = 6 + 2
$$

$$
a(3) = 8
$$

---

# 🏁 Final Answers

### Position at t = 3

$$
x(3) = 7
$$

### Acceleration at t = 3

$$
a(3) = 8
$$

---

# 📦 Summary

Position function:

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + 4
$$

Acceleration function:

$$
a(t) = 2t + 2
$$

Final values:

```
Position at t=3  →  7
Acceleration at t=3 → 8
```

---

# 💡 How To Improve This (GitHub Ideas)

You can enhance this README by adding:

### 1. Graph of velocity
Plot:

```
v(t) = t² + 2t − 5
```

---

### 2. Graph of position
Plot:

```
x(t)
```

---

### 3. Add Python solver

```python
import sympy as sp

t = sp.symbols('t')

v = t**2 + 2*t - 5

x = sp.integrate(v, t) + 4

a = sp.diff(v, t)

print("Position:", x.subs(t,3))
print("Acceleration:", a.subs(t,3))
```

---

### 4. Add animation
Show:

- moving particle  
- velocity changing  
- acceleration arrow  

---

### 5. Add general formulas

Velocity → position:

$$
x(t) = \int v(t) dt
$$

Acceleration:

$$
a(t) = v'(t)
$$
