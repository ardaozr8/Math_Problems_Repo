## Task 2

Assuming that the ratio of **very good, good, satisfactory, and failing** grades is:

1 : 3 : 4 : 2

Determine for the random variable **X** defined previously:

1. the probability mass function and its graph,
2. the cumulative distribution function (CDF) and its graph,
3. the probability \(P(X < 3.5)\).

---

## Step 1: Define the Random Variable

Let:

X = grade of a randomly selected student

Grading scale:

- 5 → very good  
- 4 → good  
- 3 → satisfactory  
- 2 → failing  

The ratio of grades is:

very good : good : satisfactory : failing  
1 : 3 : 4 : 2

Total parts:

1 + 3 + 4 + 2 = 10

---

## Step 2: Probability Mass Function (PMF)

The probability of each grade is obtained by dividing its ratio value by the total number of parts (10).

| X (Grade) | Interpretation | Probability |
|---|---|---|
| 2 | failing | 2/10 = 0.2 |
| 3 | satisfactory | 4/10 = 0.4 |
| 4 | good | 3/10 = 0.3 |
| 5 | very good | 1/10 = 0.1 |

So the **probability mass function** is:

P(X = 2) = 0.2  
P(X = 3) = 0.4  
P(X = 4) = 0.3  
P(X = 5) = 0.1  

---

## PMF Graph

The PMF graph is a **bar chart** where:

- x-axis → grade values (2,3,4,5)
- y-axis → probabilities

Values:

| X | P(X) |
|---|---|
|2|0.2|
|3|0.4|
|4|0.3|
|5|0.1|

---

## Step 3: Cumulative Distribution Function (CDF)

The cumulative distribution function is defined as:

F(x) = P(X ≤ x)

| x | F(x) |
|---|---|
| x < 2 | 0 |
| 2 ≤ x < 3 | 0.2 |
| 3 ≤ x < 4 | 0.6 |
| 4 ≤ x < 5 | 0.9 |
| x ≥ 5 | 1 |

Explanation:

F(2) = P(X ≤ 2) = 0.2  
F(3) = P(X ≤ 3) = 0.2 + 0.4 = 0.6  
F(4) = P(X ≤ 4) = 0.6 + 0.3 = 0.9  
F(5) = P(X ≤ 5) = 1

---

## Step 4: Probability \(P(X < 3.5)\)

Since the random variable is discrete, the values less than **3.5** are:

2 and 3

Therefore:

P(X < 3.5) = P(X = 2) + P(X = 3)

P(X < 3.5) = 0.2 + 0.4

P(X < 3.5) = 0.6

---

## Final Answer

- **PMF:** defined by probabilities {0.2, 0.4, 0.3, 0.1} for grades {2,3,4,5}
- **CDF:** step function with values {0, 0.2, 0.6, 0.9, 1}
- **P(X < 3.5) = 0.6**
