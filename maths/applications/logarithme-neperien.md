# Logarithme Népérien

Le logarithme népérien ou "naturel" $ln(x)$ est ce que l'on nomme une fonction logarithme, en l'occurence c'est dans ce cas précis la fonction **inverse** de l'exponentiel $e^x$ 

Ce qui nous donne $ln(e^x)=x$

$Df = \space]0; +\infty[$  avec $x \in \mathbb{R}$

![[ln.png]]

---

## Propriétés Algébriques
* $ln(A)$ n'existe que si $A > 0 : \mathbb{R}_{+}^{*}$
* $ln(A) < 0 => A \in$ $] 0 ; 1 [$
* $ln(A) > 0 => A \in$ $]1; +\infty[$
* $ln(1) = 0$
* $ln(A)=ln(B) <=> A = b$
* $ln(AB) = ln(A)+ln(B)$
* $ln\left(\frac{1}{B}\right) = - ln(B)$
* $ln(\frac{A}{B})=ln(A) -ln(B)$
* $ln(\sqrt{A}) = \frac{1}{2}ln(A)$
* $ln(A^{n)}= n\cdot ln(A)$
* $ln(e) = 1$

## Propriétés d'Analyses
* $\lim\limits_{x \to 0} ln(x) = -\infty$
* $\lim\limits_{+\infty} ln(x) = +\infty$
* $\lim\limits_{+\infty} \frac{ln(x)}{x} = 0$
* $\lim\limits_{+\infty} \frac{ln(x)}{x^n} = 0$

---
## Dérivée
* $(ln(x))' = \frac{1}{x}$
* $(ln \circ u(x))' = \frac{u'}{u}$

*Exemple:*
> $ln(x^2+1)'= \frac{u'}{u} = \frac{2x}{x^2+1}$
> $ln(e^{x}+1)= \frac{u'}{u} = \frac{e^x}{e^{x}+1}$