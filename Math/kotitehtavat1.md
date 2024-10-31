# Kotitehtavat_1.pfd

## Teht 1

$$
A = \begin{bmatrix}
    2 & 5 & -1 & 3 & 6 \\
    1 & 0 & 0 & -2 & 0 \\
    4 & 1 & -2 & 0 & 7 \\
    0 & 3 & 5 & 1 & -1 \\
    \end{bmatrix}
$$

Kertaluku on 4x5.

$A$(2,3) = 0
$A$(1,2) = 5
$A$(3,4) = 0
$A$(4,5) = -1

## Teht 2

$$

A(i,j) = \begin{cases}
            i-j, i<j \\
            0, i=j \\
            i+j2, i>j \\
        \end{cases}

$$

$$

A = \begin{bmatrix}
    0 & 1 & 2 & 3 & 4 \\
    -1 & 0 & 1 & 2 & 3 \\
    -2 & -1 & 0 & 1 & 2 \\
    -3 & -2 & -1 & 0 & 1 \\
    -4 & -3 & -2 & -1 & 0 \\
    \end{bmatrix}

$$

## Teht 3

a)
$
\sum_{i=1}^{100} i
$

b)
$
\sum_{n=1}^{\infty} \frac{(-1)^{n+1}}{n}
$

c)
$
\sum_{i=1}^{n} a_{ii}
$

d)
$
\sum_{i=1}^{n} a_{ki} x_i
$

e)
$
\sum_{i=1}^{n} a_{ki} b_{ip}
$

## Teht 4

a)

$
\sum_{j=1}^{5} A(3, j)
$

$
A(3, 1) + A(3, 2) + A(3, 3) + A(3, 4) + A(3, 5) = 4 + 1 + -2 + 0 + 7 = 10
$

b)

$
\sum_{k=1}^{4} A(k, k)
$

$
A(1, 1) + A(2, 2) + A(3, 3) + A(4, 4) = 2 + 0 + -2 + 1 = 1
$

c)

$
\sum_{i=1}^{4} A(i, 1)A(i, 3)
$

$
A(1, 1)A(1, 3) + A(2, 1)A(2, 3) + A(3, 1)A(3, 3) + A(4, 1)A(4, 3) = 2* -1 + 1*0 + 4*5 + 0*5 = 18
$

## Teht 5

$$
A = \begin{bmatrix}
1 & -3 \\
2 & 4 \\
0 & -1
\end{bmatrix}, \quad
B = \begin{bmatrix}
a & 3 \\
1 & -2 \\
x & 2
\end{bmatrix}, \quad
C = \begin{bmatrix}
0 \\
0 \\
0
\end{bmatrix}, \quad
D = \begin{bmatrix}
1 & -5 & x
\end{bmatrix}.
$$

---

a)
$
A + B = \begin{bmatrix}
1+a & 0 \\
3 & 2 \\
x & 1
\end{bmatrix}
$

b)
$
5A = \begin{bmatrix}
5 & -15 \\
10 & 20 \\
0 & -5
\end{bmatrix}
$

c)
$
C + D = \begin{bmatrix}
1 & -5 & x
\end{bmatrix}
$

d)
$
A + C = \begin{bmatrix}
1 & -3 \\
2 & 4 \\
0 & -1
\end{bmatrix}
$

e)
$
-B = \begin{bmatrix}
-a & -3 \\
-1 & 2 \\
-x & -2
\end{bmatrix}
$

f)
$
B - A = \begin{bmatrix}
a-1 & 6 \\
-1 & -6 \\
x & 3
\end{bmatrix}
$

## Teht 6

$$
A = \begin{bmatrix}
1 & 3 & 5 & 1
\end{bmatrix}, \quad
B = \begin{bmatrix}
-1 \\
3 \\
2 \\
4
\end{bmatrix}.
$$

---

$
AB = 1*-1 + 3*3 + 5*2 + 1*4 = -1 + 9 + 10 + 4 = 22
$

ja

$
BA = \begin{bmatrix}
-1 & 3 & 2 & 4
\end{bmatrix} \begin{bmatrix}
1 \\
3 \\
5 \\
1
\end{bmatrix} = -1*1 + 3*3 + 2*5 + 4*1 = -1 + 9 + 10 + 4 = 22
$

## Teht 7

$$
A = \begin{bmatrix}
1 & -1 & 1 \\
-3 & 2 & -1 \\
-2 & 1 & 0
\end{bmatrix}, \quad
B = \begin{bmatrix}
1 & 2 & 3 \\
2 & 4 & 6 \\
1 & 2 & 3
\end{bmatrix}.
$$

---

$$
AB = \begin{bmatrix}
1 & -1 & 1 \\
-3 & 2 & -1 \\
-2 & 1 & 0
\end{bmatrix} \begin{bmatrix}
1 & 2 & 3 \\
2 & 4 & 6 \\
1 & 2 & 3
\end{bmatrix} = \begin{bmatrix}
1*1 + -1*2 + 1*1 & 1*2 + -1*4 + 1*2 & 1*3 + -1*6 + 1*3 \\
-3*1 + 2*2 + -1*1 & -3*2 + 2*4 + -1*2 & -3*3 + 2*6 + -1*3 \\
-2*1 + 1*2 + 0*1 & -2*2 + 1*4 + 0*2 & -2*3 + 1*6 + 0*3
\end{bmatrix} = \begin{bmatrix}
1 & 0 & -2 \\
1 & 0 & -1 \\
0 & 0 & 0
\end{bmatrix}
$$

ja

$$
BA = \begin{bmatrix}
1 & 2 & 3 \\
2 & 4 & 6 \\
1 & 2 & 3
\end{bmatrix} \begin{bmatrix}
1 & -1 & 1 \\
-3 & 2 & -1 \\
-2 & 1 & 0
\end{bmatrix} = \begin{bmatrix}
1*1 + 2*-3 + 3*-2 & 1*-1 + 2*2 + 3*1 & 1*1 + 2*-1 + 3*0 \\
2*1 + 4*-3 + 6*-2 & 2*-1 + 4*2 + 6*1 & 2*1 + 4*-1 + 6*0 \\
1*1 + 2*-3 + 3*-2 & 1*-1 + 2*2 + 3*1 & 1*1 + 2*-1 + 3*0
\end{bmatrix} = \begin{bmatrix}
-7 & 7 & -1 \\
-14 & 10 & 2 \\
-7 & 7 & -1
\end{bmatrix}
$$

<!--ADD THESE so the equations render correctly in HTML-->
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-AMS_HTML"></script>
<script type="text/javascript">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [['$', '$'], ['\\(', '\\)']],
            displayMath: [['$$', '$$'], ['\\[', '\\]']]
        }
    });
</script>
