# mathcheatsheet
A simple math cheatsheet for fast search 🔍 

### Index
- [mathcheatsheet](#mathcheatsheet)
    - [Index](#index)
    - [Disequations](#disequations)
    - [Second order linear equations](#second-order-linear-equations)
    - [Notable products](#notable-products)
    - [Third order or more linear equations](#third-order-or-more-linear-equations)
    - [Logarithms and properties](#logarithms-and-properties)
    - [Limits and theorems](#limits-and-theorems)
    - [Function study](#function-study)

### Disequations

### Second order linear equations
given the following assumptions:

$ax^2+bx+c$ $\Delta = b^2 - 4ac, for:$
1) $\Delta > 0 :$ we have two solutions in $\R$
2) $\Delta = 0 :$ we have two solutions (same point) in $\R$
3) $\Delta < 0 :$ we have **no** solution in $\R$

Main formula, with $\Delta>=0$: $$x{_1,_2}=\frac{-b - \sqrt{b^2-4ac}}{2a}$$

### Notable products
*    $(a-b)^2 = a^2+2ab+b^2$ 
*    $(a+b+c)^2 = a^2+b^2+2ab+2ac+2bc$
*    $(a-b+c)^2 = a^2+b^2-2ab+2ac-2bc$
*    $(a+b)^3 = a^3+3a^2b+3a^b2+b^3$
*    $(a-b)^3 = a^3-3a^2b+3a^b2-b^3$
*    $a^2-b^2 = (a-b)(a+b)$
*    $a^3+b^3 = (a+b)(a^2-ab+b^2)$
*    $a^3-b^3 = (a-b)(a^2+ab+b^2)$

### Third order or more linear equations
If no notable product is found, than we can **try** *Ruffini's Method*. We shall have at end of the process:

  $$P(x)=(x-a)Q(x)$$ with $Q(x)$ as a polinome with $P(x)$-1 order.

1) We need to calculate $f(x)$ substituting $x$ with each divisor of $c$ until we take the result 0 (satisfied equation).
2) When found, apply the matrix method (see a reference). The result **must be** 0 for the known term.
3) Write the result in the given form and apply the method again if necessary (but first, see if you have a *notable product*).

---

### Logarithms and properties
*    $a^{\log{_a}{b}} = b$ (definition)
*    $\log{_a}{b^c} = c\log{_a}{b}$ (Exponent)
*    $\log{_a}{bc} = \log{_a}{b}+\log{_a}{c}$ (Product)
*    $\log{_a}{\frac{b}{c}} = \log{_a}{b}-\log{_a}{c}$ (Quotient)
*    $\log{_a}{b} = \frac{\log{_c}{b}}{\log{_c}{a}}$ (Base conversion)
*    $\log{_a}{b} = \frac{1}{\log{_b}{a}}$ (Inversion)

---

### Limits and theorems

If $f(x)$ is defined and continuous in the limit segment we want to calculate, than we can proceed. Put the limit value inside function and see if the result is an *L* $\in \R$.

**Determinated forms**

If *L* is $[\frac{C}{0^+}], [\frac{C}{0^-}], [\frac{\infin}{0}]$, the limit is $\plusmn\infin$,
if *L* is $[\frac{C}{\infin}], [\frac{\infin}{0}]$, the limit is 0

**Undeterminated forms**

If *L* is $[\frac{0}{0}], [\frac{\infin}{\infin}], [\infin-\infin], [0^\infin], [0^0], [1^\infin]$ and more...the limit must be calculated with the right theorem.


---

### Function study

