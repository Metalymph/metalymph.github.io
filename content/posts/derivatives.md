---
title: "Derivatives"
date: 2023-08-13
draft: true
toc: false
math: true
images:
tags:
  - math
---

- [What is a derivative?](#what-is-a-derivative)
- [Derivatives between two functions: constant, sum, product, ratio](#derivatives-between-two-functions-constant-sum-product-ratio)
- [Min and Max](#min-and-max)
- [Convexity, Concavity and Inflaction points](#convexity-concavity-and-inflaction-points)

### What is a derivative?

A derivative is the limit of the incremental ratio. If this limit exists, the function is derivable in that point!
$$\lim_{h \to 0^-} \frac{f(x_{0}+h)-f(x_{0})}{h} = \lim_{h \to 0^+} \frac{f(x_{0}+h)-f(x_{0})}{h} = c \in \mathbb{R}$$

Again like in [previous lesson](/posts/limits/) for limits, sum, difference, product, ratio and composition of two derivabel functions, is derivable.  
**Note:** If a function is continue in a point, not necessary is derivable in that point! Viceversa if a function is derivable in a point, the function is continue in it.
[Here](https://www.youmath.it/lezioni/analisi-matematica/derivate/212-derivate-di-funzioni-elementari.html "{rel='nofollow'}") a list of simple derivatives for italian readers, but the web is full of this examples.

### Derivatives between two functions: constant, sum, product, ratio
* $\frac{d}{dx}[cf(x)] = cf'(x)$ (*constant*) 
* $\frac{d}{dx}[f(x)+g(x)] = f'(x)+g'(x)$ (*sum*)
* $\frac{d}{dx}[f(x)g(x)] = f'(x)g(x)+f(x)g'(x)$ (*product*)
* $\frac{d}{dx}[\frac{f(x)}{g(x)}] = \frac{f'(x)g(x)-f(x)g'(x)}{g^2(x)}$ (*ratio*)
* $\frac{d}{dx}[g(f(x))] = g'(f(x))f'(x)$ (composed)

### Min and Max


### Convexity, Concavity and Inflaction points
Calculating the second degree derivative and discussing it with $f''(x) > 0$ you will find the signes. Negative sign represents the *concavity* while positive sign the *convessity*.
With $f''(x) = 0$ we find the *inflaction points*.  In these points, the $f(x)$ in not derivable.

**Full function study**
About the full study the best guide with all the steps is [here](https://www.youmath.it/lezioni/analisi-matematica/studio-di-funzioni-grafico.html "{rel='nofollow'}").