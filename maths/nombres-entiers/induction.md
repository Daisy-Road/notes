# Induction


## Axiome
Soit $A(n)$ une assertion à propos de l'entier $n$
Si on veut prouver que cela est vraie pour tous les $n$, il suffit de prouver:

>[!tip]- Ind 1 
>L'assertion $A(1)$ est vraie

>[!tip]+ Ind 2
>On suppose que l'assertion est prouvé pour tous les entiers positifs $\leq n$, on le prouve ensuite pour $n+1$, c.a.d prouver que $A(n+1)$ est vraie.


La somme des entiers naturels de $1$ à $n$ s'écrit $\sum_{k=1}^{n}k = \frac{n(n+1)}{2}$

## Coefficient binomial
On appelle le coefficient binomial le nombre de façon de choisir un sous-ensemble de $k$ éléments parmi un ensemble de $n$ éléments, on le note $C_{k}^{n}$ ou bien $\begin{pmatrix} n \\ k \end{pmatrix}$ qui se lit "$k$ parmi $n$".
$$C_{k}^{n}=\frac{n!}{k!(n-k)!}$$


On peut écrire les identités remarquables tel que $(x+y)^{n}= \sum_{k=0}^{n} C_{k}^{n}x^{k}y^{n-k}$


## Résultats de sommes utiles
- $\sum_{k=1}^{n} k = \frac{n(n+1)}{2}$
- $\sum_{k=1}^{n} k^{2} = \frac{1}{6} \cdot n(n+1)(2n+1)$
- $\sum_{k=1}^{n} k^{3} = [\frac{n(n+1)}{2}]^{2}$
- $\sum_{k=1}^{n} (2k - 1) = n^{2}$
- $\sum_{k=1}^{n} (2k - 1)^{2} = \frac{1}{3} \cdot (4n^{3} - n)$

## Divers
Soit $E$ et $F$ des ensembles avec $n$ et $m$ éléments respectivement.
Le nombre d'application allant de $E$ vers $F$ est de $m^{n}$

![[Pasted image 20221012145047.png]]