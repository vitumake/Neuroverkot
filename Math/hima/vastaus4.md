# Kotitehtavat_4.pdf

## 1. Laske derivaatta f ′(x), kun f (x)

### a) $f(x) = x^2 e^{2x}$

$
\begin{aligned}
f(x) &= x^2 e^{2x} \\
u(x) &= x^2, \quad v(x) = e^{2x} \\
u'(x) &= 2x, \quad v'(x) = 2e^{2x} \\
f'(x) &= u'(x)v(x) + u(x)v'(x) \\
f'(x) &= 2x e^{2x} + x^2 \cdot 2 e^{2x} \\
&= 2x e^{2x} + 2x^2 e^{2x} \\
&= 2x(1 + x)e^{2x}
\end{aligned}
$

### b) $f(x) = (2x + 4)^5$

$
\begin{aligned}
f(x) &= (2x + 4)^5 \\
u(x) &= 2x + 4, \quad n = 5 \\
f'(x) &= n \cdot u(x)^{n-1} \cdot u'(x) \\
u'(x) &= 2 \\
f'(x) &= 5(2x + 4)^4 \cdot 2 \\
&= 10(2x + 4)^4
\end{aligned}
$

### c) $f(x) = \frac{1}{1+e^-(ax+b)}$

$
\begin{aligned}
f(x) &= \frac{1}{1+e^-(ax+b)} \\
u(x) &= 1+e^-(ax+b) \\
f'(x) &= \frac{0 \cdot u(x) - 1 \cdot u'(x)}{u(x)^2} \\
u'(x) &= -e^-(ax+b) \cdot a \\
f'(x) &= \frac{ae^-(ax+b)}{(1+e^-(ax+b))^2}
\end{aligned}
$

## 2. Laske derivaatta f ′(x), kun f (x)

### a) $10sin(x^2)$

$
\begin{aligned}
f(x) &= 10sin(x^2) \\
u(x) &= x^2 \\
f'(x) &= 10 \cdot cos(u(x)) \cdot u'(x) \\
u'(x) &= 2x \\
f'(x) &= 10 \cdot cos(x^2) \cdot 2x \\
&= 20x \cdot cos(x^2)
\end{aligned}
$

### b) $e^{cosx}$

$
\begin{aligned}
f(x) &= e^{cosx} \\
u(x) &= cosx \\
f'(x) &= e^{u(x)} \cdot u'(x) \\
u'(x) &= -sinx \\
f'(x) &= e^{cosx} \cdot (-sinx) \\
f'(x) &= -sinx \cdot e^{cosx}
\end{aligned}
$

### c) $ln(1-x^2)$

$
\begin{aligned}
f(x) &= ln(1-x^2) \\
u(x) &= 1-x^2 \\
f'(x) &= \frac{1}{u(x)} \cdot u'(x) \\
u'(x) &= -2x \\
f'(x) &= \frac{-2x}{1-x^2}
\end{aligned}
$

## 3. Laske funktion $f$ osittaisderivaatat, kun $f(x, y)$

### a) $xy^2 + 3x$

$
\begin{aligned}
f(x, y) &= xy^2 + 3x \\
f_x(x, y) &= \frac{\partial}{\partial x}(xy^2 + 3x) \\
&= y^2 + 3 \\
f_y(x, y) &= \frac{\partial}{\partial y}(xy^2 + 3x) \\
&= 2xy
\end{aligned}
$

### b) $ln\frac{x}{y}$

$
\begin{aligned}
f(x, y) &= ln\frac{x}{y} \\
f_x(x, y) &= \frac{\partial}{\partial x} \left( ln(x) - ln(y) \right) \\
&= \frac{1}{x} \\
f_y(x, y) &= \frac{\partial}{\partial y} \left( ln(x) - ln(y) \right) \\
&= -\frac{1}{y}
\end{aligned}
$

### c) $\frac{sinx}{cosy}$

