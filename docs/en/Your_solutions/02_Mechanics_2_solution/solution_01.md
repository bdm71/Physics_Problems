# 🕰️ Simple Pendulum Problem — Step-by-Step Solution

## 📘 Problem

A simple pendulum has a period of **4 seconds** on Earth.

1. What would its period be on the Moon, where gravity is **1/6 of Earth**?
2. What length is required for a pendulum to have a period of **1 second on Earth**?

---

# 🧠 Step 1 — Pendulum Formula

The period of a simple pendulum is:

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

Where:

- \(T\) = period  
- \(L\) = length  
- \(g\) = gravitational acceleration  

---

# 🌍 Step 2 — Earth vs Moon Relationship

On Earth:

$$
T_E = 2\pi \sqrt{\frac{L}{g_E}}
$$

On Moon:

$$
T_M = 2\pi \sqrt{\frac{L}{g_M}}
$$

Divide the equations:

$$
\frac{T_M}{T_E} = \sqrt{\frac{g_E}{g_M}}
$$

Moon gravity:

$$
g_M = \frac{g_E}{6}
$$

Substitute:

$$
\frac{T_M}{T_E} = \sqrt{\frac{g_E}{g_E/6}}
$$

$$
\frac{T_M}{T_E} = \sqrt{6}
$$

---

# 🚀 Step 3 — Period on Moon

Given:

$$
T_E = 4 \text{ s}
$$

$$
T_M = 4\sqrt{6}
$$

$$
T_M = 4(2.449)
$$

$$
T_M \approx 9.80 \text{ s}
$$

---

# ✅ Answer 1

Period on Moon:

$$
T_M \approx 9.8 \text{ seconds}
$$

---

# 📏 Step 4 — Find Length for 1 Second Period

Use:

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

Solve for \(L\):

$$
L = \frac{gT^2}{4\pi^2}
$$

---

# 🧮 Step 5 — Substitute Values

For Earth:

$$
g = 9.8 \text{ m/s}^2
$$

$$
T = 1 \text{ s}
$$

$$
L = \frac{9.8(1)^2}{4\pi^2}
$$

$$
L = \frac{9.8}{39.478}
$$

$$
L \approx 0.248 \text{ m}
$$

---

# ✅ Answer 2

Required length:

$$
L \approx 0.248 \text{ m}
$$

$$
L \approx 24.8 \text{ cm}
$$

---

# 🏁 Final Answers

### Period on Moon

$$
9.8 \text{ seconds}
$$

### Required Length for 1s Period

$$
0.248 \text{ m}
$$

---

# 🎓 Concepts Used

Pendulum period:

$$
T \propto \frac{1}{\sqrt{g}}
$$

Length formula:

$$
L = \frac{gT^2}{4\pi^2}
$$

---

# 💡 How To Improve This (GitHub Ideas)

Add:

### 1. Pendulum animation
Swinging bob visualization

### 2. Slider for gravity
Earth → Moon → Mars

### 3. Length calculator
Input desired period

### 4. Graph
Period vs length

### 5. Comparison table

| Planet | g | Period |
|--------|---|-------|
| Earth | 9.8 | 4s |
| Moon | 1.63 | 9.8s |
