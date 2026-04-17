# Problem 3 — Weather (7 days × 3 states)

Each day can be:
S — sunny  
C — cloudy  
R — rainy  

---

## Part A — Marking Events

### 1. Monday is sunny
  Mon Tue Wed Thu Fri Sat Sun
S X . . . . . .
C . . . . . . .
R . . . . . . .

---

### 2. The weekend (Saturday and Sunday) is rainy
  Mon Tue Wed Thu Fri Sat Sun
S . . . . . . .
C . . . . . . .
R . . . . . X X

---

### 3. It rains on Wednesday or Friday

(OR means at least one of them is rainy)
  Mon Tue Wed Thu Fri Sat Sun
S . . . . . . .
C . . . . . . .
R . . X . X . .

---

### 4. There is no rainy day during the week
  Mon Tue Wed Thu Fri Sat Sun
S X X X X X X X
C X X X X X X X
R . . . . . . .

---

### 5. Thursday is not sunny

(so Thursday is either cloudy or rainy)
  Mon Tue Wed Thu Fri Sat Sun
S . . . . . . .
C . . . X . . .
R . . . X . . .

---

## Part B — Interpretation

### Case 1
  Mon Tue Wed Thu Fri Sat Sun
S . . . . . X X
C . . . . . . .
R . . . . . . .

**Interpretation:**  
Saturday and Sunday are sunny.

---

### Case 2
  Mon Tue Wed Thu Fri Sat Sun
S X X X X X X X
C X X X X X X X
R . . . . . . .

**Interpretation:**  
There are no rainy days during the week.
