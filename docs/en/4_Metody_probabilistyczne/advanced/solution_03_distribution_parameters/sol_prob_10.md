# Task 10 — Solution

Since X and Y are independent random variables, the expected value of their product is equal to the product of their expected values.

So:

E(X^3Y) = E(X^3)E(Y)

But we are given that:

E(Y) = 0

Therefore:

E(X^3Y) = E(X^3) · 0 = **0**

---

Now let:

Z = X^3Y

Then:

E(Z) = E(X^3Y) = **0**

So yes, the variable Z has expected value equal to 0.

---

## Interpretation

This means that, on average, the signal \(X^3Y\) has no positive or negative bias.

In the context of random signals or noise, this means that although individual values of Z may be positive or negative, their long-run average is 0.

So the signal is centered around zero and does not create a systematic shift in one direction.

---

## Final answer:

- E(X^3Y) = E(X^3)E(Y)
- E(X^3Y) = **0**
- Therefore, **E(Z) = 0**
- In the noise context, this means the signal has **zero average** and no constant bias.
