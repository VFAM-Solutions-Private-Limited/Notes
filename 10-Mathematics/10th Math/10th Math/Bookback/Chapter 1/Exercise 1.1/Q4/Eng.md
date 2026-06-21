# Exercise 1.1

## Question 4:

If A = {5,6}, B = {4,5,6}, C = {5,6,7}, 
show that A x A = (B x B) ∩ (C x C)

---
## Procedure to solve (For reference):

1. In A x A, pair each element of set A with every element of set A.  
2. In B x B, pair each element of set B with every element of set B.  
3. In C x C, pair each element of set C with every element of set C.  
4. Find the common ordered pairs from (B x B) and (C x C).  
5. Compare the result with A x A.  
6. If both are equal, the statement is proved.

---
## Solution:

#### Given:
 
A = {5,6}  
B = {4,5,6}  
C = {5,6,7}

---

```text
LHS:

To find A x A:

A x A = {5,6} x {5,6}

      = {(5,5), (5,6), (6,5), (6,6)} --->(1)

RHS:

To find B x B:

B x B = {4,5,6} x {4,5,6}

      = {(4,4), (4,5), (4,6), (5,4), (5,5), (5,6), (6,4), (6,5), (6,6)}


To find C x C:

C x C = {5,6,7} x {5,6,7}

      = {(5,5), (5,6), (5,7), (6,5), (6,6), (6,7), (7,5), (7,6), (7,7)}


To find (B x B) ∩ (C x C):

(B x B) ∩ (C x C) = {(5,5), (5,6), (6,5), (6,6)} -->(2)  

LHS = RHS

From (1) and (2)
A x A = (B x B) ∩ (C x C)
```
---
