# Exercise 6.1

## Question 1:

```text
Prove the following identities.

(i) cotθ + tanθ = secθ cosecθ

(ii) tan⁴θ + tan²θ = sec⁴θ − sec²θ
```

---

## Solution

#### (i) cotθ + tanθ = secθ cosecθ

```text
LHS = cotθ + tanθ

      cosθ      sinθ
    = ───── + ─────          (∵ cotθ = cosθ/sinθ,
      sinθ      cosθ             tanθ = sinθ/cosθ)

      cosθ × cosθ      sinθ × sinθ
    = ───────────── + ─────────────
      sinθ × cosθ      cosθ × sinθ

      cos²θ + sin²θ
    = ──────────────
       sinθ cosθ

              1
    = ─────────────        (∵ sin²θ + cos²θ = 1)
      sinθ cosθ

        1       1
    = ───── × ─────
      sinθ    cosθ

    = cosecθ × secθ        (∵ 1/sinθ = cosecθ,
                               1/cosθ = secθ)

    = secθ cosecθ

    = RHS

LHS = RHS

Hence Proved.
```

---

#### (ii) tan⁴θ + tan²θ = sec⁴θ − sec²θ

```text
LHS = tan⁴θ + tan²θ

    = tan²θ(tan²θ + 1)

    = tan²θ(sec²θ)         (∵ tan²θ + 1 = sec²θ)

    = (sec²θ − 1)sec²θ     (∵ tan²θ = sec²θ − 1)

    = sec⁴θ − sec²θ

    = RHS

LHS = RHS

Hence Proved.
```
---