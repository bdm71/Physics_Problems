# 🚀 Problem 1 – Projectile Motion

## 📌 Problem Statement

A projectile is fired from the ground with:

- Initial velocity: $100 \ \text{m/s}$
- Angle: $37^\circ$ above the horizontal  
- No air resistance  

Determine:

- Differential equations of motion  
- Time of flight  
- Maximum height  
- Range  

---

# 🧠 Step 1: Resolve Initial Velocity

We split the velocity into components:

$$
v_{0x} = v_0 \cos(\theta)
$$

$$
v_{0y} = v_0 \sin(\theta)
$$

Substitute values:

$$
v_{0x} = 100 \cos(37^\circ) \approx 80 \ \text{m/s}
$$

$$
v_{0y} = 100 \sin(37^\circ) \approx 60 \ \text{m/s}
$$

---

# 📍 Step 2: Differential Equations of Motion

## ➤ Horizontal Motion (x-direction)

No acceleration:

$$
\frac{d^2 x}{dt^2} = 0
$$

Integrate:

$$
\frac{dx}{dt} = v_{0x} = 80
$$

$$
x(t) = 80t
$$

---

## ➤ Vertical Motion (y-direction)

Gravity acts downward:

$$
\frac{d^2 y}{dt^2} = -g
$$

Take:

$$
g = 9.8 \ \text{m/s}^2
$$

Integrate:

$$
\frac{dy}{dt} = v_{0y} - gt = 60 - 9.8t
$$

$$
y(t) = 60t - \frac{1}{2}gt^2
$$

$$
y(t) = 60t - 4.9t^2
$$

---

# ⏱️ Step 3: Time of Flight

At landing:

$$
y = 0
$$

So:

$$
60t - 4.9t^2 = 0
$$

Factor:

$$
t(60 - 4.9t) = 0
$$

Non-zero solution:

$$
t = \frac{60}{4.9} \approx 12.24 \ \text{s}
$$

---

# 🏔️ Step 4: Maximum Height

At the top:

$$
v_y = 0
$$

So:

$$
60 - 9.8t = 0
$$

$$
t = \frac{60}{9.8} \approx 6.12 \ \text{s}
$$

Substitute into position:

$$
y = 60t - 4.9t^2
$$

$$
y_{\max} = 60(6.12) - 4.9(6.12)^2 \approx 183.6 \ \text{m}
$$

---

# 📏 Step 5: Range

$$
R = v_{0x} \cdot t
$$

$$
R = 80 \cdot 12.24 \approx 979 \ \text{m}
$$

---

# 🎯 Final Answers

- Time of flight: $12.24 \ \text{s}$
- Maximum height: $183.6 \ \text{m}$
- Range: $979 \ \text{m}$  

---

# ✨ Key Ideas

- Motion splits into horizontal and vertical components  
- Horizontal motion → constant velocity  
- Vertical motion → constant acceleration (gravity)  
- Use derivatives to describe motion  

---

## ✅ Final Result

- Range $\approx 979 \ \text{m}$
- Max height $\approx 183.6 \ \text{m}$
- Time $\approx 12.24 \ \text{s}$
