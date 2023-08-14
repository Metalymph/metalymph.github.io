---
title: "Limiti e continuità"
date: 2023-08-13
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
- [Conclusioni](#conclusioni)

### Introductione
Un concetto essentiale dell'analisi matematica e dello studio della funzione in particolare,
è rappresentato dai limiti. Vediamo in questa lezione lampo di che si tratta. Pronti? 

### Continuità

Se $f(x)$ è definita e *continuous* nel segmeento limite che vogliamo calcolare, allora possiamo procedere. Posizioniamo il valore del limite all'interno della funzione e vediamo
se il risultato *L* $\in \mathbb{R}$.
Una funzione è continua in un  punto se il limite da destra e sinistro sono ambedue in $\mathbb{R}$.
Cioè:
$$\lim_{x\to\ x_{0}^-} f(x) = L = \lim_{x\to\ x_{0}^+} f(x)$$
Una funzione è continua in un intervallo (o su tutto $\mathbb{R}$)  se è coninua in tutti i punti dell'intervallo. Importante notare che date due funzioni continue, le seguenti relazioni forniranno a loro volta una funzione continua: $$f(x) g(x),  \frac{f(x)}{g(x)}, f(x)+g(x),  f(x)-g(x),  g(f(x))$$
La discontinuità è data da un valore finito fornito dai due limiti implicati nello stesso punto. Cioè se lo troviamo, allora la funzione è discontinua in quel punto!


### Forme dei limiti
Alcuni limiti sono determinati, cioè, calcolabili *just-in-time*. Altre forme risultano più complesse  e richiedono diversi passaggi, come l'impiego di un bel teorema 😅.
**Forme determinate**

Se *L* è $[\frac{C}{0^+}], [\frac{C}{0^-}], [\frac{\infty}{0}]$, il limite è $\pm\infty$,
se *L* è $[\frac{C}{\infty}], [\frac{\infty}{0}]$, il limite è 0

**Forme indeterminate**

Se *L* è $[\frac{0}{0}], [\frac{\infty}{\infty}], [\infty-\infty], [0^\infty], [0^0], [1^\infty]$ ed altre...il limite deve essere calcolato col metodo *"adeguato"*, non sempre possibile...


### Teoremi rapidi
Esistono alcuni teoremi sui  limiti, utili per calcolare delle forme indeterminate. È importante notare che
**alcuni limiti non esistono** eed è essenziale sapere se il limite esiste ai fini dello *studio della funzione*, che tratteremo in un post successivo.

**Teorema della persistenza del segno**

Se:

$$\lim_{x\to\ x_{0}} f(x) = l \ne 0$$

allora un'intorno di $x_{0}$ esiste, dove **entrambi** $l$ e $f(x)$ sono **entrambi** positive or negative.

**Teorema del confronto**
Se si hanno $ h(x) \le f(x) \le g(x)$ tre funzioni definite in $H$ di $x_{0}$ (non definito in $x_{0}$) allora, se in $H$ è sempre vero che:

$$h(x)  \le f(x) \le g(x) $$

allora, se il limite per $x\to\ x_{0}$ è $l$, il limite per $f(x)$ è **anche** $l$.

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


### Conclusioni

Grazie per il tuo tempo dedicatomi e se ti è piaciuto il contenuo continua a seguirmi
nei prossimi post, commenta qui sotto se vuoi, o contattami se hai bisogno di un aiuto specifico. Pubblicherò molti altri contenuti nel mio tempo libero.

A presto 👋,

Lorenzo Pirro