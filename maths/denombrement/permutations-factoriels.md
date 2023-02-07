# Factoriel et permutations
## Factoriel
Si $n$ est un entier non-négatif, alors $n!$ est le nombre de listes de longueur $n$ pouvant être faites à partir de $n$ symboles, sans répétitions.
Ainsi, $0!  = 1$ et $1! = 1$. Si $n>1$, alors $$n! =n(n-1)(n-2)\dots \cdot 3 \cdot 2 \cdot 1 = n(n-1)!$$

![[Pasted image 20220924150702.png]]

## Permutation
Une $k$-permutation d'un ensemble $X$ de $n$ éléments est une liste sans répétitions de longueur $k$ faite d'éléments de $X$.
De manière informelle, on considère une $k$-permutation comme un arrangement de $k$ éléments de $X$ sur une ligne.

Le nombre de $k$-permutations de $X$ est noté $P(n,k)$ ou $A^{k}_{n}$, et $$P(n,k)=n(n-1)(n-2)\dots (n-k+1)$$
Si $0 \le k \le n$, alors $$P(n,k)=n(n-1)(n-2)\dots (n-k+1)= \frac{n!}{(n-k)!}$$

- $P(n,n) = n!$

## Fonction gamma
Soit la fonction gamma défini tel que $$\Gamma: [0, +\infty[ \space\longmapsto \mathbb{R}, \space x \longmapsto \Gamma(x)= \int_{0}^{+\infty}t^{x-1}e^{-1}dt$$

On note que si $x\in \mathbb{N}$ alors $\Gamma(x)=(x-1)!$ et donc $\forall n \in [0, +\infty[$ $$n! = \Gamma(n+1)$$


