# Example 1.3

## Question:

Let

```text
A = {x ∈ ℕ | 1 < x < 4}

B = {x ∈ W | 0 ≤ x < 2}

C = {x ∈ ℕ | x < 3}
```

Verify that

```text
(i) A × (B ∪ C) = (A × B) ∪ (A × C)

(ii) A × (B ∩ C) = (A × B) ∩ (A × C)
```

---

## Procedure to solve (For reference):

To verify the given identities:

1. Write the given sets in roster form.
2. Find the union and intersection of the sets.
3. Find the Cartesian products required.
4. Evaluate the Left Hand Side (LHS) and Right Hand Side (RHS).
5. Compare both sides.

---

## Solution:

#### Given:

```text
A = {2,3}

B = {0,1}

C = {1,2}
```

---

#### (i) Verify : A × (B ∪ C) = (A × B) ∪ (A × C)

```text
LHS:

B ∪ C

= {0,1} ∪ {1,2}

= {0,1,2}

A × (B ∪ C)

= {2,3} × {0,1,2}

= {(2,0), (2,1), (2,2), (3,0), (3,1), (3,2)} --->(1)
```

```text
RHS:

A × B

= {2,3} × {0,1}

= {(2,0), (2,1), (3,0), (3,1)}

A × C

= {2,3} × {1,2}

= {(2,1), (2,2), (3,1), (3,2)}

(A × B) ∪ (A × C)

= {(2,0), (2,1), (2,2), (3,0), (3,1), (3,2)} --->(2)
```

```text
LHS = RHS
```

Hence, from (1) and (2)

```text
A × (B ∪ C) = (A × B) ∪ (A × C)
```

is verified.

---

#### (ii) Verify : A × (B ∩ C) = (A × B) ∩ (A × C)

```text
LHS:

B ∩ C

= {0,1} ∩ {1,2}

= {1}

A × (B ∩ C)

= {2,3} × {1}

= {(2,1), (3,1)} --->(1)
```

```text
RHS:

A × B

= {(2,0), (2,1), (3,0), (3,1)}

A × C

= {(2,1), (2,2), (3,1), (3,2)}

(A × B) ∩ (A × C)

= {(2,1), (3,1)} --->(2)
```

```text
LHS = RHS
```

Hence, from (1) and (2)

```text
A × (B ∩ C) = (A × B) ∩ (A × C)
```

is verified.

---