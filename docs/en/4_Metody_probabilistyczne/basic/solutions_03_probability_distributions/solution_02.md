# Task 2 — Hypergeometric Model (Sampling from a Batch)

## 1. Description of the random experiment
The random experiment consists of selecting **4 components** at random from a batch of **20 components** **without replacement**.  
Among the 20 components, **5 are defective** and **15 are functional**.  
After the selection, we observe how many defective components appear in the sample.

## 2. Definition of the random variable
Let **X** denote the **number of defective components** in the sample of 4 selected components.

## 3. Possible values of X
Since we choose 4 components, the number of defective items in the sample can be:

\[
X \in \{0,1,2,3,4\}
\]

The value 4 is possible because there are 5 defective components in total, so drawing 4 defective ones can happen.

## 4. Probability distribution
The random variable **X** follows a **hypergeometric distribution** with parameters:

- Population size: \(N = 20\)
- Number of defective components: \(K = 5\)
- Sample size: \(n = 4\)

The probability mass function is:

\[
P(X = x) = \frac{\binom{5}{x}\binom{15}{4-x}}{\binom{20}{4}}, \quad x=0,1,2,3,4
\]

Now we calculate each probability:

### For \(X=0\)
\[
P(X=0)=\frac{\binom{5}{0}\binom{15}{4}}{\binom{20}{4}}
=\frac{1 \cdot 1365}{4845}
=\frac{1365}{4845}
\approx 0.2817
\]

### For \(X=1\)
\[
P(X=1)=\frac{\binom{5}{1}\binom{15}{3}}{\binom{20}{4}}
=\frac{5 \cdot 455}{4845}
=\frac{2275}{4845}
\approx 0.4696
\]

### For \(X=2\)
\[
P(X=2)=\frac{\binom{5}{2}\binom{15}{2}}{\binom{20}{4}}
=\frac{10 \cdot 105}{4845}
=\frac{1050}{4845}
\approx 0.2167
\]

### For \(X=3\)
\[
P(X=3)=\frac{\binom{5}{3}\binom{15}{1}}{\binom{20}{4}}
=\frac{10 \cdot 15}{4845}
=\frac{150}{4845}
\approx 0.0310
\]

### For \(X=4\)
\[
P(X=4)=\frac{\binom{5}{4}\binom{15}{0}}{\binom{20}{4}}
=\frac{5 \cdot 1}{4845}
=\frac{5}{4845}
\approx 0.0010
\]

## Probability table

| \(x\) | \(P(X=x)\) |
|------|------------|
| 0 | \(\frac{1365}{4845} \approx 0.2817\) |
| 1 | \(\frac{2275}{4845} \approx 0.4696\) |
| 2 | \(\frac{1050}{4845} \approx 0.2167\) |
| 3 | \(\frac{150}{4845} \approx 0.0310\) |
| 4 | \(\frac{5}{4845} \approx 0.0010\) |

The probabilities add up to 1, so this is a valid probability distribution.

## 5. Meaning of success in this model
In the hypergeometric model, a **success** means selecting an item with the characteristic of interest.  
In this problem, the characteristic of interest is being **defective**.  

So, **a success means that a selected component is defective**.
