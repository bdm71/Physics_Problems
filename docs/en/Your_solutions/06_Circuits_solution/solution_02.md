# Equivalent Resistances Using Three 1Ω Resistors

We have exactly three resistors:

$$
R = 1\Omega
$$

We need to find all possible unique equivalent resistances.

---

# 1) All Resistors in Series

For series connection:

$$
R_{eq} = R_1 + R_2 + R_3
$$

Since all resistors are \(1\Omega\):

$$
R_{eq} = 1\Omega + 1\Omega + 1\Omega
$$

$$
R_{eq} = 3\Omega
$$

✅ Final Answer:

$$
\boxed{3\Omega}
$$

---

# 2) All Resistors in Parallel

For parallel connection:

$$
\frac{1}{R_{eq}} =
\frac{1}{R_1} +
\frac{1}{R_2} +
\frac{1}{R_3}
$$

Substitute values:

$$
\frac{1}{R_{eq}} =
\frac{1}{1\Omega} +
\frac{1}{1\Omega} +
\frac{1}{1\Omega}
$$

$$
\frac{1}{R_{eq}} = 1 + 1 + 1
$$

$$
\frac{1}{R_{eq}} = 3
$$

Invert both sides:

$$
R_{eq} = \frac{1}{3}\Omega
$$

✅ Final Answer:

$$
\boxed{\frac{1}{3}\Omega}
$$

---

# 3) Two Resistors in Series, Then Parallel with the Third

## Step 1: Combine Two Resistors in Series

$$
R_s = 1\Omega + 1\Omega
$$

$$
R_s = 2\Omega
$$

---

## Step 2: Put This in Parallel with Third Resistor

$$
\frac{1}{R_{eq}} =
\frac{1}{2\Omega} +
\frac{1}{1\Omega}
$$

$$
\frac{1}{R_{eq}} =
\frac{1}{2} + 1
$$

Convert to common denominator:

$$
\frac{1}{R_{eq}} =
\frac{1}{2} + \frac{2}{2}
$$

$$
\frac{1}{R_{eq}} =
\frac{3}{2}
$$

Invert:

$$
R_{eq} = \frac{2}{3}\Omega
$$

✅ Final Answer:

$$
\boxed{\frac{2}{3}\Omega}
$$

---

# 4) Two Resistors in Parallel, Then Series with the Third

## Step 1: Combine Two Resistors in Parallel

$$
\frac{1}{R_p} =
\frac{1}{1\Omega} +
\frac{1}{1\Omega}
$$

$$
\frac{1}{R_p} = 1 + 1
$$

$$
\frac{1}{R_p} = 2
$$

Invert:

$$
R_p = \frac{1}{2}\Omega
$$

---

## Step 2: Add Third Resistor in Series

$$
R_{eq} =
\frac{1}{2}\Omega + 1\Omega
$$

$$
R_{eq} =
\frac{1}{2}\Omega + \frac{2}{2}\Omega
$$

$$
R_{eq} =
\frac{3}{2}\Omega
$$

✅ Final Answer:

$$
\boxed{\frac{3}{2}\Omega}
$$

---

# Final List of All Unique Equivalent Resistances

$$
\boxed{
\frac{1}{3}\Omega,\;
\frac{2}{3}\Omega,\;
\frac{3}{2}\Omega,\;
3\Omega
}
$$

---

# Summary Table

| Configuration | Equivalent Resistance |
|---|---|
| All in parallel | \( \frac{1}{3}\Omega \) |
| Two in series, then parallel with third | \( \frac{2}{3}\Omega \) |
| Two in parallel, then series with third | \( \frac{3}{2}\Omega \) |
| All in series | \( 3\Omega \) |
