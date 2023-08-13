---
title: "Equazioni e disequazioni"
date: 2023-08-11
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
Iniziamo facilmente ricordando che un'equazione di primo grado è  della forma:
$$ ax + b = 0 $$
ha una ed una sola soluzione e si calcola semplicemente spostando i membri e gestendo
i segni di conseguenza, invertendoli se si moltiplica o divide per uno stesso fattore. Dunque:
$$ ax = -b; x = -\frac{b}{a}$$
E per le disequazioni? Facile! Abbiamo solo bisogno di cambiare il segno a seconda delle
condizioni dete sopra per l'equazione.

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
Esistono alcune forme *composte polinomiali* che hanno delle soluzioni dimostrate. Diamogli uno sguardo:

*    $(a-b)^2 = a^2+2ab+b^2$ 
*    $(a+b+c)^2 = a^2+b^2+2ab+2ac+2bc$
*    $(a-b+c)^2 = a^2+b^2-2ab+2ac-2bc$
*    $(a+b)^3 = a^3+3a^2b+3a^b2+b^3$
*    $(a-b)^3 = a^3-3a^2b+3a^b2-b^3$
*    $a^2-b^2 = (a-b)(a+b)$
*    $a^3+b^3 = (a+b)(a^2-ab+b^2)$
*    $a^3-b^3 = (a-b)(a^2+ab+b^2)$

Saranno una delle armi migliori in MOLTE circostanze...

---

### Equazioni lineari di ordine superiore al secondo
Se nessun prodotto notevole compare (vedi sopra), allora possiamo **provare** *il mettodo di Ruffini*. Si, provare, in quanto non garantisce un risulato. Dovremmo averee al termine del processo:

  $$P(x)=(x-a)Q(x)$$ con $Q(x)$ polinomio di ordine $P(x)$-1.

1) Abbiamo bisogno di calcolare $f(x)$ substituting $x$ with each divisor of $c$ until we take the result 0 (satisfied equation).
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
Ora hai gli strumenti per risolvere equazioni e disequazioni di ogni ordine e spero
ti possano essere utili 🙂!
Grazie per il tuo tempo dedicatomi e se ti è piaciuto il contenuo continua a seguirmi
nei prossimi post, commenta qui sotto se vuoi, o contattami se hai bisogno di un aiuto specifico. Pubblicherò molti altri contenuti nel mio tempo libero.

A presto 👋,

Lorenzo Pirro