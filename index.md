---
title: New comer training program
layout: home
---

# Problem 1
The transfer function of a digital filter is expressed as follows:
```math
H(z) = \frac{B(z)}{A(z)} = \frac{b_0+b_1z^{-1}+...+b_{n-1}z^{-(n-1)}+b_nz^{-n}}{a_0+a_1z^{-1}+...+a_{m-1}z^{-(m-1)}+a_mz^{-m}}
```
Accordingly, a filter is usually expressed by two coefficient vectors, $b$ and $a$.
```math
\begin{eqnarray}
   b &= &[b_0,b_1,...,b_n],\\
   a &= &[a_0,a_1,...,a_m]
\end{eqnarray}
```
1. Given a low-pass filter with $b=[1,2,1]$ and $a=[4,0]$, plot its **frequency response** (with the cut-off frequency showed in the figure) and its **phase response**.
2. Given a high-pass filter with $b=[-1,2,-1]$ and $a=[4,0]$, plot its **frequency response** (with the cut-off frequency showed in the figure) and its **phase response**.

# Problem 2
The mathematical expression of the 1-D CZP(Circular Zone Plate) signal is given as follows:
```math
z(x) = C_w\cdot \mathrm{cos}\left(\pi\frac{x^2}{T}\right) + C_{offset}
```
where
|||
| --- | --- |
| $C_w$ | gain |
| $C_{offset}$ | offset |
| $T$ | period |

Plot the 1-D CZP signal ($C_w$, $C_{offset}$, and $T$ can be freely chosen).

# Problem 3
The mathematical expression of the 2-D CZP signal is given as follows:
```math
z(x,y) = C_w\cdot \mathrm{cos}\left(\pi\frac{x^2+y^2}{T}\right) + C_{offset}
```
1. Plot the 2-D CZP signal ($C_w$, $C_{offset}$, and $T$ can be freely chosen).
2. Given a low-pass filter represented by the following matrix, plot the result of filtering the CZP signal.
```math
\frac{1}{4}\cdot
\begin{bmatrix}
1 & 2 & 1 \\[0.3em]
2 & 4 & 2 \\[0.3em]
1 & 2 & 1
\end{bmatrix}
```
3. Given a high-pass filter represented by the following matrix, plot the result of filtering the CZP signal.
```math
\frac{1}{4}\cdot
\begin{bmatrix}
1 & -2 & 1 \\[0.3em]
-2 & 4 & -2 \\[0.3em]
1 & -2 & 1
\end{bmatrix}
```
