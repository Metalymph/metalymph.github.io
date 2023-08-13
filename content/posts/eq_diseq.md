---
title: "Equations and disequations"
date: 2023-08-11
toc: false
math: true
images:
tags:
  - math
---


- [Introduction](#introduction)
- [First order linear equation and disequation](#first-order-linear-equation-and-disequation)
- [Second order linear equations](#second-order-linear-equations)
- [Second order linear disequations](#second-order-linear-disequations)
- [Notable products](#notable-products)
- [Third order or more linear equations](#third-order-or-more-linear-equations)
- [Logarithms](#logarithms)
- [Conclusions](#conclusions)


### Introduction
Hi dear readers! Welcome on my first cheatsheet on math analysis.\
Today we'll remember how to calculate a second or third order linear equation or disequation.
We will add a  quick reference on notable products! 🙂\
Let's go!

### First order linear equation and disequation
We start easily remembering that a first order equation in the form:
$$ ax + b = 0 $$
has one and  only one solution and we can find it simply moving the factors and executing basic algebraic operations like this:
$$ ax = -b; x = -\frac{b}{a}$$
And for disequations? Easy! We need only to reverse the sign < to > or viceversa if we apply to both members an algebraic operation
like division or multiplication, et voilà!

---

### Second order linear equations
Given the following assumptions:

$$ ax^2+bx+c, \Delta = b^2 - 4ac $$ for:
1) $\Delta > 0 :$ we have two solutions in $\mathbb{R}$
2) $\Delta = 0 :$ we have two solutions (same point) in $\mathbb{R}$
3) $\Delta < 0 :$ we have **no** solution in $\mathbb{R}$ but in $\mathbb{C}$ instead (not treated).

Main formula: with $$ (with: \Delta>=0); x{_1,_2}=\frac{-b - \sqrt{b^2-4ac}}{2a} $$
**Note**: some equations and disequations of second or third order can be instantly
resolved using [notable products](#notable-products).

---

### Second order linear disequations
For second order disequations, you can resolve the related second order equation and, with $a \ne 0$:

$ax^2+bx+c$ and $\Delta = b^2 - 4ac,$ for:
1) $\Delta > 0 :$ we have two solutions in $\mathbb{R}$, so solution : $x_{1} < x, x > x_{2}$.
2) $\Delta = 0 :$ we have two solutions (same point) in $\mathbb{R}$, so solution is $\forall x \ne x1,x2$ (where $x_{1}= x_{2}$).
3) $\Delta < 0 :$ we have **no** solution in $\mathbb{R}$ but in $\mathbb{C}$ instead, so solution is $\forall x \in \R$.

---

### Notable products
There are some *composed polynomials* which have a fixed (proofed) solutions. Let's take a look:

*    $(a-b)^2 = a^2+2ab+b^2$ 
*    $(a+b+c)^2 = a^2+b^2+2ab+2ac+2bc$
*    $(a-b+c)^2 = a^2+b^2-2ab+2ac-2bc$
*    $(a+b)^3 = a^3+3a^2b+3a^b2+b^3$
*    $(a-b)^3 = a^3-3a^2b+3a^b2-b^3$
*    $a^2-b^2 = (a-b)(a+b)$
*    $a^3+b^3 = (a+b)(a^2-ab+b^2)$
*    $a^3-b^3 = (a-b)(a^2+ab+b^2)$

They will be one of the best weapons for you in MANY circumnstances...

---

### Third order or more linear equations
If no notable product is found (look above), than we can **try** the *Ruffini's Method*. Yes, try, because no result is guaranteed. We shall have at end of the process:

  $$P(x)=(x-a)Q(x)$$ with $Q(x)$ as a polinome with $P(x)$-1 order.

1) We need to calculate $f(x)$ substituting $x$ with each divisor of $c$ until we take the result 0 (satisfied equation).
2) When found, apply the matrix method ([see here](https://www.youmath.it/lezioni/algebra-elementare/polinomi/272-la-regola-di-ruffini.html)). The result **must be** 0 for the known term.
3) Write the result in the given form and apply the method again if necessary (but first, see if you have a [Notable products](#notable-products)).

### Logarithms
The last sheet i want to remember is about logarithms. Here a set of rules for them.

*    $a^{\log{_a}{b}} = b$ (definition)
*    $\log{_a}{b^c} = c\log{_a}{b}$ (Exponent)
*    $\log{_a}{bc} = \log{_a}{b}+\log{_a}{c}$ (Product)
*    $\log{_a}{\frac{b}{c}} = \log{_a}{b}-\log{_a}{c}$ (Quotient)
*    $\log{_a}{b} = \frac{\log{_c}{b}}{\log{_c}{a}}$ (Base conversion)
*    $\log{_a}{b} = \frac{1}{\log{_b}{a}}$ (Inversion)

### Conclusions
Now you have a good set of sheets to resolve many equations and disequations and i hope it will be useful 🙂!
Thanks you reading and if you like my contents, follow me on this simple, comment below, site or contact me if you need a specific help. I will publish more contents based also on the comments according with my time.

See you at soon 👋,

Lorenzo Pirro