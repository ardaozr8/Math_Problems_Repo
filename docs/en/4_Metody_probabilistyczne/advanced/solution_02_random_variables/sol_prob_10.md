## Task 10

For the density function from **Task 9**:

f(x,y) = xy   for 0 ≤ x ≤ 2 and 0 ≤ y ≤ 1  
f(x,y) = 0    otherwise

determine the **marginal densities** \(f_1(x)\) and \(f_2(y)\).  
Then check whether the random variables **X** and **Y** are **independent**, i.e. whether

f(x,y) = f₁(x) · f₂(y)

---

## Step 1: Marginal Density of X

The marginal density of **X** is obtained by integrating the joint density over all possible values of **y**:

f₁(x) = ∫₀¹ f(x,y) dy

Substitute f(x,y) = xy:

f₁(x) = ∫₀¹ xy dy

Since **x** is constant with respect to **y**:

f₁(x) = x ∫₀¹ y dy

f₁(x) = x [ y² / 2 ]₀¹

f₁(x) = x / 2

So:

f₁(x) = x/2, for 0 ≤ x ≤ 2  
f₁(x) = 0, otherwise

---

## Step 2: Marginal Density of Y

The marginal density of **Y** is obtained by integrating the joint density over all possible values of **x**:

f₂(y) = ∫₀² f(x,y) dx

Substitute f(x,y) = xy:

f₂(y) = ∫₀² xy dx

Since **y** is constant with respect to **x**:

f₂(y) = y ∫₀² x dx

f₂(y) = y [ x² / 2 ]₀²

f₂(y) = y · 2

f₂(y) = 2y

So:

f₂(y) = 2y, for 0 ≤ y ≤ 1  
f₂(y) = 0, otherwise

---

## Step 3: Check Independence

Now compute the product:

f₁(x) · f₂(y) = (x/2) · (2y)

f₁(x) · f₂(y) = xy

But the joint density is:

f(x,y) = xy

Thus:

f(x,y) = f₁(x) · f₂(y)

for all \(0 ≤ x ≤ 2\) and \(0 ≤ y ≤ 1\).

Therefore, the variables **X** and **Y** are **independent**.

---

## Final Results

Marginal densities:

f₁(x) = x/2, for 0 ≤ x ≤ 2  
f₁(x) = 0, otherwise

f₂(y) = 2y, for 0 ≤ y ≤ 1  
f₂(y) = 0, otherwise

Independence:

X and Y are **independent**, because

f(x,y) = f₁(x) · f₂(y)
