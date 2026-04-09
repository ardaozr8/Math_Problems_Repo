# Task 1 — Solution

## Given:

| x_i | -2 | 2 | 4 |
|-----|----|---|---|
| p_i | 0.5 | 0.3 | 0.2 |

---

## 1. Expected value E(X)

E(X) = (-2)(0.5) + (2)(0.3) + (4)(0.2)  
E(X) = -1 + 0.6 + 0.8 = **0.4**

---

## 2. Variance D^2(X)

First compute:

E(X^2) = (-2)^2(0.5) + (2)^2(0.3) + (4)^2(0.2)  
E(X^2) = 4(0.5) + 4(0.3) + 16(0.2)  
E(X^2) = 2 + 1.2 + 3.2 = **6.4**

Now:

D^2(X) = E(X^2) - (E(X))^2  
D^2(X) = 6.4 - (0.4)^2  
D^2(X) = 6.4 - 0.16 = **6.24**

---

## 3. Standard deviation σ

σ = √6.24 ≈ **2.50**

---

## 4. Median x₀.₅

Cumulative probabilities:

- P(X ≤ -2) = 0.5  
- P(X ≤ 2) = 0.8  
- P(X ≤ 4) = 1.0  

Median is the smallest value where cumulative ≥ 0.5:

**Median = -2**
