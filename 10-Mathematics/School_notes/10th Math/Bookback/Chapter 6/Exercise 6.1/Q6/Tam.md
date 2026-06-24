# பயிற்சி 6.1

## வினா 6:

பின்வரும் மெய்யுறாமைகளை நிரூபிக்கவும்.

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

## தீர்க்கும் முறை (குறிப்பிற்காக):

1. மெய்யுறாமையின் இடது பக்கத்தை (LHS) எடுத்துக் கொள்ளவும்.
2. இயற்கணித மற்றும் முக்கோணவியல் மெய்யுறாமைகளைப் பயன்படுத்தவும்.
3. படிப்படியாக எளிமைப்படுத்தவும்.
4. வலது பக்கத்தை (RHS) பெறவும்.

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

எனவே நிரூபிக்கப்பட்டது.
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