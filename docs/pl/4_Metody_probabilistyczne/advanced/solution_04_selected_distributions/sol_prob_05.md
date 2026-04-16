# Problem 5 — From Recorded Frequencies to Probability

A student rolled a six-sided die 1000 times.

Observed frequencies:

n({1}) = 168  
n({2}) = 154  
n({3}) = 181  
n({4}) = 167  
n({5}) = 160  
n({6}) = 170  

Total: 1000

Define:
f(A) = n(A) / 1000

---

## Part A — From elementary outcomes to events

### A = {2,4,6}

n(A) = 154 + 167 + 170 = 491  
f(A) = 491 / 1000 = 0.491

---

### B = {1,2,3}

n(B) = 168 + 154 + 181 = 503  
f(B) = 503 / 1000 = 0.503

---

### C = {5,6}

n(C) = 160 + 170 = 330  
f(C) = 330 / 1000 = 0.330

---

### D = {1,3,5}

n(D) = 168 + 181 + 160 = 509  
f(D) = 509 / 1000 = 0.509

---

### E = {1,2,3,4}

n(E) = 168 + 154 + 181 + 167 = 670  
f(E) = 670 / 1000 = 0.670

---

## Part B — How frequencies combine

1. f({2,4,6}) = f({2}) + f({4}) + f({6})

0.491 = 0.154 + 0.167 + 0.170 ✔

Explanation: disjoint events → frequencies add.

---

2. f({1,2,3,4}) = f({1,2}) + f({3,4})

0.670 = (168+154)/1000 + (181+167)/1000  
0.670 = 0.322 + 0.348 ✔

Explanation: disjoint union.

---

3. f({1,3,5}) + f({2,4,6}) = 1

0.509 + 0.491 = 1 ✔

Explanation: complementary events.

---

4. f({5,6}) = 1 − f({1,2,3,4})

0.330 = 1 − 0.670 ✔

Explanation: complement rule.

---

## Part C — When addition works and when it fails

### Check:

f({1,2} ∪ {5,6}) = f({1,2}) + f({5,6})

Left side:
n = 168 + 154 + 160 + 170 = 652 → f = 0.652

Right side:
(168+154)/1000 + (160+170)/1000 = 0.322 + 0.330 = 0.652 ✔

Explanation: disjoint sets.

---

### Now let:

M = {1,2,3}  
N = {3,4,5}

n(M) = 168 + 154 + 181 = 503 → f(M) = 0.503  
n(N) = 181 + 167 + 160 = 508 → f(N) = 0.508  

M ∪ N = {1,2,3,4,5}

n = 168 + 154 + 181 + 167 + 160 = 830 → f = 0.830

f(M) + f(N) = 0.503 + 0.508 = 1.011

---

### Conclusion:

f(M ∪ N) ≠ f(M) + f(N)

Explanation:  
The outcome {3} is counted twice.

---

### Double-counted outcome:

{3}

---

## Part D — Covering the whole sample space

n({1}) + n({2}) + n({3}) + n({4}) + n({5}) + n({6}) = 1000  

Thus:

f({1}) + ... + f({6}) = 1

---

Split:

{1,2}, {3,4}, {5,6}

f({1,2}) = (168+154)/1000 = 0.322  
f({3,4}) = (181+167)/1000 = 0.348  
f({5,6}) = (160+170)/1000 = 0.330  

Sum:

0.322 + 0.348 + 0.330 = 1 ✔

---

### General statement:

For any disjoint partition of Ω, the sum of frequencies equals 1.

---

## Part E — From observed frequency to probability

We define a function:

f(A) = n(A) / 1000

This function satisfies:

1. 0 ≤ f(A) ≤ 1  
2. f(∅) = 0  
3. f(Ω) = 1  
4. For disjoint events: f(A ∪ B) = f(A) + f(B)  
5. For complements: f(Aᶜ) = 1 − f(A)

Thus, f behaves like a probability measure.

---

## Part F — Conclusion

The three levels are connected as follows:

1. Elementary outcomes and events describe all possible results of an experiment.

2. Observed frequencies come from repeating the experiment many times and counting how often events occur.

3. Probability is an abstraction of these frequencies — it represents the expected long-run behavior of events.

In other words, probability generalizes observed data into a mathematical model.
