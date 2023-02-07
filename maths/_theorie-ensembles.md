# Théorie des ensembles
Soit $X$ un ensemble, sa notation ensembliste s'écrit sous la forme $$\{expression : règles\}$$

- L'ensemble vide $\{\}$ peut simplement se noter $\emptyset$
- $\{1,5,2\} = \{2,1,5\}$ l'ordre n'a pas d'importance

## Cardinal
Le cardinal d'un ensemble est le nombre d'élément qu'il contient.
Le cardinal d'un ensemble $X$ se note $$|X|=n$$ avec $n$ un nombre.

- $|\emptyset | = 0$
- $|\{\emptyset \}| = 1 \neq |\emptyset |$

## Ensembles usuels
- $\mathbb{N}$ -> naturels
- $\mathbb{Z}$ -> relatifs
- $\mathbb{Q}$ -> rationnels
- $\mathbb{R}$ -> réels
- $\mathbb{C}$ -> complexes

## Produit Cartésien
Soit $A$ et $B$ deux ensembles.
On peut alors les "multiplier" pour faire un nouvel ensemble $A \times B$

On nomme cette opération le **produit Cartésien.**

### Définition 1
Un n-uplet est une liste ordonnée $(x_{1}, \dots, x_{n})$ .
On nomme un 2-uplet un **couple**.

Deux n-uplets $(x_{1}, \dots,x_{n})$ et $(y_{1}, \dots,y_{n})$ sont égaux si et seulement si $x_{i}=y_{i}$ avec $i=1,\dots,n$

### Définition 2
Le produit Cartésien de deux ensembles $A$ et $B$ est un autre ensemble, que l'on note $A \times B$ et définit tel que $$A\times B= \{(x,y): x\in A, y\in B\}$$

De manière générale, $$A_{1}\times \dots \times A_{n}=\{(x_{1}, \dots, x_{n}) : x_{i} \in A_{i} \text{ avec } i=1,\dots ,n\}$$

*exemples* $A\times B$

![[Pasted image 20220727173017.png]]

>[!tip]+ Propriété 1
>Si $A$ et $B$ sont des ensembles finis, alors $$|A\times B| = |A| \cdot |B|$$

### Puissance Cartésienne
Pour un ensemble $A$ quelconque et un entier positif $n$, la **puissance Cartésienne** de $A^{n}$ est $$A^{n}=A\times A \times \dots \times A = \{(x_{1}, \dots, x_{n}) : x_{1}, \dots, x_{n} \in A \}$$

- $|A^{n}|=|A|^{n}$


## Sous-ensemble
### Définition 3
On suppose que $A$ et $B$ sont des ensembles. Si **tous** les éléments de $A$ sont aussi des éléments de $B$, alors $A$ est un sous-ensemble de $B$, que l'on dénote par $A \subseteq B$.

On écrit $A \nsubseteq B$ si $A$ n'est pas un sous-ensemble de $B$
Autrement dit, il est faux de dire que tous les éléments de $A$ sont aussi des éléments de $B$ dans ce cas-là.
Donc $A \nsubseteq B$ veut dire qu'il y a au moins un élément de $A$ qui n'est pas un élément de $B$.

- ($A$ un sous-ensemble de $B$ ) $=$ ( $A$ est inclut dans $B$ ) = ( A est une partie de B )
- $X \subseteq X$ pour tout ensemble $X$

>[!tip]+ Propriété 2
>L'ensemble vide est un sous-ensemble de tous les ensembles, c'est à dire $\emptyset \subseteq B$ pour tout ensemble $B$

>[!tip]+ Propriété 3
>Si un ensemble fini a $n$ éléments, alors il a $2^{n}$ sous-ensembles

## Ensemble des parties d'un ensemble (powerset)

### Définition 4
Si $A$ est un ensemble, alors l'ensemble des parties de $A$ est un autre ensemble, que l'on note $P(A)$ et définit comme étant l'ensemble de **tous** les sous-ensembles de $A$.
Autrement dit, $$P(A)=\{X: X\subseteq A\}$$

>[!tip]+ Propriété 4
>Si $A$ est un ensemble fini, alors $|P(A)|=2^{|A|}$

## Réunion/Intersection/Différence
### Définition 5
On suppose que $A$ et $B$ sont des ensembles.

La **réunion** de $A$ et $B$ est l'ensemble ($A$ union $B$) $$A\cup B=\{x: x\in A \text{ ou } x\in B\}$$ 
L'**intersection** de $A$ et $B$ est l'ensemble ($A$ inter $B$) $$A\cap B=\{x: x\in A \text{ et } x\in B\}$$
La **différence** de $A$ et $B$ est l'ensemble ($A$ moins $B$) $$A-B = \{x: x\in A \text{ et } x\notin B\}$$

- Pour tout ensemble $X,Y$, la réunion et l'intersection sont commutatives, associatives mais pas la différence
- $A\cap(B\cup C)=(A\cap B)\cup (A\cap C)$
- $A\cup(B\cap C)=(A\cup B)\cap (A\cup C)$
- $A\cap(B-C)=(A\cap B) - (A\cap C)$

## Complémentaire
### Définition 6
Soit $A$ un ensemble avec un univers $U$.
Le **complémentaire** de $A$, que l'on note $\overline{A}$, est l'ensemble $$\overline{A}=U-A$$

- univers/ensemble référentiel/ensemble universel -> $U$

## Diagramme de Venn
![[Pasted image 20220808205130.png]]
![[Pasted image 20220808205157.png]]

## Ensembles indexés

On note $$\bigcup_{i=1}^{n}A_{i}=A_{1}\cup A_{2} \cup \dots \cup A_{n}$$ $$\bigcap_{i=1}^{n}A_{i}=A_{1}\cap A_{2} \cap \dots \cap A_{n}$$

ainsi que $$\bigcup_{i=1}^{\infty}A_{i}=A_{1}\cup A_{2} \cup \dots$$
$$\bigcap_{i=1}^{\infty}A_{i}=A_{1}\cap A_{2} \cap \dots $$

### Définition 7/8
Soit $I$ un ensemble d'indices avec $\alpha \in I$.
Si $A_{\alpha}$ est un ensemble pour chaque $\alpha$ de l'ensemble $I\neq \emptyset$, alors $$\bigcup_{\alpha \in I}A_{\alpha}=\{x:x\in A_{\alpha} \text{ pour au moins un ensemble } A_{\alpha} \text{ avec } \alpha \in I\}$$
$$\bigcap_{\alpha \in I}A_{\alpha}=\{x:x\in A_{\alpha} \text{ pour tout ensemble } A_{\alpha} \text{ avec } \alpha \in I\}$$install sxiv fedora

## Divers
N'importe quel sous-ensemble de $\mathbb{N}$ a un plus petit élément.

>[!tip] Algorithme de division
>Soit $a,b$ avec $b>0$ des entiers donnés, il existe des entiers uniques $q$ et $r$ pour lesquels $$a=qb+r$$ avec $0\le r < b$