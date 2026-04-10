# Task 2 — Hypergeometric Model (Sampling from a Batch)

## 1. Description of the random experiment
The random experiment consists of selecting **4 components** at random from a batch of **20 components** without replacement.  
Among the 20 components, **5 are defective** and **15 are functional**.  
After the selection, we count how many defective components are in the sample.

## 2. Definition of the random variable
Let **X** be the number of defective components in the sample of 4 selected components.

## 3. Possible values of X
Since 4 components are selected, the number of defective components can be:

**X ∈ {0, 1, 2, 3, 4}**

The value 4 is possible because there are 5 defective components in total.

## 4. Probability distribution
The random variable **X** follows a **hypergeometric distribution** with parameters:

- Population size: **N = 20**
- Number of defective components: **K = 5**
- Sample size: **n = 4**

The probability formula is:

**P(X = x) = [C(5, x) × C(15, 4 - x)] / C(20, 4)**, for **x = 0, 1, 2, 3, 4**

Now we calculate each probability:

### P(X = 0)
P(X = 0) = [C(5,0) × C(15,4)] / C(20,4)  
= (1 × 1365) / 4845  
= 1365 / 4845  
≈ **0.2817**

### P(X = 1)
P(X = 1) = [C(5,1) × C(15,3)] / C(20,4)  
= (5 × 455) / 4845  
= 2275 / 4845  
≈ **0.4696**

### P(X = 2)
P(X = 2) = [C(5,2) × C(15,2)] / C(20,4)  
= (10 × 105) / 4845  
= 1050 / 4845  
≈ **0.2167**

### P(X = 3)
P(X = 3) = [C(5,3) × C(15,1)] / C(20,4)  
= (10 × 15) / 4845  
= 150 / 4845  
≈ **0.0310**

### P(X = 4)
P(X = 4) = [C(5,4) × C(15,0)] / C(20,4)  
= (5 × 1) / 4845  
= 5 / 4845  
≈ **0.0010**

## Probability table

| x | P(X = x) |
|---|----------|
| 0 | 1365 / 4845 ≈ 0.2817 |
| 1 | 2275 / 4845 ≈ 0.4696 |
| 2 | 1050 / 4845 ≈ 0.2167 |
| 3 | 150 / 4845 ≈ 0.0310 |
| 4 | 5 / 4845 ≈ 0.0010 |

The probabilities add up to 1, so this is a valid probability distribution.

## 5. Meaning of success in this model
In the hypergeometric model, a **success** means selecting an item with the characteristic of interest.  
In this problem, the characteristic of interest is being **defective**.  

So, **a success means that a selected component is defective**.
