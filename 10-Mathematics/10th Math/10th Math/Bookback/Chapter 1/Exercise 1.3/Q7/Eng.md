# Exercise 1.3

## Question:

An open box is to be made from a square piece of material, 24 cm on a side, by cutting equal squares of side x cm from each corner and turning up the sides as shown Fig 1.17.

<p align="center">
  <img src="https://raw.githubusercontent.com/Jeevanya25Ravi/Vfam_Roteen/main/Roteen%20Maths/Exercise%201.3-7.png" width="250">
</p>

<p align="center"><b>Fig. 1.17</b></p>

Express the volume V of the box as a function of x.

---

## Procedure to solve (For reference):

1. The original square sheet has side length 24 cm.
2. Squares of side x cm are cut from each corner.
3. After folding:
   - Height of the box = x cm
   - Length of the base = 24 − 2x cm
   - Width of the base = 24 − 2x cm
4. Use the volume formula:

```text
Volume = Length × Width × Height
```

5. Substitute the dimensions and simplify.

---

## Solution:

Given:

```text
Total length of Side of square sheet = 24 cm
```

Squares of side x cm are removed from each corner.

After folding:

```text
The length of square cut off = x cm
Remaining length = 24 − 2x cm
Remaining breadth  = 24 − 2x cm
```

Volume of the box:

```text
V = Length × Width × Height
```

Substituting the values:

```text
V(x) = (24 − 2x)(24 − 2x)(x)
```

```text
V(x) = (24 − 2x)²(x)
```

Expanding by (a-b)² formula:

```text
(a-b)² = (a² - 2ab + b²)

V(x) = [(24)² -2 x 24 + 2x + (2x)²](x)
     = (576 - 48x - 48x + 4x²)(x)
     = (576 - 96x + 4x²)(x)
     = 576x - 96x² + 4x³
     = 4x³ - 96x² + 576x
```

---

## Final Answer:

```text
V(x) = 4x³ - 96x² + 576x
```

where

```text
0 < x < 12
```

(since the side length of the base must remain positive).

---