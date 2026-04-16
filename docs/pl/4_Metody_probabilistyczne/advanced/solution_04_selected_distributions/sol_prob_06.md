# Problem 6 — Final Discussion: The Axiomatic Point of View

## The Axiomatic Formulation of Probability

Probability can be formalized as a mathematical function that assigns a number to each event in a sample space. This idea generalizes the notion of observed frequencies from repeated experiments and provides a consistent theoretical framework.

The modern formulation is based on the Kolmogorov axioms.

---

## Kolmogorov Axioms

Let Ω be a sample space and let A, B, ... be events (subsets of Ω). A probability measure P satisfies:

1. **Non-negativity**  
   \[
   P(A) \ge 0 \quad \text{for every event } A
   \]

2. **Normalization**  
   \[
   P(\Omega) = 1
   \]

3. **Countable additivity**  
   For any sequence of pairwise disjoint events \( A_1, A_2, A_3, \dots \):
   \[
   P\left(\bigcup_{i=1}^{\infty} A_i\right) = \sum_{i=1}^{\infty} P(A_i)
   \]

---

## Connection with Earlier Work

In the previous problems, we worked with:

- elementary outcomes and events,
- observed frequencies from repeated experiments,
- functions of the form \( f(A) = \frac{n(A)}{N} \).

From this framework, several properties naturally appeared:

### 1. Non-negativity

Observed frequencies are always non-negative because counts cannot be negative:

\[
f(A) = \frac{n(A)}{N} \ge 0
\]

---

### 2. Normalization

The total number of outcomes equals the total number of trials:

\[
f(\Omega) = \frac{N}{N} = 1
\]

---

### 3. Finite Additivity

For disjoint events A and B:

\[
f(A \cup B) = f(A) + f(B)
\]

This follows directly from counting, since disjoint events do not overlap.

---

## What Goes Beyond Finite Experiments

While non-negativity, normalization, and finite additivity arise naturally from observed data, the third Kolmogorov axiom — **countable additivity** — is more subtle.

In our earlier work:

- we only considered **finite sample spaces**,
- and **finite unions of events**.

However, countable additivity involves:

- potentially infinite collections of events,
- limits of sequences of events,
- situations that cannot be directly observed through finite experiments.

---

## Why Countable Additivity Is More Subtle

Finite experiments can only produce finite data. Therefore:

- we can verify additivity for a finite number of disjoint events,
- but we cannot experimentally verify infinite sums.

Countable additivity is introduced as a **mathematical principle** that ensures:

- consistency of probability in infinite settings,
- proper behavior of limits,
- compatibility with more advanced constructions (e.g., continuous distributions).

---

## Conclusion

The axiomatic approach to probability extends the intuitive ideas obtained from observed frequencies into a rigorous mathematical theory.

- Non-negativity, normalization, and finite additivity arise naturally from counting and experimentation.
- Countable additivity goes beyond empirical observation and reflects a deeper structural requirement of the theory.

Thus, probability can be understood as a bridge between empirical data and abstract mathematics.
