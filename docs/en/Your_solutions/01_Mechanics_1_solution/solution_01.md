# Solutions goes here
# 🚀 Problem 1 – Projectile Motion

## 📌 Problem Statement

A projectile is fired from the ground with:

- Initial velocity: 100 m/s  
- Angle: 37° above horizontal  
- No air resistance  

Find:

1. Differential equations of motion  
2. Time of flight  
3. Maximum height  
4. Range  

---

# 🧠 Step 1: Resolve Initial Velocity

We split the velocity into components:

$$

v_{0x} = v_0 \cos\theta

$$

$$

v_{0y} = v_0 \sin\theta

$$

Substitute values:

$$

v_{0x} = 100 \cos(37^\circ) \approx 100 \cdot 0.8 = 80 \text{ m/s}

$$

$$

v_{0y} = 100 \sin(37^\circ) \approx 100 \cdot 0.6 = 60 \text{ m/s}

$$

---

# 📍 Step 2: Differential Equations of Motion

## ➤ Horizontal motion (x-direction)

No acceleration (no air resistance):

$$

\frac{d^2 x}{dt^2} = 0

$$

Integrate once:

$$

\frac{dx}{dt} = v_{0x} = 80

$$

Integrate again:

$$

x(t) = 80t

$$

---

## ➤ Vertical motion (y-direction)

Gravity acts downward:

$$

\frac{d^2 y}{dt^2} = -g

$$

Take:

$$

g = 9.8 \text{ m/s}^2

$$

Integrate once:

$$

\frac{dy}{dt} = v_{0y} - gt = 60 - 9.8t

$$

Integrate again:

$$

y(t) = 60t - \frac{1}{2}gt^2

$$

$$

y(t) = 60t - 4.9t^2

$$

---

# ⏱️ Step 3: Time of Flight

The projectile lands when:

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

t = \frac{60}{4.9}

$$

$$

t \approx 12.24 \text{ s}

$$

---

# 🏔️ Step 4: Maximum Height

At maximum height:

$$

v_y = 0

$$

So:

$$

60 - 9.8t = 0

$$

$$

t = \frac{60}{9.8} \approx 6.12 \text{ s}

$$

Now substitute into position:

$$

y = 60t - 4.9t^2

$$

$$

y_{\max} = 60(6.12) - 4.9(6.12)^2

$$

$$

y_{\max} \approx 183.6 \text{ m}

$$

---

# 📏 Step 5: Range

Range is horizontal distance at total time:

$$

R = v_{0x} \cdot t

$$

$$

R = 80 \cdot 12.24

$$

$$

R \approx 979 \text{ m}

$$

---

# 🎯 Final Answers

- Time of flight:

$$

12.24 \text{ s}

$$

- Maximum height:

$$

183.6 \text{ m}

$$

- Range:

$$

979 \text{ m}

$$

---

# ✨ Key Ideas

- Motion splits into independent x and y components  
- Horizontal motion → constant velocity  
- Vertical motion → constant acceleration (gravity)  
- Use derivatives to describe motion  
