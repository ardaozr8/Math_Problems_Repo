## Task 6

A certain mechanism consists of two gears: a large one and a small one.  
Technical conditions during the assembly of the device are violated if both gears have positive thickness deviations ("plus") or if both have negative deviations ("minus").

Consider two binary random variables:

- **X = 1**, if the large gear is **"plus"**, and **X = 0** if **"minus"**
- **Y = 1**, if the small gear is **"plus"**, and **Y = 0** if **"minus"**

The probabilities are given as:

- P(X = 0, Y = 0) = 1/4
- P(X = 1, Y = 1) = 1/4
- P(X = 0, Y = 1) = 1/4
- P(X = 1, Y = 0) = 1/4

The pairs **(0,0)** and **(1,1)** correspond to **bad assembly**.  
The pairs **(0,1)** and **(1,0)** correspond to **good assembly**.

We need to:

1. determine the **joint distribution table** of the two-dimensional random variable \((X,Y)\),
2. calculate the probability that the assembly is correct.

---

## Step 1: Joint Distribution Table

Since all four possible outcomes have probability **1/4**, the joint distribution table is:

| X \ Y | 0 | 1 |
|------|---|---|
| 0 | 1/4 | 1/4 |
| 1 | 1/4 | 1/4 |

This means:

- P(X = 0, Y = 0) = 1/4
- P(X = 0, Y = 1) = 1/4
- P(X = 1, Y = 0) = 1/4
- P(X = 1, Y = 1) = 1/4

---

## Step 2: Probability of Correct Assembly

The assembly is **correct** when one gear is "plus" and the other is "minus".  
So the favorable cases are:

- (X = 0, Y = 1)
- (X = 1, Y = 0)

Therefore:

P(correct assembly) = P(X = 0, Y = 1) + P(X = 1, Y = 0)

P(correct assembly) = 1/4 + 1/4

P(correct assembly) = 2/4 = 1/2

---

## Final Results

### Joint distribution table

| X \ Y | 0 | 1 |
|------|---|---|
| 0 | 1/4 | 1/4 |
| 1 | 1/4 | 1/4 |

### Probability of correct assembly

P(correct assembly) = **1/2 = 0.5**

So the probability that the assembly is technically correct is **0.5**.
