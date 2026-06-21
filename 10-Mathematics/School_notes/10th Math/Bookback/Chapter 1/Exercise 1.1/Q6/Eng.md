# Exercise 1.1

## Question 6:

Let A = {x ∈ W | x < 2}, B = {x ∈ N | 1 < x ≤ 4} and C = {3,5}.  

Verify that:

(i) A x (B ∪ C) = (A × B) ∪ (A × C)  
(ii) A x (B ∩ C) = (A × B) ∩ (A × C)  
(iii) (A ∪ B) × C = (A x C) ∪ (B x C)

---

## Procedure to solve (For reference):

1. Write the given sets in roster form.
2. Find the required operation between sets (Union ∪ or Intersection ∩).
3. Calculate the Left Hand Side (LHS) Cartesian product.
4. Calculate the Cartesian products on the Right Hand Side (RHS) separately.
5. Apply Union (∪) or Intersection (∩) to the RHS results.
6. List all ordered pairs correctly without repetition.
7. Compare the LHS and RHS sets.
8. If both sides contain the same ordered pairs, the result is verified..

---

## Solution:

#### Given:

- A = {x ∈ W | x < 2}

    W = Whole numbers = {0,1,2,3,...}

    x < 2 ⇒ values are 0 and 1

    ∴ A = {0,1}


- B = {x ∈ N | 1 < x ≤ 4}

    N = Natural numbers = {1,2,3,4,...}

    1 < x ≤ 4 ⇒ values are 2, 3, 4

    ∴ B = {2,3,4}


- C = {3,5}  (Already in roster form)


---

#### Final Given Sets:

A = {0,1}  
B = {2,3,4}  
C = {3,5}

---

#### (i) A × (B ∪ C) = (A × B) ∪ (A × C)
```text
LHS:

B ∪ C = {2,3,4,5}

A × (B ∪ C) = {(0,2), (0,3), (0,4), (0,5), (1,2), (1,3), (1,4), (1,5)} --->(1)

RHS:

A × B = {(0,2), (0,3), (0,4), (1,2), (1,3), (1,4)}

A × C = {(0,3), (0,5), (1,3), (1,5)}

(A × B) ∪ (A × C) = {(0,2), (0,3), (0,4), (0,5), (1,2), (1,3), (1,4), (1,5)} --->(2)

LHS = RHS

Hence, From (1) and (2), we get
A × (B ∪ C) = (A × B) ∪ (A × C)
```
---

#### (ii) A × (B ∩ C) = (A × B) ∩ (A × C)
```text
LHS:

B ∩ C = {3}

A × (B ∩ C) = {(0,3), (1,3)} ---> [Since by (1)] --->(3)

RHS:

A × B = {(0,2), (0,3), (0,4), (1,2), (1,3), (1,4)}

A × C = {(0,3), (0,5), (1,3), (1,5)}

(A × B) ∩ (A × C) = {(0,3), (1,3)} ---(4)

LHS = RHS

Hence, From (3) and (4), we get
A × (B ∩ C) = (A × B) ∩ (A × C)
```

---

#### (iii) (A ∪ B) × C = (A × C) ∪ (B × C)

```text
LHS:

A ∪ B = {0,1,2,3,4}

(A ∪ B) × C = {(0,3), (0,5), (1,3), (1,5), (2,3), (2,5), (3,3), (3,5), (4,3), (4,5)} --->(5)

RHS:

A × C = {(0,3), (0,5), (1,3), (1,5)}

B × C = {(2,3), (2,5), (3,3), (3,5), (4,3), (4,5)}

(A × C) ∪ (B × C) = {(0,3), (0,5), (1,3), (1,5), (2,3), (2,5), (3,3), (3,5), (4,3), (4,5)} --->(6)

LHS = RHS

Hence, From (5) and (6), we get
(A ∪ B) × C = (A × C) ∪ (B × C)
```
---


## Final answer:
Hence, the above three statements have been verified.

---
