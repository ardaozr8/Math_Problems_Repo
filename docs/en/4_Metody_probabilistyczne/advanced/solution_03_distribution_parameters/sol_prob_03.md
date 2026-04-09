# Task 3 — Solution

## Given:

f(x) = 6x(1 − x), for 0 < x < 1

---

First, I calculate the expected value:

E(X) = ∫₀¹ x · 6x(1 − x) dx  
= ∫₀¹ 6x²(1 − x) dx  
= ∫₀¹ (6x² − 6x³) dx  

= [2x³ − (6/4)x⁴]₀¹  
= 2 − 1.5 = **0.5**

---

Now I calculate E(X²):

E(X²) = ∫₀¹ x² · 6x(1 − x) dx  
= ∫₀¹ 6x³(1 − x) dx  
= ∫₀¹ (6x³ − 6x⁴) dx  

= [(6/4)x⁴ − (6/5)x⁵]₀¹  
= 1.5 − 1.2 = **0.3**

---

Variance:

D²(X) = E(X²) − (E(X))²  
D²(X) = 0.3 − (0.5)²  
D²(X) = 0.3 − 0.25 = **0.05**

---

Now for Y = 2X − 1:

Using the property:

D²(Y) = a² · D²(X)

Here a = 2:

D²(Y) = 2² · 0.05  
D²(Y) = 4 · 0.05 = **0.2**
