# ⚡ Conservation of Energy — Pendulum Speed

## 📘 Problem

A pendulum of length

```
L = 1.0 m
```

is released from an initial angle

```
θ = 15°
```

Find the **speed of the bob at the bottom** of the swing.

---

# 🧠 Step 1 — Use Conservation of Energy

We use conservation of mechanical energy:

```
Potential Energy (top) = Kinetic Energy (bottom)
```

At the top:
- velocity = 0  
- only gravitational potential energy  

At the bottom:
- height = 0  
- all energy becomes kinetic  

So:

$$
mgh = \frac12 mv^2
$$

Mass cancels out.

---

# 📐 Step 2 — Find Height Drop

We need vertical height the bob falls.

From pendulum geometry:

$$
h = L(1 - \cos\theta)
$$

This comes from:
- top position tilted at angle θ  
- bottom position vertical  
- difference gives height drop  

---

# 🧮 Step 3 — Substitute Values

Given:

```
L = 1.0 m
θ = 15°
```

$$
h = 1(1 - \cos 15^\circ)
$$

$$
\cos 15^\circ = 0.966
$$

$$
h = 1(1 - 0.966)
$$

$$
h = 0.034 \text{ m}
$$

---

# ⚡ Step 4 — Apply Energy Equation

From conservation:

$$
mgh = \frac12 mv^2
$$

Cancel mass:

$$
gh = \frac12 v^2
$$

Solve for velocity:

$$
v = \sqrt{2gh}
$$

---

# 🚀 Step 5 — Substitute Numbers

```
g = 9.8 m/s²
h = 0.034 m
```

$$
v = \sqrt{2(9.8)(0.034)}
$$

$$
v = \sqrt{0.666}
$$

$$
v = 0.816 \text{ m/s}
$$

---

# ✅ Final Answer

Speed at bottom:

$$
v \approx 0.82 \text{ m/s}
$$

---

# 🎓 Concept Used

Energy conservation:

$$
PE_{top} = KE_{bottom}
$$

Pendulum height:

$$
h = L(1-\cos\theta)
$$

Velocity:

$$
v = \sqrt{2gh}
$$

---

# 📊 Summary

| Quantity | Value |
|---------|------|
| Length | 1.0 m |
| Angle | 15° |
| Height drop | 0.034 m |
| Speed at bottom | 0.82 m/s |

---

# 💡 How To Improve This (GitHub Ideas)

### Add pendulum diagram
Show:

- initial angle  
- height drop  
- bottom velocity  

---

### Add animation
Swinging pendulum with speed increasing

---

### Add interactive inputs
Change:

- length  
- angle  
- gravity  

---

### Add energy graph
Plot:

- potential energy  
- kinetic energy  
- total energy  

---

### Add general formula

Final speed:

$$
v = \sqrt{2gL(1-\cos\theta)}
$$
