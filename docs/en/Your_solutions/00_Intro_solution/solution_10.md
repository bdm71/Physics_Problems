# 🐜 Problem 10 – Infinite Series

## 📌 Problem Statement

An ant starts at the origin (0,0) and moves in the following pattern:

- 1 m east  
- 1/2 m north  
- 1/3 m west  
- 1/4 m south  
- 1/5 m east  
- 1/6 m north  
- 1/7 m west  
- 1/8 m south  
- ...

This pattern continues infinitely.

👉 Determine the **final position** of the ant.

---

# 🧠 Step 1: Understand the Pattern

The movement repeats every four steps:

East → North → West → South → repeat

The distances follow the harmonic sequence:

$$
1, \frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \frac{1}{5}, \frac{1}{6}, ...
$$

---

# 📍 Step 2: Separate Horizontal and Vertical Components

We analyze x and y coordinates separately.

---

# ➤ Horizontal Movement (x-coordinate)

East = positive  
West = negative  

So the horizontal displacement is:

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \frac{1}{9} - \frac{1}{11} + ...
$$

We recognize this as:

$$
\sum_{n=0}^{\infty} (-1)^n \frac{1}{2n+1}
$$

This is the **Gregory–Leibniz series**, and it equals:

$$
\frac{\pi}{4}
$$

✅ Therefore:

$$
x = \frac{\pi}{4}
$$

---

# ➤ Vertical Movement (y-coordinate)

North = positive  
South = negative  

So the vertical displacement is:

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \frac{1}{10} - ...
$$

Factor out 1/2:

$$
y = \frac{1}{2} \left( 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + ... \right)
$$

The expression inside parentheses is:

$$
\sum_{n=1}^{\infty} (-1)^{n+1} \frac{1}{n}
$$

This is the **alternating harmonic series**, and it equals:

$$
\ln(2)
$$

So:

$$
y = \frac{1}{2} \ln(2)
$$

---

# 🎯 Final Position

$$
\boxed{
\left( \frac{\pi}{4}, \frac{1}{2}\ln(2) \right)
}
$$

---

# 🔢 Numerical Approximation

$$
\frac{\pi}{4} \approx 0.785
$$

$$
\frac{1}{2}\ln(2) \approx 0.347
$$

So the ant ends approximately at:

$$
(0.785,\; 0.347)
$$

---

# ✨ Key Ideas Used

- Splitting motion into x and y components
- Recognizing special infinite series
- Gregory–Leibniz series:
  $$
  \frac{\pi}{4}
  $$
- Alternating harmonic series:

$$
\ln(2)
$$

---

## ✅ Final Answer

The ant's final position is:

$$
\left( \frac{\pi}{4}, \frac{1}{2}\ln(2) \right)
$$