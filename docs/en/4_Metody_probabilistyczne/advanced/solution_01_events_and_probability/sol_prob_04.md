## Task 4

The network consists of **two elements connected in parallel**: **a₁** and **a₂**.

Let:
- A₁ = event that element **a₁** remains functional for at least time **t**
- A₂ = event that element **a₂** remains functional for at least time **t**

We need to find the probability that **current flows continuously through the system for at least time t**.

### Step 1: Describe the event

Because the elements are connected in **parallel**, the system works if **at least one** of the two elements is functional.

So the required event is:

**A = A₁ ∪ A₂**

### Step 2: Use the formula for union of events

For any two events:

**P(A₁ ∪ A₂) = P(A₁) + P(A₂) - P(A₁ ∩ A₂)**

We are given:
- **P(A₁) = p**
- **P(A₂) = p**
- **P(A₁ ∩ A₂) = p²**

Substituting into the formula:

**P(A) = p + p - p²**

**P(A) = 2p - p²**

### Final Answer

The probability of continuous current flow through the system for at least time **t** is:

**P(A₁ ∪ A₂) = 2p - p²**
