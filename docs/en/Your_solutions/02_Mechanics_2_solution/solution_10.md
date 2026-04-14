# 📐 Full Dynamics Problem — Position to Power

## 📘 Problem

Given motion of a particle:

$$
x = 5t^2 - t
$$

$$
y = 2t^3
$$

$$
z = -3t + 2
$$

Mass:

```
m = 0.5 kg
```

Find:

- Velocity  
- Momentum  
- Acceleration  
- Force  
- Power  

---

# 🧠 Step 1 — Position Vector

Write motion in vector form:

$$
\mathbf{r}(t) = (5t^2 - t,\; 2t^3,\; -3t + 2)
$$

---

# 🚀 Step 2 — Velocity (First Derivative)

Velocity = derivative of position:

$$
\mathbf{v}(t) = \frac{d\mathbf{r}}{dt}
$$

Differentiate each component:

---

### x-component

$$
v_x = \frac{d}{dt}(5t^2 - t) = 10t - 1
$$

---

### y-component

$$
v_y = \frac{d}{dt}(2t^3) = 6t^2
$$

---

### z-component

$$
v_z = \frac{d}{dt}(-3t + 2) = -3
$$

---

# ✅ Velocity

$$
\mathbf{v}(t) = (10t - 1,\; 6t^2,\; -3)
$$

---

# ⚡ Step 3 — Acceleration (Second Derivative)

Acceleration = derivative of velocity:

$$
\mathbf{a}(t) = \frac{d\mathbf{v}}{dt}
$$

---

### x:

$$
a_x = 10
$$

---

### y:

$$
a_y = 12t
$$

---

### z:

$$
a_z = 0
$$

---

# ✅ Acceleration

$$
\mathbf{a}(t) = (10,\; 12t,\; 0)
$$

---

# 🔥 Step 4 — Momentum

Momentum formula:

$$
\mathbf{p} = m\mathbf{v}
$$

Mass:

```
m = 0.5
```

Multiply velocity:

$$
\mathbf{p}(t) = 0.5(10t - 1,\; 6t^2,\; -3)
$$

---

# ✅ Momentum

$$
\mathbf{p}(t) = (5t - 0.5,\; 3t^2,\; -1.5)
$$

---

# ⚡ Step 5 — Force

Newton’s second law:

$$
\mathbf{F} = m\mathbf{a}
$$

$$
\mathbf{F}(t) = 0.5(10,\; 12t,\; 0)
$$

---

# ✅ Force

$$
\mathbf{F}(t) = (5,\; 6t,\; 0)
$$

---

# ⚡ Step 6 — Power

Power formula:

$$
P = \mathbf{F} \cdot \mathbf{v}
$$

(dot product)

---

Substitute:

$$
P = (5,\; 6t,\; 0) \cdot (10t - 1,\; 6t^2,\; -3)
$$

---

Multiply components:

$$
P = 5(10t - 1) + 6t(6t^2) + 0(-3)
$$

$$
P = 50t - 5 + 36t^3
$$

---

# ✅ Power

$$
P(t) = 36t^3 + 50t - 5
$$

---

# 🏁 Final Answers

## Velocity

$$
(10t - 1,\; 6t^2,\; -3)
$$

---

## Acceleration

$$
(10,\; 12t,\; 0)
$$

---

## Momentum

$$
(5t - 0.5,\; 3t^2,\; -1.5)
$$

---

## Force

$$
(5,\; 6t,\; 0)
$$

---

## Power

$$
P(t) = 36t^3 + 50t - 5
$$

---

# 🎓 Key Idea

```
Position → Velocity → Acceleration → Force → Power
```

Chain:

1. Differentiate → velocity  
2. Differentiate → acceleration  
3. Multiply by mass → force  
4. Dot product (F · v) → power  

---

# 💡 How To Improve (GitHub Ideas)

### Add 3D trajectory plot
Show motion in space

### Add vector arrows
Velocity and force directions

### Add animation
Moving particle

### Add graphs
Plot:

- velocity vs time  
- acceleration vs time  
- power vs time  

### Add Python code

```python
import sympy as sp

t = sp.symbols('t')

vx = 10*t - 1
vy = 6*t**2
vz = -3

ax = sp.diff(vx,t)
ay = sp.diff(vy,t)

F = [0.5*ax, 0.5*ay, 0]

P = F[0]*vx + F[1]*vy
```
