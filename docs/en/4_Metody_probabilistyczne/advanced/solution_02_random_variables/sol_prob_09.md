## Task 9

Select the constant **c** such that the function

f(x,y) = cxy   for 0 ≤ x ≤ 2 and 0 ≤ y ≤ 1  
f(x,y) = 0     for other (x,y)

is the **density function of the two-dimensional random variable (X,Y)**.

---

## Step 1: Property of a Density Function

For a function to be a valid **joint probability density function**, the integral over the entire domain must equal **1**:

∬ f(x,y) dx dy = 1

The domain is:

0 ≤ x ≤ 2  
0 ≤ y ≤ 1

So we compute:

∫₀² ∫₀¹ cxy dy dx = 1

---

## Step 2: Compute the Inner Integral

∫₀¹ cxy dy

Since **x and c are constants with respect to y**:

= cx ∫₀¹ y dy

= cx [ y² / 2 ]₀¹

= cx / 2

---

## Step 3: Compute the Outer Integral

Now integrate with respect to **x**:

∫₀² (cx / 2) dx

= c/2 ∫₀² x dx

= c/2 [ x² / 2 ]₀²

= c/2 · (4/2)

= c

---

## Step 4: Solve for c

Since the total integral must equal **1**:

c = 1

---

## Final Result

The constant is:

c = 1

So the valid joint density function is:

f(x,y) = xy   for 0 ≤ x ≤ 2 and 0 ≤ y ≤ 1  
f(x,y) = 0    otherwise
