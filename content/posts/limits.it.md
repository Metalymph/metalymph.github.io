---
title: "Limiti e continuità"
date: 2023-08-13
draft: true
toc: false
math: true
images:
tags:
  - math
---

- [Introductione](#introductione)
- [Continuità](#continuità)
- [Forme dei limiti](#forme-dei-limiti)
- [Teoremi rapidi](#teoremi-rapidi)

### Introductione
Un concetto essentiale dell'analisi matematica e dello studio della funzione in particolare,
è rappresentato dai limiti. Vediamo in questa lezione lampo di che si tratta. Pronti? 

### Continuità

If $f(x)$ is defined and *continuous* in the limit segment we want to calculate, than we can proceed. Put the limit value inside function and see if the result is an *L* $\in \mathbb{R}$.
A function is continue in a point if the limit from left and right gives the same value in $\mathbb{R}$.
That is:
$$\lim_{x\to\ x_{0}^-} f(x) = L = \lim_{x\to\ x_{0}^+} f(x)$$
A function is continue in a range (or the full $\mathbb{R}$)  if it's continue in all the range's points. Important to note that given two functions, the following operations give an other continue function: $$f(x) g(x),  \frac{f(x)}{g(x)}, f(x)+g(x),  f(x)-g(x),  g(f(x))$$
Discontinuity is given by a finite value from the two limits in the same point.


### Forme dei limiti
Some limits are deetermined, that is, can be calculated *just-in-time*. Other forms are more complex
and require the use of a theorem or more passes.
**Forme determinate**

If *L* is $[\frac{C}{0^+}], [\frac{C}{0^-}], [\frac{\infty}{0}]$, the limit is $\pm\infty$,
if *L* is $[\frac{C}{\infty}], [\frac{\infty}{0}]$, the limit is 0

**Forme indeterminate**

If *L* is $[\frac{0}{0}], [\frac{\infty}{\infty}], [\infty-\infty], [0^\infty], [0^0], [1^\infty]$ and more...the limit must be calculated with the right theorem, sometimes challenging...


### Teoremi rapidi
There are some theorems related to limits, useful to calculate some indeterminated forms. Is important to note that
**some limits don't exist** and is essential to know if a limit exists in the [function study](#function-study).

**Teorema della persistenza del segno**

Se:

$$\lim_{x\to\ x_{0}} f(x) = l \ne 0$$

than, a surrounding area of $x_{0}$ exists, where **both** $l$ and $f(x)$ are **both** positive or both negative.

**Teorema del confronto**
If you have $ h(x) \le f(x) \le g(x)$ three functions defined in the surrounding area $H$ of $x_{0}$ (not defined in $x_{0}$) so, if in $H$ is always valid:

$$h(x)  \le f(x) \le g(x) $$

than, if the limit for $x\to\ x_{0}$ is $l$, the limit for $f(x)$ is **also** $l$.

**Teorema di unicità del limite**
Se $f(x)$ ha limite $l$ per $x\to\ x_{0}$, allora $l$ è **unico**.

**Limiti notevoli**
 There are some limits for whom the existence of limit and proofness is battle-tested. They are known and they are all $\frac{0}{0}$ cases, but not the last (Neplero's number, $1^{\infty} $). 
 *N.B:* Non tutti i casi sono descritti.

*    **Logaritmica**, con $a > 0$ e $a \ne 1$:
    $$\lim_{x\to\ 0}\frac{log_{a}(1+x)}{x} = \frac{1}{ln(a)};  \lim_{f(x) \to 0}\frac{log_{a}(1+f(x))}{f(x)} = \frac{1}{ln(a)}$$
quindi, sia $a = e$:
    $$\lim_{x\to\ 0}\frac{ln(1+x)}{x} = 1;  \lim_{f(x) \to 0}\frac{ln(1+f(x))}{f(x)} = 1$$  

*    **Exponentiale**, with $a > 0$:
    $$\lim_{x\to\ 0}\frac{a^x-1}{x} = ln(a);  \lim_{f(x) \to 0}\frac{a^{f(x)}-1}{f(x)} = ln(a)$$

quindi, sia $a = e$:
    $$\lim_{x\to\ 0}\frac{e^x-1}{x} = 1;  \lim_{f(x) \to 0}\frac{e^{f(x)}-1}{f(x)} = 1$$

*    **Potenza con differenza** con $c \in \mathbb{R}$:
    $$\lim_{x\to\ 0}\frac{(1+x)^c-1}{x} = c;  \lim_{f(x) \to 0}\frac{(1+f(x))^c-1}{f(x)} = c$$

*    **Numero di Neplero**
    $$\lim_{x\to\ \pm\infty}(1+\frac{1}{x})^x = e;  \lim_{f(x) \to \pm\infty}(1+\frac{1}{f(x)})^{f(x)} = e$$


## Conclusioni

Grazie per il tuo tempo dedicatomi e se ti è piaciuto il contenuo continua a seguirmi
nei prossimi post, commenta qui sotto se vuoi, o contattami se hai bisogno di un aiuto specifico. Pubblicherò molti altri contenuti nel mio tempo libero.

A presto 👋,

Lorenzo Pirro