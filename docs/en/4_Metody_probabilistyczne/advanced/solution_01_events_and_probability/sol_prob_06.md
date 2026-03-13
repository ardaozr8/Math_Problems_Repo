## Task 6

Two automated machines produce identical products.  
The production ratio between the machines is:

M₁ : M₂ = 3 : 2

So the probabilities that a randomly selected product comes from each machine are:

P(M₁) = 3/5  
P(M₂) = 2/5  

The probability that a product is **first-grade** is:

P(F | M₁) = 0.65  
P(F | M₂) = 0.85  

---

### 1. Probability that a randomly selected product is first-grade

Using the **total probability formula**:

**P(F) = P(M₁)·P(F | M₁) + P(M₂)·P(F | M₂)**

Substitute the values:

P(F) = (3/5)(0.65) + (2/5)(0.85)

P(F) = 0.39 + 0.34

**P(F) = 0.73**

So the probability that a randomly selected product is **first-grade** is:

**P(F) = 0.73**

---

### 2. Probability that a first-grade product came from machine 1

Using **Bayes' theorem**:

**P(M₁ | F) = [P(M₁) · P(F | M₁)] / P(F)**

Substitute the values:

P(M₁ | F) = (3/5 × 0.65) / 0.73

P(M₁ | F) = 0.39 / 0.73

**P(M₁ | F) ≈ 0.534**

---

## Final Results

1. **P(first-grade product) = 0.73**  
2. **P(product came from machine 1 | first-grade) ≈ 0.534**
