# Problem 4 — Building Complex Statements from Simple Ones

## Representation

Each outcome is denoted by a pair (i, j), where:
- i — result of the first die (row)
- j — result of the second die (column)

---

## Part A — Basic Events

### A: The sum is equal to 7
  1 2 3 4 5 6
1 . . . . . X
2 . . . . X .
3 . . . X . .
4 . . X . . .
5 . X . . . .
6 X . . . . .

---

### B: The first die is greater than the second
  1 2 3 4 5 6
1 . . . . . .
2 X . . . . .
3 X X . . . .
4 X X X . . .
5 X X X X . .
6 X X X X X .

---

### C: At least one die shows 6
  1 2 3 4 5 6
1 . . . . . X
2 . . . . . X
3 . . . . . X
4 . . . . . X
5 . . . . . X
6 X X X X X X

---

## Part B — Compound Events

### 1. A ∪ C (sum = 7 OR at least one die is 6)
  1 2 3 4 5 6
1 . . . . . X
2 . . . . X X
3 . . . X . X
4 . . X . . X
5 . X . . . X
6 X X X X X X

---

### 2. A ∩ C (sum = 7 AND at least one die is 6)
  1 2 3 4 5 6
1 . . . . . X
2 . . . . . .
3 . . . . . .
4 . . . . . .
5 . . . . . .
6 X . . . . .

---

### 3. B ∩ C (first die > second AND at least one die is 6)
  1 2 3 4 5 6
1 . . . . . .
2 . . . . . .
3 . . . . . .
4 . . . . . .
5 . . . . . .
6 X X X X X .

---

### 4. A ∩ (not B) (sum = 7 AND first ≤ second)
  1 2 3 4 5 6
1 . . . . . X
2 . . . . X .
3 . . . X . .
4 . . . . . .
5 . . . . . .
6 . . . . . .

---

### 5. A ∩ (no 6)
  1 2 3 4 5 6
1 . . . . . .
2 . . . . X .
3 . . . X . .
4 . . X . . .
5 . X . . . .
6 . . . . . .

---

### 6. C ∩ (not A)
  1 2 3 4 5 6
1 . . . . . .
2 . . . . . X
3 . . . . . X
4 . . . . . X
5 . . . . . X
6 . X X X X X

---

### 7. (not A) ∩ B
  1 2 3 4 5 6
1 . . . . . .
2 X . . . . .
3 X X . . . .
4 X X X . . .
5 X X X X . .
6 . X X X X .

---

### 8. (not B) ∩ C
  1 2 3 4 5 6
1 . . . . . X
2 . . . . . X
3 . . . . . X
4 . . . . . X
5 . . . . . X
6 . . . . . X

---

### 9. not (A ∪ C)
  1 2 3 4 5 6
1 X X X X X .
2 X X X X . .
3 X X X . X .
4 X X . X X .
5 X . X X X .
6 . . . . . .

---

### 10. not (A ∩ C)
  1 2 3 4 5 6
1 X X X X X .
2 X X X X X X
3 X X X X X X
4 X X X X X X
5 X X X X X X
6 . X X X X X
