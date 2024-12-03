# Kotitehtävät 6

## Teht 1

Aktivaatiot ai,i = 1,2,3, lasketaan seuraavasti:

$
z_1 = w_1x + b_1, \\
a_1 = g(z_1), \\
z_2 = w_2a_1 + b_2, \\
a_2 = g(z_2)
$

Jokaisessa kerroksessa käytetään aktivaatiofunktiona sigmoid-funktiota.

$
g(x) = \frac{1}{1 + e^{-x}}
$

Laske yhdistetyn funktion derivointisäännön eli ketjusäännön avulla
derivaatat

$
\frac{\partial a_2}{\partial w_2}
$

$
\frac{\partial a_2}{\partial w_2} = \frac{\partial a_2}{\partial z_2} \frac{\partial z_2}{\partial w_2}
$

$
\frac{\partial a_2}{\partial z_2} = g'(z_2)
$

$
g'(x) = g(x)(1 - g(x))
$

$
\frac{\partial a_2}{\partial z_2} = g(z_2)(1 - g(z_2))
$

$
\frac{\partial z_2}{\partial w_2} = a_1
$

$
\frac{\partial a_2}{\partial w_2} = \frac{\partial a_2}{\partial z_2} \frac{\partial z_2}{\partial w_2} = g(z_2)(1 - g(z_2))a_1
$

---

$
\frac{\partial a_2}{\partial w_1}
$

$
\frac{\partial a_2}{\partial w_1} = \frac{\partial a_2}{\partial z_2} \frac{\partial z_2}{\partial a_1} \frac{\partial a_1}{\partial z_1} \frac{\partial z_1}{\partial w_1}
$

$
\frac{\partial a_2}{\partial z_2} = g'(z_2)
$

$
\frac{\partial z_2}{\partial a_1} = w_2
$

$
\frac{\partial a_1}{\partial z_1} = g'(z_1)
$

$
\frac{\partial z_1}{\partial w_1} = x
$

$
\frac{\partial a_2}{\partial w_1} = \frac{\partial a_2}{\partial z_2} \frac{\partial z_2}{\partial a_1} \frac{\partial a_1}{\partial z_1} \frac{\partial z_1}{\partial w_1} = g(z_2)(1 - g(z_2))w_2g(z_1)(1 - g(z_1))x
$

<!--ADD THESE so the equations render correctly in HTML-->
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config">
    MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });
</script>