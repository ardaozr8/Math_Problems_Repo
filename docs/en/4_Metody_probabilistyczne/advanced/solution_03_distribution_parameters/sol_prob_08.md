# Task 8 — Solution

The measurement error X has a normal distribution with:

- μ = 0
- σ = 0.01

We need to calculate:

P(|X| < 0.02)

This means:

P(-0.02 < X < 0.02)

---

Now I standardize the values:

Z = (X - μ) / σ

For X = 0.02:

Z = (0.02 - 0) / 0.01 = 2

For X = -0.02:

Z = (-0.02 - 0) / 0.01 = -2

So:

P(-0.02 < X < 0.02) = P(-2 < Z < 2)

Using the standard normal distribution table:

Φ(2) ≈ 0.9772

Because of symmetry:

P(-2 < Z < 2) = 2Φ(2) - 1

P(-2 < Z < 2) = 2 · 0.9772 - 1 = 0.9544

---

## Final answer:

P(|X| < 0.02) ≈ **0.9544**
