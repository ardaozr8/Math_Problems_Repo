## Task 5

Select constants **A** and **B** such that the function

F(x) = A + B arctan(x),  for −∞ < x < ∞

is the **cumulative distribution function (CDF)** of a certain continuous random variable **X**.  
Then determine the **probability density function (PDF)** of this variable.

---

## Step 1: Properties of a CDF

For a function to be a valid cumulative distribution function, it must satisfy:

1. lim(x → −∞) F(x) = 0  
2. lim(x → ∞) F(x) = 1  
3. F(x) must be non-decreasing

We use the limits of the arctangent function:

lim(x → −∞) arctan(x) = −π/2  
lim(x → ∞) arctan(x) = π/2

---

## Step 2: Apply the Limits

### Condition 1

lim(x → −∞) F(x) = A + B(−π/2) = 0

A − Bπ/2 = 0

---

### Condition 2

lim(x → ∞) F(x) = A + B(π/2) = 1

A + Bπ/2 = 1

---

## Step 3: Solve for A and B

We have the system:

A − Bπ/2 = 0  
A + Bπ/2 = 1

Subtract the first equation from the second:

Bπ = 1

Therefore:

B = 1/π

Substitute into the first equation:

A − (1/π)(π/2) = 0

A − 1/2 = 0

A = 1/2

---

## Step 4: Final CDF

F(x) = 1/2 + (1/π) arctan(x)

---

## Step 5: Probability Density Function

The density function is the derivative of the CDF:

f(x) = dF(x)/dx

Since

d/dx arctan(x) = 1 / (1 + x²)

we obtain:

f(x) = (1/π) · 1/(1 + x²)

---

## Final Results

Constants:

A = 1/2  
B = 1/π  

Cumulative distribution function:

F(x) = 1/2 + (1/π) arctan(x)

Probability density function:

f(x) = 1 / (π(1 + x²))

This is the **Cauchy distribution**.
