# Kotitehtavat_2.pdf

## Teht 1

$
A_0=
\begin{bmatrix}
3 \\
2 \\
5 \\
\end{bmatrix},
$
$
W_1=
\begin{bmatrix}
1.1 & -1.3 & 1.5 \\
0.1 & 2.0 & 1.7 \\
\end{bmatrix},
$
$
W_2=
\begin{bmatrix}
2.0, -1.2 \\
\end{bmatrix}
$

---

$
A_1=W_1 A_0
$

$
A_1=
\begin{bmatrix}
1.1 & -1.3 & 1.5 \\
0.1 & 2.0 & 1.7 \\
\end{bmatrix}
$
$
\begin{bmatrix}
3 \\
2 \\
5 \\
\end{bmatrix}
$

$
A_1=
\begin{bmatrix}
1.1 * 3 - 1.3 * 2 + 1.5 * 5 \\
0.1 * 3 + 2.0 * 2 + 1.7 * 5 \\
\end{bmatrix}
$

$
A_1=
\begin{bmatrix}
8.2 \\
12.8 \\
\end{bmatrix}
$

---

$
A_2=W_2 A_1
$

$
A_2=
\begin{bmatrix}
2.0, -1.2 \\
\end{bmatrix}
$
$
\begin{bmatrix}
8.2 \\
12.8 \\
\end{bmatrix}
$

$
A_2=
\begin{bmatrix}
2.0 * 8.2 - 1.2 * 12.8 \\
\end{bmatrix}
$

$
A_2=
\begin{bmatrix}
1.04 \\
\end{bmatrix}
$

## Teht 2

$
g(x)=\frac{1}{1+e^{-x}}
$

---

$
A_1=g(W_1 A_0)
$

$
A_1=g(
\begin{bmatrix}
1.1 & -1.3 & 1.5 \\
0.1 & 2.0 & 1.7 \\
\end{bmatrix}
$
$
\begin{bmatrix}
3 \\
2 \\
5 \\
\end{bmatrix}
)
$

$
A_1=g(
\begin{bmatrix}
1.1 * 3 - 1.3 * 2 + 1.5 * 5 \\
0.1 * 3 + 2.0 * 2 + 1.7 * 5 \\
\end{bmatrix}
)
$

$
A_1=
\begin{bmatrix}
0.99972542 \\
0.99999724 \\
\end{bmatrix}
$

---

$
A_2=g(W_2 A_1)
$

$
A_2=g(
\begin{bmatrix}
2.0, -1.2 \\
\end{bmatrix}
$
$
\begin{bmatrix}
0.99972542 \\
0.99999724 \\
\end{bmatrix}
)
$

$
A_2=g(
\begin{bmatrix}
2.0 * 0.99972542 - 1.2 * 0.99999724 \\
\end{bmatrix}
)
$

$
A_2=
\begin{bmatrix}
0.68985771 \\
\end{bmatrix}
$

<!--ADD THESE so the equations render correctly in HTML-->
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config">
    MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });
</script>