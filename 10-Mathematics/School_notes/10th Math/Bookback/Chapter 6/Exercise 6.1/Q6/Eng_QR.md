# Exercise 6.1

## Question 6:

Prove the following identities.

### (i)

$$
\frac{\sin A-\sin B}{\cos A+\cos B}
+
\frac{\cos A-\cos B}{\sin A+\sin B}
=
0
$$

### (ii)

$$
\frac{\sin^3A+\cos^3A}{\sin A+\cos A}
+
\frac{\sin^3A-\cos^3A}{\sin A-\cos A}
=
2
$$

---

## Solution:

#### (i)

$$
\frac{\sin A-\sin B}{\cos A+\cos B}
+
\frac{\cos A-\cos B}{\sin A+\sin B}
=
0
$$

To prove:

```text
            sinA - sinB              cosA - cosB
LHS =  ─────────────────── + ───────────────────
            cosA + cosB              sinA + sinB

      2cos(A+B/2)sin(A-B/2)    -2sin(A+B/2)sin(A-B/2)
    = ────────────────────── + ───────────────────────
      2cos(A+B/2)cos(A-B/2)    2sin(A+B/2)cos(A-B/2)

        sin(A-B/2)             sin(A-B/2)
    = ─────────────── - ───────────────
        cos(A-B/2)             cos(A-B/2)

    = tan(A-B/2) - tan(A-B/2)

    = 0

    = RHS

Hence proved.
```
---
#### (ii)

$$
\frac{\sin^3A+\cos^3A}{\sin A+\cos A}
+
\frac{\sin^3A-\cos^3A}{\sin A-\cos A}
=
2
$$

To prove:
```text
           sin³A + cos³A
LHS =  ───────────────────
            sinA + cosA

           sin³A - cos³A
    +  ───────────────────
            sinA - cosA

    = (sin²A - sinAcosA + cos²A)

      + (sin²A + sinAcosA + cos²A)

    = 2sin²A + 2cos²A

    = 2(sin²A + cos²A)

    = 2(1)

    = 2

    = RHS

Hence proved.
```

---