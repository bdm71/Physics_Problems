# 📐 Vector Motion Problem — Time Dependent Force

## 📘 Problem

A particle of mass:

```
m = 3 kg
```

moves under a time-dependent force:

$$
\mathbf{F}(t) = (15t,\; 3t - 12,\; -6t^2)
$$

Initial conditions:

$$
\mathbf{r}_0 = (5, 2, -3)
$$

$$
\mathbf{v}_0 = (2, 0, 1)
$$

Find:

1. Velocity as a function of time  
2. Position as a function of time  

---

# 🧠 Step 1 — Use Newton’s Second Law

Newton's law:

$$
\mathbf{F} = m\mathbf{a}
$$

So acceleration:

$$
\mathbf{a}(t) = \frac{\mathbf{F}(t)}{m}
$$

---

# ⚡ Step 2 — Find Acceleration

Divide each component by mass (3 kg):

$$
\mathbf{a}(t) = \left(\frac{15t}{3},\; \frac{3t - 12}{3},\; \frac{-6t^2}{3}\right)
$$

Simplify:

$$
\mathbf{a}(t) = (5t,\; t - 4,\; -2t^2)
$$

---

# 🚀 Step 3 — Find Velocity

Velocity is integral of acceleration:

$$
\mathbf{v}(t) = \int \mathbf{a}(t)\,dt
$$

Integrate each component:

---

### x-component

$$
v_x = \int 5t\,dt = \frac{5}{2}t^2 + C_1
$$

---

### y-component

$$
v_y = \int (t - 4)\,dt = \frac{t^2}{2} - 4t + C_2
$$

---

### z-component

$$
v_z = \int (-2t^2)\,dt = -\frac{2}{3}t^3 + C_3
$$

---

# 🧩 Step 4 — Apply Initial Velocity

Given:

$$
\mathbf{v}(0) = (2, 0, 1)
$$

Substitute \( t = 0 \):

---

### x:

$$
2 = 0 + C_1 \Rightarrow C_1 = 2
$$

---

### y:

$$
0 = 0 + C_2 \Rightarrow C_2 = 0
$$

---

### z:

$$
1 = 0 + C_3 \Rightarrow C_3 = 1
$$

---

# ✅ Velocity Function

$$
\mathbf{v}(t) =
\left(
\frac{5}{2}t^2 + 2,\;
\frac{t^2}{2} - 4t,\;
-\frac{2}{3}t^3 + 1
\right)
$$

---

# 📍 Step 5 — Find Position

Position is integral of velocity:

$$
\mathbf{r}(t) = \int \mathbf{v}(t)\,dt
$$

---

### x-component

$$
x(t) = \int \left(\frac{5}{2}t^2 + 2\right) dt
$$

$$
x(t) = \frac{5}{6}t^3 + 2t + C_4
$$

---

### y-component

$$
y(t) = \int \left(\frac{t^2}{2} - 4t\right) dt
$$

$$
y(t) = \frac{1}{6}t^3 - 2t^2 + C_5
$$

---

### z-component

$$
z(t) = \int \left(-\frac{2}{3}t^3 + 1\right) dt
$$

$$
z(t) = -\frac{1}{6}t^4 + t + C_6
$$

---

# 🧩 Step 6 — Apply Initial Position

Given:

$$
\mathbf{r}(0) = (5, 2, -3)
$$

---

### x:

$$
5 = 0 + C_4 \Rightarrow C_4 = 5
$$

---

### y:

$$
2 = 0 + C_5 \Rightarrow C_5 = 2
$$

---

### z:

$$
-3 = 0 + C_6 \Rightarrow C_6 = -3
$$

---

# 🏁 Final Position Function

$$
\mathbf{r}(t) =
\left(
\frac{5}{6}t^3 + 2t + 5,\;
\frac{1}{6}t^3 - 2t^2 + 2,\;
-\frac{1}{6}t^4 + t - 3
\right)
$$

---

# 📦 Final Answers

## Velocity

$$
\mathbf{v}(t) =
\left(
\frac{5}{2}t^2 + 2,\;
\frac{t^2}{2} - 4t,\;
-\frac{2}{3}t^3 + 1
\right)
$$

---

## Position

$$
\mathbf{r}(t) =
\left(
\frac{5}{6}t^3 + 2t + 5,\;
\frac{1}{6}t^3 - 2t^2 + 2,\;
-\frac{1}{6}t^4 + t - 3
\right)
$$

---

# 🎓 Key Idea (Very Important)

```
Force → Acceleration → Velocity → Position
```

Step-by-step:

1. Divide by mass → acceleration  
2. Integrate → velocity  
3. Integrate again → position  
4. Use initial conditions  

---

# 💡 How To Improve (GitHub Ideas)

### Add 3D trajectory plot
Visualize motion in space

### Add animation
Particle moving along path

### Add component graphs
Plot:

- x(t)
- y(t)
- z(t)

### Add velocity vectors
Show direction changing over time

### Add Python version

```python
import sympy as sp

t = sp.symbols('t')

ax = 5*t
ay = t - 4
az = -2*t**2

vx = sp.integrate(ax, t) + 2
vy = sp.integrate(ay, t)
vz = sp.integrate(az, t) + 1

rx = sp.integrate(vx, t) + 5
ry = sp.integrate(vy, t) + 2
rz = sp.integrate(vz, t) - 3
```