$
\begin{aligned}
f(x, y) &= \frac{sinx}{cosy} \\
f_x(x, y) &= \frac{\partial}{\partial x} \left( \frac{sinx}{cosy} \right) \\
&= \frac{cosx \cdot cosy}{cosy \cdot cosy} \\
&= \frac{cosx}{cosy} \\
f_y(x, y) &= \frac{\partial}{\partial y} \left( \frac{sinx}{cosy} \right) \\
&= \frac{sinx \cdot siny}{cos^2y} \\
&= -\frac{sinx \cdot siny}{cos^2y}
\end{aligned}
$

## 4. Laske funktion $f$ gradientti $\nabla f$, kun

### a) $f(x, y) = 2x^2y-5y+4xy^2$

$
\begin{aligned}
f(x, y) &= 2x^2y-5y+4xy^2 \\
_xf(x, y) &= 4xy + 4y^2 \\
_yf(x, y) &= 2x^2 - 5 + 8xy \\
\nabla f(x, y) &= _xf(x, y) \hat{i} + _yf(x, y) \hat{j} \\
&= (4xy + 4y^2) \hat{i} + (2x^2 - 5 + 8xy) \hat{j}
\end{aligned}
$

$
\begin{aligned}
\nabla f(2,1) &= (4 \cdot 2 \cdot 1 + 4 \cdot 1^2) \hat{i} + (2 \cdot 2^2 - 5 + 8 \cdot 2 \cdot 1) \hat{j} \\
&= 8 \hat{i} + (8 - 5 + 16) \hat{j} \\
&= 8 \hat{i} + 19 \hat{j}
\end{aligned}
$

### b) $f(x, y) = \sqrt{x^2 + y^2}$

$
\begin{aligned}
f(x, y) &= \sqrt{x^2 + y^2} \\
_xf(x, y) &= \frac{1}{2\sqrt{x^2 + y^2}} \cdot 2x \\
&= \frac{x}{\sqrt{x^2 + y^2}} \\
_yf(x, y) &= \frac{1}{2\sqrt{x^2 + y^2}} \cdot 2y \\
&= \frac{y}{\sqrt{x^2 + y^2}} \\
\nabla f(x, y) &= \frac{x}{\sqrt{x^2 + y^2}} \hat{i} + \frac{y}{\sqrt{x^2 + y^2}} \hat{j}
\end{aligned}
$

$
\begin{aligned}
\nabla f(2,1) &= \frac{2}{\sqrt{2^2 + 1^2}} \hat{i} + \frac{1}{\sqrt{2^2 + 1^2}} \hat{j} \\
&= \frac{2}{\sqrt{5}} \hat{i} + \frac{1}{\sqrt{5}} \hat{j} \\
&= \frac{2}{\sqrt{5}} \hat{i} + \frac{1}{\sqrt{5}} \hat{j}
\end{aligned}
$

## 5. Laske funktion $f$ gradientti $\nabla f$, kun

$f(x, y, z) = x^3 + 3xy^2 - 5y^2z+2z^4$

$
\begin{aligned}
f(x, y, z) &= x^3 + 3xy^2 - 5y^2z+2z^4 \\
_xf(x, y, z) &= 3x^2 + 3y^2 \\
_yf(x, y, z) &= 6xy - 10yz \\
_zf(x, y, z) &= -5y^2 + 8z^3 \\
\nabla f(x, y, z) &= (3x^2 + 3y^2) \hat{i} + (6xy - 10yz) \hat{j} + (-5y^2 + 8z^3) \hat{k}
\end{aligned}
$

$
\begin{aligned}
\nabla f(1,3,0) &= (3 \cdot 1^2 + 3 \cdot 3^2) \hat{i} + (6 \cdot 1 \cdot 3 - 10 \cdot 3 \cdot 0) \hat{j} + (-5 \cdot 3^2 + 8 \cdot 0^3) \hat{k} \\
&= 12 \hat{i} + 18 \hat{j} - 45 \hat{k}
\end{aligned}
$

<!--ADD THESE so the equations render correctly in HTML-->
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config">
    MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });
</script>