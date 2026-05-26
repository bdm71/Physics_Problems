# 4. Mixed Circuit

Calculate the equivalent resistance for the circuit shown in the figure.

All resistors have resistance:

$$
R = 10\Omega
$$

---

# Step 1: Analyze the Circuit

The circuit has:

- **Top branch:** two resistors in series
- **Bottom branch:** one resistor in series with two parallel resistors
- Finally, one extra resistor in series on the right side

---

# Step 2: Simplify the Top Branch

Two resistors are connected in series.

For series resistors:

$$
R_{series} = R_1 + R_2
$$

Substitute values:

$$
R_{top} = 10\Omega + 10\Omega
$$

$$
R_{top} = 20\Omega
$$

✅ Top branch equivalent:

$$
\boxed{20\Omega}
$$

---

# Step 3: Simplify the Parallel Part in Bottom Branch

The two lower resistors are in parallel.

For parallel resistors:

$$
\frac{1}{R_p} =
\frac{1}{R_1} + \frac{1}{R_2}
$$

Substitute values:

$$
\frac{1}{R_p} =
\frac{1}{10} + \frac{1}{10}
$$

$$
\frac{1}{R_p} =
\frac{2}{10}
$$

$$
\frac{1}{R_p} =
\frac{1}{5}
$$

Invert both sides:

$$
R_p = 5\Omega
$$

✅ Parallel section equivalent:

$$
\boxed{5\Omega}
$$

---

# Step 4: Simplify the Entire Bottom Branch

Now add the left bottom resistor in series with the parallel section.

Series formula:

$$
R_{bottom} = 10\Omega + 5\Omega
$$

$$
R_{bottom} = 15\Omega
$$

✅ Bottom branch equivalent:

$$
\boxed{15\Omega}
$$

---

# Step 5: Combine Top and Bottom Branches

Now the circuit has:

- Top branch: \(20\Omega\)
- Bottom branch: \(15\Omega\)

These two branches are connected in parallel.

Use the parallel formula:

$$
\frac{1}{R_{main}} =
\frac{1}{20} + \frac{1}{15}
$$

Find common denominator:

$$
\frac{1}{R_{main}} =
\frac{3}{60} + \frac{4}{60}
$$

$$
\frac{1}{R_{main}} =
\frac{7}{60}
$$

Invert:

$$
R_{main} =
\frac{60}{7}\Omega
$$

Approximate value:

$$
R_{main} \approx 8.57\Omega
$$

✅ Equivalent of middle network:

$$
\boxed{\frac{60}{7}\Omega}
$$

---

# Step 6: Add Final Series Resistor

There is one more \(10\Omega\) resistor in series on the right side.

Series formula:

$$
R_{eq} =
\frac{60}{7}\Omega + 10\Omega
$$

Convert \(10\Omega\) into denominator 7:

$$
10\Omega =
\frac{70}{7}\Omega
$$

Now add:

$$
R_{eq} =
\frac{60}{7} + \frac{70}{7}
$$

$$
R_{eq} =
\frac{130}{7}\Omega
$$

Approximate value:

$$
R_{eq} \approx 18.57\Omega
$$

---

# Final Answer

$$
\boxed{
R_{eq} =
\frac{130}{7}\Omega
\approx 18.57\Omega
}
$$

---

# Summary of Simplification

| Part of Circuit | Equivalent Resistance |
|---|---|
| Top branch | $$20\Omega$$ |
| Parallel pair | $$5\Omega$$ |
| Bottom branch | $$15\Omega$$ |
| Middle parallel network | $$\frac{60}{7}\Omega$$ |
| Final total resistance | $$\frac{130}{7}\Omega$$ |

---
