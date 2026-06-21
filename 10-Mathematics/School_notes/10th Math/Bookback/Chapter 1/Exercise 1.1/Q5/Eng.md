# Exercise 1.1

## Question 5:

Given A = {1,2,3}, B = {2,3,5}, C = {3,4} and D = {1,3,5}, check if  
(A ∩ C) x (B ∩ D) = (A x B) ∩ (C x D) is true?

---

## Procedure to solve (For reference):

1. Find the intersection of A and C → (A ∩ C).  
2. Find the intersection of B and D → (B ∩ D).  
3. Find the Cartesian product of (A ∩ C) and (B ∩ D).  
4. Find A x B and C x D separately.  
5. Find the intersection of (A x B) and (C x D).  
6. Compare both results to check equality.

---

## Solution:

#### Given:

A = {1,2,3}  
B = {2,3,5}  
C = {3,4}  
D = {1,3,5}

---
```text
LHS => (A ∩ C) x (B ∩ D)

    A ∩ C = {1,2,3} x {3,4} = {3}

    B ∩ D = {2,3,5} x {1,3,5} = {3,5}

    (A ∩ C) x (B ∩ D) = {3} x {3,5}

                      = {(3,3), (3,5)}...(1)


RHS => (A x B) ∩ (C x D)
 
    A x B = {1,2,3} x {2,3,5} = {(1,2), (1,3), (1,5), (2,2), (2,3), (2,5), (3,2), (3,3), (3,5)}

    C x D = {3,4} x {1,3,5} = {(3,1), (3,3), (3,5), (4,1), (4,3), (4,5)}

    (A x B) ∩ (C x D) = {(1,2), (1,3), (1,5), (2,2), (2,3), (2,5), (3,2), (3,3), (3,5)} x {(3,1), (3,3), (3,5), (4,1), (4,3), (4,5)}

                      = {(3,3), (3,5)}...(2)

LHS = RHS

From (1) and (2) we get
(A ∩ C) x (B ∩ D) = (A x B) ∩ (C x D)
```
---

## Final Answer:

The given statement is TRUE.

---