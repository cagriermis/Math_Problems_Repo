# Problem 6 — Final Discussion: The Axiomatic Point of View

Probability can be understood as a function that assigns a number to each event, extending the idea of observed frequencies from repeated experiments.

## Kolmogorov Axioms

A probability measure P satisfies:

1. P(A) ≥ 0 for every event A (non-negativity)
2. P(Ω) = 1 (normalization)
3. For disjoint events A and B:
   P(A ∪ B) = P(A) + P(B)

More generally, for countably many disjoint events:
   P(⋃ A_i) = Σ P(A_i)

---

## Relation to Earlier Work

From previous problems, we defined:

f(A) = n(A) / N

This naturally satisfies:

- f(A) ≥ 0 (counts are non-negative)
- f(Ω) = 1 (total outcomes divided by total trials)
- f(A ∪ B) = f(A) + f(B) for disjoint A, B (no overlap in counting)

Thus, non-negativity, normalization, and finite additivity arise directly from observed frequencies.

---

## What Goes Beyond

In earlier problems, we only worked with:

- finite sample spaces
- finite sums of events

However, the Kolmogorov axioms require **countable additivity**, which involves infinitely many events.

This cannot be derived from experiments, since:

- real experiments are always finite
- we cannot observe infinitely many trials or events

---

## Key Insight

Finite additivity comes from counting.

Countable additivity is an additional mathematical assumption that ensures consistency when dealing with infinite collections of events.

---

## Conclusion

Probability theory generalizes observed frequencies into a mathematical model:

- elementary outcomes → define events  
- observed frequencies → suggest properties  
- axioms → formalize these properties  

Non-negativity, normalization, and finite additivity come from experiments, while countable additivity extends the theory beyond finite observations.
