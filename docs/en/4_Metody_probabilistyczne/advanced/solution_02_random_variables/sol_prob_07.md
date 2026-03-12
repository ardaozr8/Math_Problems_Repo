## Task 7

The two-dimensional random variable **(X,Y)** has the following joint distribution:

| Y \ X | 1 | 2 | 3 |
|------|---|---|---|
| 2 | 0.1 | 0.2 | 0.3 |
| 4 | 0.1 | 0.1 | 0.2 |

Determine the **cumulative distribution function (CDF)** of the **marginal distribution of Y**.

---

## Step 1: Find the Marginal Distribution of Y

To obtain the marginal distribution of **Y**, sum the probabilities across each row (over all values of **X**).

### For Y = 2

P(Y = 2) = 0.1 + 0.2 + 0.3  
P(Y = 2) = 0.6

### For Y = 4

P(Y = 4) = 0.1 + 0.1 + 0.2  
P(Y = 4) = 0.4

So the marginal distribution of **Y** is:

| Y | P(Y) |
|---|---|
| 2 | 0.6 |
| 4 | 0.4 |

---

## Step 2: Determine the Cumulative Distribution Function

The cumulative distribution function is defined as:

F_Y(y) = P(Y ≤ y)

### Case 1: y < 2

F_Y(y) = 0

---

### Case 2: 2 ≤ y < 4

F_Y(y) = P(Y = 2)  
F_Y(y) = 0.6

---

### Case 3: y ≥ 4

F_Y(y) = P(Y = 2) + P(Y = 4)  
F_Y(y) = 0.6 + 0.4 = 1

---

## Final Result

The **CDF of Y** is:

F_Y(y) = 0, for y < 2  
F_Y(y) = 0.6, for 2 ≤ y < 4  
F_Y(y) = 1, for y ≥ 4
