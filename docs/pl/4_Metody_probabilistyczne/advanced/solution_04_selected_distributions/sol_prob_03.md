# Problem 3 — Weather (7 days × 3 states)

Each day can be:
- S — Sunny  
- C — Cloudy  
- R — Rainy  

---

## Part A — Events

**1. Monday is sunny**

Monday = S

---

**2. The weekend (Saturday and Sunday) is rainy**

Saturday = R, Sunday = R

---

**3. It rains on Wednesday or Friday**

Wednesday = R or Friday = R

---

**4. There is no rainy day during the week**

No day has state R (only S or C allowed)

---

**5. Thursday is not sunny**

Thursday ∈ {C, R}

---

## Part B — Interpretation

**Case 1**

Saturday = S, Sunday = S

**Interpretation:**  
Saturday and Sunday are sunny.

---

**Case 2**

Rainy is excluded for all days.

**Interpretation:**  
There are no rainy days during the week.
