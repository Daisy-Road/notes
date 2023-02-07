# Permutations
Soit l'ensemble $J_{n}=\{k\in \mathbb{N} : 1\le k \le n\}$
On nomme une **permutation** de $J_{n}$, une application $$\sigma : J_{n} \longmapsto J_{n}$$

ayant cette propriété,

>[!tip] Propriété 1
>Si $i,j$ sont dans $J_{n}$ et $i \neq j$, alors $\sigma(i) \neq \sigma(j)$

Donc les images de $J_{n}$ sont ses propres éléments mais dans un ordre différent

On note une permutation $\sigma$ $$\begin{bmatrix} 1 & 2 & 3 & \dots & n \\ \sigma(1) & \sigma(2) & \sigma(3) & \dots & \sigma(n) \end{bmatrix}$$

- Le nombre de permutations de $J_{n}$ est égale à $n!$

## Produits
Si $\sigma$ et $\sigma'$ sont des permutations, on note leur composée $\sigma\sigma'$
On appelle cette composition le produit de $\sigma$ et $\sigma'$

- L'égalité $\sigma\sigma'=\sigma'\sigma$ n'est pas toujours vraie
- Multiplier une permutation par une transposition augmente ou diminue de $1$ son nombre d'orbites

## Réciproques
Soit $\sigma$ est une permutation de $J_{n}$
Pour chaque élément de $J_{n}$, il existe un unique élément $i$ de sorte que $$\sigma(i)=j$$

On définit alors la **permutation réciproque** de $\sigma$, comme étant la permutation $\sigma^{-1}$ de sorte que $$\sigma\sigma^{-1}=\sigma^{-1}\sigma=I$$

On a donc $\sigma(i)=j$ si et seulement si $\sigma^{-1}(j)=i$

## Transpositions
Une transposition $\tau$ est une permutation qui échange deux nombres distincts $i \neq j$ tout en laissant les autres nombres fixés.

*exemples*

La permutation $$\sigma = \begin{bmatrix} 1 & 2 & 3 & 4 \\ 1 & 3 & 2 & 4 \end{bmatrix}$$
est une transposition qui échange $2$ et $3$ en laissant $1$ et $4$ fixes.

>[!tip]+ Propriété 2
>Si $\tau$ est une transposition, alors $\tau^{2}=I$, donc $\tau^{-1}=\tau$

>[!info]+ Théorème 1
>Toutes les permutations de $J_{n}$ peuvent s'exprimer comme un produit de transpositions.

**exemples**
![[Pasted image 20220815194746.png]]

## Signes/Signatures
>[!info]+ Théorème 2
>Soit $\sigma$ une permutation de $J_{n}$. 
>Dans toute expression de $\sigma$ comme un produit de transpositions, le nombre de transpositions qui occurent dans ce produit est soit toujours **pair**, soit toujours **impair**.

Si $\sigma= \tau_{1}\dots\tau_{m}$ est l'expression de $\sigma$ s'écrivant comme un produit de transpositions, alors on nomme $$(-1)^{m}$$ le **signe** de $\sigma$.
Ce signe est $1$ ou $-1$ en fonction de si $m$ est pair ou impair.
$1$ correspond à une **permutation pair** et $-1$ correspond à une **permutation impair**.

## Orbites

![[Pasted image 20220815171906.png]]

On nomme l'ensemble contenant $$i, \sigma(i), \sigma^{2}(i), \dots, \sigma^{k-1}(i)$$ une **orbite** de $\sigma$, plus précisément l'orbite appartenant à $i$.

L'effet de $\sigma$ sur cette orbite est dénoté par $$\gamma =[i, \sigma(i), \sigma^{2}(i), \dots, \sigma^{k-1}(i)]$$ et est appelé le **cycle** de l'orbite.

On nomme $k$, la période de $i$ par $\sigma$ ou la période du cycle, ou bien la longueur du cycle.

>[!tip]+ Propriété 3
>Soit $k$ le plus petit entier positif de sorte que $\sigma^{k}(i)=i$
>Alors, les nombres $$i, \sigma(i), \sigma^{2}(i), \dots, \sigma^{k-1}(i)$$ sont distincts.

>[!info]+ Théorème 3
>Si $a,b$ sont des éléments de $J_{n}$ et si $\sigma$ est une permutation de $J_{n}$, alors les orbites à laquelles appartiennent $a$ et $b$ coincïde ou bien n'ont aucun élément en commun, i.e disjoints

### Décomposition orbitale
Soit $S$ une orbite de $\sigma$ et soit $i$ un élément de $S$. On note le cycle de cette orbite par $$\gamma=[i,\sigma(i),\dots,\sigma^{k-1}(i)]$$

Si $S_{1},\dots, S_{m}$ sont les orbites disjointes de $\sigma$, alors elles ont les cycles $\gamma_{1},\dots,\gamma_{m}$ correspondant et note symboliquement $$\sigma=\gamma_{1}\gamma_{2}\dots\gamma_{m}$$

---
>[!tip]+ Propriété 4
>Si $\sigma$ a $k$ orbites, alors $\tau\sigma$ a $k\pm 1$ orbites.

>[!info]+ Théorème 4
>Soit $\sigma$ une permutation de $J_{n}$ et on suppose que $\sigma$ a $k$ orbites.
>
>Si $n-k$ est pair, alors $\sigma$ est une permutation pair.
>Si $n-k$ est impair, alors $\sigma$ est une permutation impair.

>[!tip]+ Propriété 5
>Le nombre de permutations impairs de $J_{n}$ pour $n\ge 2$ est égale à son nombre de permutations pairs.

