## Task 4

In many situations (e.g., in computer science and electronics), it can be assumed that the time **X** of failure-free operation of a tested device is a continuous random variable with the density:

f(x) = (1/λ) e^(-x/λ)  for x > 0  
f(x) = 0  for x ≤ 0

This is the **exponential distribution**.  
Let the parameter **λ = 10** (e.g., hours).

We need to:

1. Calculate the probability that the device will operate without failure from **5 to 10 hours**, i.e. **P(5 ≤ X ≤ 10)**.
2. Determine the **cumulative distribution function (CDF)**.

---

## Step 1: Probability Density Function

For the exponential distribution:

f(x) = (1/λ) e^(-x/λ),  for x > 0

Given:

λ = 10

Therefore:

f(x) = (1/10) e^(-x/10)

---

## Step 2: Cumulative Distribution Function (CDF)

The CDF of the exponential distribution is:

F(x) = 1 − e^(-x/λ),  for x ≥ 0

Substituting λ = 10:

F(x) = 1 − e^(-x/10)

and

F(x) = 0  for x < 0

---

## Step 3: Calculate P(5 ≤ X ≤ 10)

Using the CDF:

P(a ≤ X ≤ b) = F(b) − F(a)

So:

P(5 ≤ X ≤ 10) = F(10) − F(5)

Compute each value.

### F(10)

F(10) = 1 − e^(-10/10)  
F(10) = 1 − e^(-1)

### F(5)

F(5) = 1 − e^(-5/10)  
F(5) = 1 − e^(-0.5)

---

## Step 4: Final Probability

P(5 ≤ X ≤ 10) = (1 − e^-1) − (1 − e^-0.5)

P(5 ≤ X ≤ 10) = e^-0.5 − e^-1

Numerical values:

e^-0.5 ≈ 0.60653  
e^-1 ≈ 0.36788

Therefore:

P(5 ≤ X ≤ 10) ≈ 0.60653 − 0.36788

P(5 ≤ X ≤ 10) ≈ **0.23865**

---

## Final Results

**CDF:**

F(x) = 1 − e^(-x/10),  for x ≥ 0

**Probability:**

P(5 ≤ X ≤ 10) ≈ **0.23865**
