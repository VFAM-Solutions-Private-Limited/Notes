# Exercise 1.1

## Question 7:

Let  
A = Set of all natural numbers less than 8  
B = Set of all prime numbers less than 8  
C = Set of even prime numbers  

Verify that:<br>

(i) (A ∩ B) × C = (A × C) ∩ (B × C)<br>
(ii) A × (B − C) = (A × B) − (A × C)

---
## Procedure to solve (For reference):

1. Convert all given sets into **roster form**.  
2. Identify the required operations (∩, −, ×).  
3. For **LHS**:
   - Perform set operation first (∩ or −).
   - Then apply Cartesian product (×).
4. For **RHS**:
   - First compute Cartesian products separately.
   - Then apply ∩ (intersection) or − (difference).
5. While finding Cartesian product:
   - Pair each element of first set with every element of second set.
6. Write all ordered pairs clearly without repetition.
7. Compare LHS and RHS results.
8. If both are equal → **Verified**.

---
## Solution:

#### Given:

- A = Set of natural numbers less than 8  
  ⇒ A = {1, 2, 3, 4, 5, 6, 7}

- B = Set of prime numbers less than 8  
  ⇒ B = {2, 3, 5, 7}

- C = Set of even prime numbers  
  ⇒ C = {2}

---


#### (i) (A ∩ B) × C = (A × C) ∩ (B × C)
```text
LHS:

A ∩ B = {2, 3, 5, 7}

(A ∩ B) × C = {(2,2), (3,2), (5,2), (7,2)} --->(1)

RHS:

A × C = {(1,2), (2,2), (3,2), (4,2), (5,2), (6,2), (7,2)}

B × C = {(2,2), (3,2), (5,2), (7,2)}

(A × C) ∩ (B × C) = {(2,2), (3,2), (5,2), (7,2)} --->(2)

LHS = RHS

From (1) and (2), we get
(A ∩ B) × C = (A × C) ∩ (B × C)
```
---

#### (ii) A × (B − C) = (A × B) − (A × C)

```text
LHS:

B − C = {3,5,7}

A × (B − C) = {(1,3), (1,5), (1,7), (2,3), (2,5), (2,7), (3,3), (3,5), (3,7), (4,3), (4,5), (4,7), (5,3), (5,5), (5,7), (6,3), (6,5), (6,7), (7,3), (7,5), (7,7)} --->(1)

RHS:

A × B = {(1,2), (1,3), (1,5), (1,7), (2,2), (2,3), (2,5), (2,7), (3,2), (3,3), (3,5), (3,7), (4,2), (4,3), (4,5), (4,7), (5,2), (5,3), (5,5), (5,7), (6,2), (6,3), (6,5), (6,7), (7,2), (7,3), (7,5), (7,7)}

A × C = {(1,2), (2,2), (3,2), (4,2), (5,2), (6,2), (7,2)}

(A × B) − (A × C) = {(1,3), (1,5), (1,7),(2,3), (2,5), (2,7), (3,3), (3,5), (3,7), (4,3), (4,5), (4,7), (5,3), (5,5), (5,7), (6,3), (6,5), (6,7), (7,3), (7,5), (7,7)} --->(2)

LHS = RHS

From (1) and (2), we get
A × (B − C) = (A × B) − (A × C)
```
---
## Final answer:
Hence, the above two statements have been verified.

---