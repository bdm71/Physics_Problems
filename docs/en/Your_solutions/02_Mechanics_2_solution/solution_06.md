# 🎬 Particle Dynamics — Visualization + Full Solution

## 📘 Problem

In a certain force field, the motion of a particle with mass:

```
m = 0.5 kg
```

is given by:

$$
x = 5t^2 - t,\quad y = 2t^3,\quad z = -3t + 2
$$

Find the time dependence of:

- Velocity  
- Momentum  
- Acceleration  
- Force  
- Power  

---

# 🧠 Step 1 — Position Vector

We write motion in vector form:

$$
\mathbf{r}(t) = (5t^2 - t,\; 2t^3,\; -3t + 2)
$$

👉 This fully describes the motion.

---

# 🚀 Step 2 — Velocity

Velocity is the derivative of position:

$$
\mathbf{v}(t) = \frac{d\mathbf{r}}{dt}
$$

Differentiate each component:

$$
\mathbf{v}(t) = (10t - 1,\; 6t^2,\; -3)
$$

---

# ⚡ Step 3 — Acceleration

Acceleration is the derivative of velocity:

$$
\mathbf{a}(t) = \frac{d\mathbf{v}}{dt}
$$

$$
\mathbf{a}(t) = (10,\; 12t,\; 0)
$$

---

# 🔥 Step 4 — Momentum

Momentum formula:

$$
\mathbf{p} = m\mathbf{v}
$$

$$
\mathbf{p}(t) = 0.5(10t - 1,\; 6t^2,\; -3)
$$

$$
\mathbf{p}(t) = (5t - 0.5,\; 3t^2,\; -1.5)
$$

---

# ⚡ Step 5 — Force

Using Newton’s second law:

$$
\mathbf{F} = m\mathbf{a}
$$

$$
\mathbf{F}(t) = 0.5(10,\; 12t,\; 0)
$$

$$
\mathbf{F}(t) = (5,\; 6t,\; 0)
$$

---

# ⚡ Step 6 — Power

Power is:

$$
P = \mathbf{F} \cdot \mathbf{v}
$$

Substitute:

$$
P = (5,\; 6t,\; 0)\cdot(10t - 1,\; 6t^2,\; -3)
$$

$$
P = 50t - 5 + 36t^3
$$

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

# 🎬 Visualization (HTML)

This project also includes an animation that shows:

- 🟡 Particle motion  
- 🔵 Trajectory  
- 🔴 Velocity vector  
- 🟢 Force vector  
- 📊 Speed and power  

---

# 🎮 How the Visualization Works

## Time update

```js
t += 0.02
```

👉 moves simulation forward

---

## Position update

```js
pos(t)
```

👉 recalculates particle position

---

## Trail (trajectory)

```js
trail.push(pos(t))
```

👉 shows path over time

---

## Projection (3D → 2D)

```js
x: 400 + p.x * scale
y: 250 - p.y * scale
```

👉 converts math into screen coordinates

---

# 🎯 What You Should Notice

### 1. Motion is curved

```
because of t² and t³ terms
```

---

### 2. Velocity changes direction

```
not constant → vector rotates
```

---

### 3. Force only affects x and y

```
Fz = 0 → no acceleration in z
```

---

### 4. Power changes over time

```
depends on F · v
```

---

# 🧩 Visual Meaning

| Element | Meaning |
|--------|--------|
| Yellow dot | particle |
| Blue line | trajectory |
| Red arrow | velocity |
| Green arrow | force |

---

# 🚀 How to Run

1. Save HTML file:

```
particle-dynamics.html
```

2. Open in browser  

3. Click **Play**

---

# 💡 How To Improve (GitHub Ideas)

### Add real 3D (Three.js)
Rotate camera

---

### Add graphs

```
x(t), y(t), z(t)
```

---

### Add energy

$$
KE = \frac12 mv^2
$$

---

### Add step-by-step mode
Pause and analyze motion

---

### Add sliders

- mass  
- force  
- initial conditions  

---

# 🏁 Final Insight

```
Position → Velocity → Acceleration → Force → Power
```

👉 This project lets you **SEE physics in motion** 🔥
