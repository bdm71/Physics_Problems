# 🚤 River Crossing Problem — Step by Step Solution

## 📘 Problem

A river flows east at **2 m/s**.  
A boat that can travel at **5 m/s** in still water wants to go **directly north** across the river.  

The river is **200 m wide**.

Find:

1. The direction (angle) the boat should head  
2. The time needed to cross the river  

---

# 🧠 Step 1 — Understand the Situation

There are **two velocities** acting on the boat:

Boat velocity (relative to water):

```
5 m/s
```

River velocity:

```
2 m/s east
```

The boat wants to go **straight north**, so:

- East movement must cancel
- Boat must aim **west of north**

---

# 🎯 Step 2 — Resolve Boat Velocity

Let the boat head at angle **θ west of north**

Horizontal component:

$$
v_x = 5\sin\theta
$$

Vertical component:

$$
v_y = 5\cos\theta
$$

---

# 🧩 Step 3 — Cancel River Motion

River pushes east at:

$$
2 \text{ m/s}
$$

To move straight north:

$$
5\sin\theta = 2
$$

---

# 🧮 Step 4 — Solve for Angle

$$
\sin\theta = \frac{2}{5}
$$

$$
\theta = \sin^{-1}\left(\frac{2}{5}\right)
$$

$$
\theta \approx 23.58^\circ
$$

---

# ✅ Direction

The boat must head:

$$
23.6^\circ \text{ west of north}
$$

---

# 🚀 Step 5 — Northward Velocity

Only vertical motion crosses the river:

$$
v_y = 5\cos\theta
$$

Using identity:

$$
v_y = \sqrt{5^2 - 2^2}
$$

$$
v_y = \sqrt{25-4}
$$

$$
v_y = \sqrt{21}
$$

$$
v_y \approx 4.58\ \text{m/s}
$$

---

# ⏱ Step 6 — Time to Cross River

River width:

```
200 m
```

Time formula:

$$
t = \frac{distance}{speed}
$$

$$
t = \frac{200}{4.58}
$$

$$
t \approx 43.7\ \text{s}
$$

---

# 📦 Final Answers

### Direction

$$
\theta = 23.6^\circ \text{ west of north}
$$

### Crossing Time

$$
t = 43.7\ \text{s}
$$

---

# 🎓 Physics Concept Used

Relative velocity:

$$
\vec v_{ground} = \vec v_{boat} + \vec v_{river}
$$

We forced:

$$
v_{east} = 0
$$

So the boat travels straight north.

---

# 🧭 Vector Triangle (Concept)

```
        North
          ↑
          |\
          | \
          |  \ 5 m/s (boat)
          |θ  \
          |    \
          |     \
          |______\ → East
              2 m/s (river)
```

---

# 💡 Summary

Boat heading:

```
23.6° west of north
```

Time to cross:

```
43.7 seconds
```

---

# 🚀 How to Improve This Solution (for GitHub)

You can upgrade this README by adding:

### 1. Add vector diagram image
Draw triangle using SVG or PNG

### 2. Add interactive calculator
Allow changing:

- river speed  
- boat speed  
- river width  

### 3. Add Python version

```python
import math

river = 2
boat = 5
width = 200

angle = math.degrees(math.asin(river/boat))
north = math.sqrt(boat**2 - river**2)
time = width / north

print("Angle:", angle)
print("Time:", time)
```

### 4. Add animation (HTML canvas)

Show:

- river drift  
- boat direction  
- final motion  

### 5. Add general formula section

General angle:

$$
\theta = \sin^{-1}\left(\frac{v_{river}}{v_{boat}}\right)
$$

General time:

$$
t = \frac{W}{\sqrt{v_{boat}^2 - v_{river}^2}}
$$

---

# 🏁 Final Box

**Angle**

$$
23.6^\circ
$$

**Time**

$$
43.7\ \text{s}
$$
