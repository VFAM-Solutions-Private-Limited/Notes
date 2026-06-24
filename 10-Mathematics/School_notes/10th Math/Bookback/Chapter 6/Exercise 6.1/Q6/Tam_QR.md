# பயிற்சி 6.1

## வினா 6:

பின்வரும் முற்றொருமைகளை நிரூபிக்கவும்.

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

## விடை:

#### (i)

$$
\frac{\sin A-\sin B}{\cos A+\cos B}
+
\frac{\cos A-\cos B}{\sin A+\sin B}
=
0
$$

நிரூபிக்க:


$$
\begin{aligned}
LHS &=
\frac{\sin A-\sin B}{\cos A+\cos B}
+
\frac{\cos A-\cos B}{\sin A+\sin B}
\\[6pt]
&=
\frac{2\cos\frac{A+B}{2}\sin\frac{A-B}{2}}
     {2\cos\frac{A+B}{2}\cos\frac{A-B}{2}}
+
\frac{-2\sin\frac{A+B}{2}\sin\frac{A-B}{2}}
     {2\sin\frac{A+B}{2}\cos\frac{A-B}{2}}
\\[6pt]
&=
\frac{\sin\frac{A-B}{2}}
     {\cos\frac{A-B}{2}}
-
\frac{\sin\frac{A-B}{2}}
     {\cos\frac{A-B}{2}}
\\[6pt]
&=
\tan\frac{A-B}{2}
-
\tan\frac{A-B}{2}
\\[6pt]
&=0
\\[6pt]
&=\text{RHS}
\end{aligned}
$$

எனவே நிரூபிக்கப்பட்டது.

---

#### (ii)

$$
\frac{\sin^3A+\cos^3A}{\sin A+\cos A}
+
\frac{\sin^3A-\cos^3A}{\sin A-\cos A}
=
2
$$

நிரூபிக்க:

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

எனவே நிரூபிக்கப்பட்டது.
```

---