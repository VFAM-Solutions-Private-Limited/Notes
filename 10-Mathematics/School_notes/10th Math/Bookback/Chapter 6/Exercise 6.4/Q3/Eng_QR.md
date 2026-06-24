# Exercise 6.4

## Question 3:

If the angle of elevation of a cloud from a point $h$ metres above a lake is $\theta_1$ and the angle of depression of its reflection in the lake is $\theta_2$. Prove that the height that the cloud is located from the ground is

$$
\frac{h(\tan\theta_1+\tan\theta_2)}
{\tan\theta_2-\tan\theta_1}.
$$

---

## Diagram

<p align="center">
  <img src="https://raw.githubusercontent.com/Jeevanya25Ravi/Vfam_Roteen/main/Roteen%20Maths/Exercise%206.4_3.png" width="350">
</p>

---
## Solution:

Let

- $AB = h$ m be the height of the observation point above the lake.
- $CD = H$ m be the height of the cloud above the ground.
- $C'D$ be the reflection of the cloud in the lake.
- $BD = x$ m be the horizontal distance.

### Considering the cloud

$$
\begin{aligned}
\tan\theta_1
&= \frac{CD-AB}{BD}
\\
\tan\theta_1
&= \frac{H-h}{x}
\\
x
&= \frac{H-h}{\tan\theta_1}
\end{aligned}
$$

### Considering the reflection of the cloud

Since the reflection is at the same distance below the lake surface,

$$
\begin{aligned}
\tan\theta_2
&= \frac{AB+CD}{BD}
\\
\tan\theta_2
&= \frac{h+H}{x}
\\
x
&= \frac{h+H}{\tan\theta_2}
\end{aligned}
$$

Equating the two values of $x$,

$$
\begin{aligned}
\frac{H-h}{\tan\theta_1}
&=
\frac{h+H}{\tan\theta_2}
\end{aligned}
$$

Cross multiplying,

$$
\begin{aligned}
(H-h)\tan\theta_2
&=
(h+H)\tan\theta_1
\\
H\tan\theta_2-h\tan\theta_2
&=
h\tan\theta_1+H\tan\theta_1
\\
H(\tan\theta_2-\tan\theta_1)
&=
h(\tan\theta_1+\tan\theta_2)
\end{aligned}
$$

Therefore,

$$
\begin{aligned}
H
&=
\frac{h(\tan\theta_1+\tan\theta_2)}
{\tan\theta_2-\tan\theta_1}
\end{aligned}
$$

Hence,

$$
\boxed{
H=
\frac{h(\tan\theta_1+\tan\theta_2)}
{\tan\theta_2-\tan\theta_1}
}
$$

Hence proved.

---
