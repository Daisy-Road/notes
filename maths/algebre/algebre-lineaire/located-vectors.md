# Vecteur-positions
On s'intéresse aux vecteurs positions et non formellement aux vecteurs "classique"

Les vecteurs positions sont les représentants de leurs classes.

Un vecteur-position est une paire de points ordonnées ( un segment orienté ).
Soit $\overrightarrow{AB}$ un vecteur-position et soit $C=B-A$.
On a $$\overrightarrow{AB} = \overrightarrow{OC}$$

- $A$ est le point d'origine du vecteur et $B$ est le bout du vecteur
- On note le vecteur $\overrightarrow{OX}$ simplement $X$ pour la simplicité


## Égalité/équivalence/équipollence
Soit $A,B,C,D$ des points, $\overrightarrow{AB}=\overrightarrow{CD}$ si et seulement si $A,B,C,D$ est un parallélograme ( donc $\overrightarrow{AC}=\overrightarrow{BD}$ ).

Soit les vecteurs $\overrightarrow{PQ}$ et $\overrightarrow{MN}$
Ils sont équivalents si et seulement si $$Q-P=N-M$$

Autrement dit, deux vecteurs sont équipollents si et seulement si ils ont la même norme, le même sens, et la même direction

- équivalent $<=>$ équipollent $<=>$ égale

## Parallélisme/colinéarité/sens
Soit les vecteurs $\overrightarrow{PQ}$ et $\overrightarrow{MN}$
Ils sont parallèles si et seulement si $$Q-P=c(N-M)<=> \overrightarrow{PQ}=c\overrightarrow{MN}$$ avec $c$ un nombre positif ou négatif

- $A$ est parallèle à $B$ si et seulement si $a_{1}b_{2} - a_{2}b_{1} = 0$
- Vecteurs parallèles $<=>$ vecteurs colinéaires

### Sens
Ils sont de même sens si et seulement si  $c > 0$
Si $c < 0$ alors ils sont de sens opposés

- sens $\neq$ direction, la direction est déterminée par la droite passant par les points du vecteurs

## Produit scalaire
Soit $A=(a_{1}, ... , a_{n})$ et $B=(b_{1}, ... , b_{n})$ deux vecteurs.
On définit le produit scalaire entre $A$ et $B$ tel que $$A\cdot B=\Sigma_{k=1}^{n}a_{k}b_{k}=||A||\cdot ||B||cos(A,B)$$

---

>[!tip]+ Propriété 1
>Soit $A$ et $B$ deux vecteurs. Le produit scalaire est commutatif.
>On a donc $$A \cdot B=B\cdot A$$

>[!tip]+ Propriété 2
>Si $A,B,C$ sont 3 vecteurs, on a alors ( distributivité ) $$A\cdot (B+C)=A\cdot B + A\cdot C=(B+C)\cdot A$$

>[!tip]+ Propriété 3
>Si $\lambda$ est un scalaire, alors ( associativité ) $$(\lambda A) \cdot B = A\cdot (\lambda B)= \lambda(A\cdot B)$$

>[!tip]+ Propriété 4
>Si $A=O$ est le vecteur nul, alors $A\cdot A=0$.
>Et si $A\neq O$, alors $A\cdot A > 0$

- On pourra noter exclusivement $A\cdot A=A^{2}$
- $(A+B)^{2}=A^{2}+2(A\cdot B)+B^{2}$

>[!tip]+ Propriété 5
>Soit $A$ et $B$ des vecteurs.
>Par définition, ils sont perpendiculaires/orthogonales si et seulement si $$A\cdot B =0$$

## Vecteurs unitaires
Soit $E$ un vecteur unitaire quelconque.
Soit $c$ le composant du vecteur $A$ le long de $E$, on a $$c=A\cdot E$$

- $|c| \le ||A||$
- $c^{2} \le ||A||^{2}$
- Un vecteur $E$ est un vecteur unité si $||E||=1$.
- Soit $a=||A||$, alors $\frac{1}{a}A$ est un vecteur unité

## Norme
On définit la norme d'un vecteur $A$, que l'on note $||A||$, telle que $$||A||=\sqrt{A\cdot A}$$

>[!info]+ Théorème N1
>Soit $x$ un nombre, alors $$||xA||=|x|\cdot ||A||$$

### Perpendicularité
$||A+B||=||A-B||$ si et seulement si $A \cdot B=0$

>[!info]+ Théorème de Pythagore généralisé
>Si deux vecteurs $A$ et $B$ sont orthogonales/perpendiculaires, alors $$||A+B||^{2}=||A||^{2}+||B||^{2}$$

### Projection orthogonale
Soit $A,B$ deux vecteurs et $B\neq \vec{O}$.
Soit $P$ le point sur la droite passant par $\overrightarrow{OB}$ et de sorte que $\overrightarrow{PA}$ est perpendiculaire à $\overrightarrow{OB}$.

![[Pasted image 20220729224952.png]]

>[!tip]+ Définition 1
>Le composant de $A$ le long du vecteur $B$ est le nombre $c=\frac{A\cdot B}{B\cdot B}$

>[!tip]+ Défintion 2
>La projection du vecteur $A$ sur $B$ est le vecteur $cB$.

- Si $B$ est un vecteur unitaire $c=A\cdot B$

---

>[!info]+ Inégalité de Schwartz N2
>Soit $A$ et $B$ deux vecteurs dans $\mathbb{R^{n}}$.
>On a alors $$|A\cdot B| \le ||A||||B||$$

>[!tip]+ Défintion 3
>$$-1\le cos(\theta)=\frac{A \cdot B}{||A||||B||} \le 1$$

>[!info]+ Inégalité triangulaire N3
>Soit $A$ et $B$ des vecteurs.
>On a alors $$||A+B|| \le ||A|| +||B||$$
