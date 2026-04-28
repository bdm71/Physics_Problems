# 🌊 Standing Wave Problem – Step-by-Step Solution

Two waves are described by:

y₁(x,t) = A sin(kx − ωt)

y₂(x,t) = A sin(kx + ωt)

We need to determine:

a) The equation of the resulting **standing wave**  
b) The positions of the **nodes**

---

# 📘 Step 1: Add the Two Waves

The total displacement is:

y(x,t) = y₁(x,t) + y₂(x,t)

Substitute the given equations:

y(x,t) = A sin(kx − ωt) + A sin(kx + ωt)

Factor out A:

y(x,t) = A [sin(kx − ωt) + sin(kx + ωt)]

---

# 📘 Step 2: Use Trigonometric Identity

Use the identity:

sin(α − β) + sin(α + β) = 2 sin(α) cos(β)

Let:

- α = kx  
- β = ωt

Then:

sin(kx − ωt) + sin(kx + ωt) = 2 sin(kx) cos(ωt)

So:

y(x,t) = 2A sin(kx) cos(ωt)

---

# ✅ Resulting Standing Wave Equation

y(x,t) = 2A sin(kx) cos(ωt)

### ✔ Final Answer:

**Standing wave equation:**

y(x,t) = 2A sin(kx) cos(ωt)

---

# 📘 Step 3: Find the Nodes

Nodes are points that **never move**, meaning displacement is always zero.

From:

y(x,t) = 2A sin(kx) cos(ωt)

For all time, this happens when:

sin(kx) = 0

---

# 📘 Step 4: Solve for x

We know:

sin(kx) = 0

This occurs when:

kx = nπ

where:

n = 0, 1, 2, 3, ...

Now solve for x:

x = nπ / k

---

# ✅ Positions of the Nodes

x = nπ / k

where n = 0, 1, 2, 3, ...

### ✔ Final Answer:

**Node positions:**

x = 0, π/k, 2π/k, 3π/k, ...

---

# 📘 Step 5: If Using Wavelength

Since:

k = 2π / λ

Substitute:

x = nπ / (2π/λ)

Simplify:

x = nλ / 2

---

# ✅ Nodes in Terms of Wavelength

x = nλ / 2

where n = 0, 1, 2, 3, ...

So nodes occur every **half wavelength**.

---

# 📌 Final Answers Summary

| Quantity | Result |
|--------|--------|
| Standing wave equation | y(x,t) = 2A sin(kx) cos(ωt) |
| Node condition | sin(kx) = 0 |
| Nodes (wave number form) | x = nπ/k |
| Nodes (wavelength form) | x = nλ/2 |

---

# 🧠 Extra Note

- **Nodes** = points that never move  
- **Antinodes** = points with maximum vibration  

Antinodes occur halfway between nodes.

---
