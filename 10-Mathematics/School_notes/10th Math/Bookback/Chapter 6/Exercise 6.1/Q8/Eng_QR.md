# Exercise 6.1

## Question 8:

Prove the following.

$$
\text{(i) If }
\frac{\cos\alpha}{\cos\beta}=m
\text{ and }
\frac{\cos\alpha}{\sin\beta}=n,
\text{ then prove that }
(m^2+n^2)\cos^2\beta=n^2.
$$

$$
\text{(ii) If }
\cot\theta+\tan\theta=x
\text{ and }
\sec\theta-\cos\theta=y,
\text{ then prove that }
(x^2y)^{\frac{2}{3}}-(xy^2)^{\frac{2}{3}}=1.
$$

---

## Solution:

#### (i)

Given:

$$
\frac{\cos\alpha}{\cos\beta}=m
\qquad
\text{and}
\qquad
\frac{\cos\alpha}{\sin\beta}=n
$$

To prove:

$$
(m^2+n^2)\cos^2\beta=n^2
$$

$$
m=\frac{\cos\alpha}{\cos\beta}
\Rightarrow
m^2=\frac{\cos^2\alpha}{\cos^2\beta}
$$

$$
n=\frac{\cos\alpha}{\sin\beta}
\Rightarrow
n^2=\frac{\cos^2\alpha}{\sin^2\beta}
$$

$$
m^2+n^2
=
\frac{\cos^2\alpha}{\cos^2\beta}
+
\frac{\cos^2\alpha}{\sin^2\beta}
$$

$$
=
\cos^2\alpha
\left(
\frac{\sin^2\beta+\cos^2\beta}
     {\sin^2\beta\cos^2\beta}
\right)
$$

$$
=
\frac{\cos^2\alpha}
     {\sin^2\beta\cos^2\beta}
$$

Multiplying by $\cos^2\beta$,

$$
(m^2+n^2)\cos^2\beta
=
\frac{\cos^2\alpha}
     {\sin^2\beta}
$$

$$
=
n^2
$$

Hence proved.

---
#### (ii)

Given:

$$
\cot\theta+\tan\theta=x
$$

and

$$
\sec\theta-\cos\theta=y
$$

To prove:

$$
(x^2y)^{\frac23}
-
(xy^2)^{\frac23}
=
1
$$

$$
x
=
\frac{\cos\theta}{\sin\theta}
+
\frac{\sin\theta}{\cos\theta}
$$

$$
=
\frac{\sin^2\theta+\cos^2\theta}
     {\sin\theta\cos\theta}
=
\frac1{\sin\theta\cos\theta}
$$

$$
y
=
\frac1{\cos\theta}-\cos\theta
$$

$$
=
\frac{1-\cos^2\theta}
     {\cos\theta}
=
\frac{\sin^2\theta}
     {\cos\theta}
$$

$$
x^2y
=
\frac1{\sin^2\theta\cos^2\theta}
\cdot
\frac{\sin^2\theta}
     {\cos\theta}
=
\frac1{\cos^3\theta}
$$

$$
(x^2y)^{\frac23}
=
\frac1{\cos^2\theta}
=
\sec^2\theta
$$

$$
xy^2
=
\frac1{\sin\theta\cos\theta}
\cdot
\frac{\sin^4\theta}
     {\cos^2\theta}
=
\frac{\sin^3\theta}
     {\cos^3\theta}
$$

$$
(xy^2)^{\frac23}
=
\frac{\sin^2\theta}
     {\cos^2\theta}
=
\tan^2\theta
$$

$$
(x^2y)^{\frac23}
-
(xy^2)^{\frac23}
=
\sec^2\theta-\tan^2\theta
$$

$$
=1
$$

Hence proved.

---