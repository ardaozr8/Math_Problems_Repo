## Task 10

Only three sequences can be transmitted:

- **AAAA** with probability **0.4**
- **BBBB** with probability **0.3**
- **CCCC** with probability **0.3**

For each single transmitted letter, the reception probabilities are:

| Transmitted \\ Received | A   | B   | C   |
|-------------------------|-----|-----|-----|
| A                       | 0.8 | 0.1 | 0.1 |
| B                       | 0.1 | 0.8 | 0.1 |
| C                       | 0.1 | 0.1 | 0.8 |

The letters are distorted **independently**.

We need to find the probability of receiving the following output signals.

---

### 1. Probability of receiving AAAA

The received sequence **AAAA** can come from:

#### Case 1: AAAA was transmitted

Each **A** must be received correctly as **A**.

**P(AAAA received | AAAA sent) = 0.8⁴ = 0.4096**

Contribution:

**0.4 × 0.4096 = 0.16384**

#### Case 2: BBBB was transmitted

Each **B** must be changed to **A**.

**P(AAAA received | BBBB sent) = 0.1⁴ = 0.0001**

Contribution:

**0.3 × 0.0001 = 0.00003**

#### Case 3: CCCC was transmitted

Each **C** must be changed to **A**.

**P(AAAA received | CCCC sent) = 0.1⁴ = 0.0001**

Contribution:

**0.3 × 0.0001 = 0.00003**

Now add all contributions:

**P(receiving AAAA) = 0.16384 + 0.00003 + 0.00003 = 0.16390**

---

### 2. Probability of receiving ACAA

The received sequence is **A C A A**.

Again, this output can come from each transmitted sequence.

#### Case 1: AAAA was transmitted

To receive **ACAA** from **AAAA**:
- 1st A → A : 0.8
- 2nd A → C : 0.1
- 3rd A → A : 0.8
- 4th A → A : 0.8

So:

**P(ACAA received | AAAA sent) = 0.8 × 0.1 × 0.8 × 0.8 = 0.0512**

Contribution:

**0.4 × 0.0512 = 0.02048**

#### Case 2: BBBB was transmitted

To receive **ACAA** from **BBBB**:
- 1st B → A : 0.1
- 2nd B → C : 0.1
- 3rd B → A : 0.1
- 4th B → A : 0.1

So:

**P(ACAA received | BBBB sent) = 0.1⁴ = 0.0001**

Contribution:

**0.3 × 0.0001 = 0.00003**

#### Case 3: CCCC was transmitted

To receive **ACAA** from **CCCC**:
- 1st C → A : 0.1
- 2nd C → C : 0.8
- 3rd C → A : 0.1
- 4th C → A : 0.1

So:

**P(ACAA received | CCCC sent) = 0.1 × 0.8 × 0.1 × 0.1 = 0.0008**

Contribution:

**0.3 × 0.0008 = 0.00024**

Now sum the contributions:

**P(receiving ACAA) = 0.02048 + 0.00003 + 0.00024 = 0.02075**

---

## Final Results

1. **P(receiving AAAA) = 0.16390**  
2. **P(receiving ACAA) = 0.02075**
