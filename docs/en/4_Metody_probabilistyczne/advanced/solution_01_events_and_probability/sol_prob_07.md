## Task 7

Two code combinations are transmitted:

- **111** with prior probability **0.65**
- **000** with prior probability **0.35**

During transmission:
- each transmitted **1** is received as **0** with probability **0.2**
- each transmitted **0** is received as **1** with probability **0.2**

So each symbol is received correctly with probability:

**0.8**

The symbols are distorted **independently**.

---

### 1. Probability of receiving 111

The received signal **111** can come from two cases:

#### Case 1: 111 was sent and all three symbols were received correctly

P(111 received | 111 sent) = 0.8³ = 0.512

Contribution:

0.65 × 0.512 = 0.3328

#### Case 2: 000 was sent and all three symbols were flipped

P(111 received | 000 sent) = 0.2³ = 0.008

Contribution:

0.35 × 0.008 = 0.0028

Now add both contributions:

**P(receiving 111) = 0.3328 + 0.0028 = 0.3356**

---

### 2. Probability of receiving 000

Again, this can happen in two cases:

#### Case 1: 000 was sent and all three symbols were received correctly

P(000 received | 000 sent) = 0.8³ = 0.512

Contribution:

0.35 × 0.512 = 0.1792

#### Case 2: 111 was sent and all three symbols were flipped

P(000 received | 111 sent) = 0.2³ = 0.008

Contribution:

0.65 × 0.008 = 0.0052

Add both contributions:

**P(receiving 000) = 0.1792 + 0.0052 = 0.1844**

---

### 3. Probability of receiving 010

The received signal **010** can also come from both transmitted signals.

#### Case 1: 111 was sent

To receive **010** from **111**:
- first 1 must flip to 0 → 0.2
- second 1 must stay 1 → 0.8
- third 1 must flip to 0 → 0.2

So:

P(010 received | 111 sent) = 0.2 × 0.8 × 0.2 = 0.032

Contribution:

0.65 × 0.032 = 0.0208

#### Case 2: 000 was sent

To receive **010** from **000**:
- first 0 must stay 0 → 0.8
- second 0 must flip to 1 → 0.2
- third 0 must stay 0 → 0.8

So:

P(010 received | 000 sent) = 0.8 × 0.2 × 0.8 = 0.128

Contribution:

0.35 × 0.128 = 0.0448

Now add both parts:

**P(receiving 010) = 0.0208 + 0.0448 = 0.0656**

---

## Final Results

1. **P(receiving 111) = 0.3356**  
2. **P(receiving 000) = 0.1844**  
3. **P(receiving 010) = 0.0656**
