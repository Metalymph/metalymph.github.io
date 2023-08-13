---
title: "Equazioni e disequazioni"
date: 2023-08-11
draft: true
toc: false
math: true
images:
tags:
  - math
---


- [Introduzione](#introduzione)
- [Equazioni e disequazioni lineari del primo ordine](#equazioni-e-disequazioni-lineari-del-primo-ordine)
- [Equazioni lineari del secondo ordine](#equazioni-lineari-del-secondo-ordine)
- [Disequazioni lineari del secondo ordine](#disequazioni-lineari-del-secondo-ordine)
- [Prodotti notevoli](#prodotti-notevoli)
- [Equazioni lineari di ordine superiore al secondo](#equazioni-lineari-di-ordine-superiore-al-secondo)
- [Logaritmi](#logaritmi)
- [Conclusioni](#conclusioni)


### Introduzione
Salve caro lettore! Benvenuto sul mio memorandum sull'analisi matematica.\
Oggi ricorderemo per cominciare, come calcolare un'equazione o disequazione lineare generica,
di qualunque ordine essa sia. Gli argomenti potrebbero sembrare futili, ma, tutto
dipende da  come questi vengono esposti 🙂. Cominciamo!

### Equazioni e disequazioni lineari del primo ordine
We start easily remembering that a first order equation in the form:
$$ ax + b = 0 $$
has one and  only one solution and we can find it simply moving the factors and executing basic algebraic operations like this:
$$ ax = -b; x = -\frac{b}{a}$$
And for disequations? Easy! We need only to reverse the sign < to > or viceversa if we apply to both members an algebraic operation
like division or multiplication, et voilà!

---

### Equazioni lineari del secondo ordine
Date le seguenti assunzioni:

$$ ax^2+bx+c, \Delta = b^2 - 4ac $$ per:
1) $\Delta > 0 :$ abbiamo due soluzioni in $\mathbb{R}$
2) $\Delta = 0 :$ abbiamo due soluzioni (coincidenti) in $\mathbb{R}$
3) $\Delta < 0 :$ **non** abbiamo solutioni in $\mathbb{R}$ bensì in $\mathbb{C}$ invece (non trattate qui).

Formula: $$ (sia: \Delta>=0); x{_1,_2}=\frac{-b - \sqrt{b^2-4ac}}{2a} $$
**Note**: alcune equazioni e disequazioni di ssecondo e terzo grado possono essere risolte rapidamente
tramite l'utilizzo dei [notable products](#notable-products). Li vedremo tra poco!

---

### Disequazioni lineari del secondo ordine
Per le disequazioni di secondo grado, si può risolvere l'equazione di secondo grado *associata*. Sia $a \ne 0$:

$ax^2+bx+c$ e $\Delta = b^2 - 4ac,$ per:
1) $\Delta > 0 :$ abbiamo due soluzioni in $\mathbb{R}$, quindi la soluzione è : $x_{1} < x, x > x_{2}$.
2) $\Delta = 0 :$ abbiamo due soluzioni (coincidenti) in $\mathbb{R}$, quindi la soluzione è $\forall x \ne x1,x2$ (dove $x_{1}= x_{2}$).
3) $\Delta < 0 :$ **non** abbiamo solutioni in $\mathbb{R}$ bensì in $\mathbb{C}$ invece, quindi la soluzione è $\forall x \in \R$. Il perché viene rimandato ad un'altro post in futuro.

---

### Prodotti notevoli
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

### Equazioni lineari di ordine superiore al secondo
If no notable product is found (look above), than we can **try** the *Ruffini's Method*. Yes, try, because no result is guaranteed. We shall have at end of the process:

  $$P(x)=(x-a)Q(x)$$ with $Q(x)$ as a polinome with $P(x)$-1 order.

1) We need to calculate $f(x)$ substituting $x$ with each divisor of $c$ until we take the result 0 (satisfied equation).
2) When found, apply the matrix method ([see here](https://www.youmath.it/lezioni/algebra-elementare/polinomi/272-la-regola-di-ruffini.html)). The result **must be** 0 for the known term.
3) Write the result in the given form and apply the method again if necessary (but first, see if you have a [Notable products](#notable-products)).

### Logaritmi
L'ultimo randez-vouz che volevo trattare riguarda i logaritmi. Ecco un insieme di regole:

*    $a^{\log{_a}{b}} = b$ (definitione)
*    $\log{_a}{b^c} = c\log{_a}{b}$ (esponente)
*    $\log{_a}{bc} = \log{_a}{b}+\log{_a}{c}$ (prodotto)
*    $\log{_a}{\frac{b}{c}} = \log{_a}{b}-\log{_a}{c}$ (quoziente)
*    $\log{_a}{b} = \frac{\log{_c}{b}}{\log{_c}{a}}$ (cambio di base)
*    $\log{_a}{b} = \frac{1}{\log{_b}{a}}$ (inversione)

### Conclusioni
Now you have a good set of sheets to resolve many equations and disequations and i hope it will be useful 🙂!
Thanks you reading and if you like my contents, follow me on this simple, comment below, site or contact me if you need a specific help. I will publish more contents based also on the comments according with my time.

A presto 👋,

Lorenzo Pirro