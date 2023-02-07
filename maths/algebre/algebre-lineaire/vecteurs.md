# Vecteurs du plan et de l'espace
$\overrightarrow{AB}=\overrightarrow{CD}$ si et seulement si $A,B,C,D$ est un parallèlograme

>[!info]+ Propriétés d'un vecteur
>![[Pasted image 20220909154355.png]]

- $\overrightarrow{AA}=\overrightarrow{O}$
- $\lambda \vec{u}$ est un multiple du vecteur $\vec{u}$
- $\overrightarrow{AB}$ et $\overrightarrow{BA}=-\overrightarrow{AB}$ sont dit opposés 
- $||\lambda\vec{u}||=|\lambda| \times ||\vec{u}||$

---

>[!tip]+ Colinéarité
>Deux vecteurs non-nuls sont dit colinéaires s'ils ont la même direction.
>Dans ce cas, il existe un réel $\lambda$ tel que $\vec{u}=\lambda\vec{u}$
>
>- $\overrightarrow{O}$ est par définition colinéaire à tous les autres vecteurs


>[!tip]+ Relation de Chalse
>Pour tout points $A,B,C$, $$\overrightarrow{AB} + \overrightarrow{BC} = \overrightarrow{AC}$$
il est 
## Base

![[Pasted image 20220913133423.png]]

## Produit scalaire
Le produt scalaire entre deux vecteurs est un nombre réel défini par la formule $$\vec{u}\cdot\vec{v}= \Vert\vec{u}\Vert \Vert\vec{v} \Vert cos(\theta)$$

Deux vecteurs sont orthogonaux si et seulement si leur produit scalaire est nul.

Dans une base **orthonormée**, 
$$\begin{pmatrix} x \\y \\ z \end{pmatrix} \cdot \begin{pmatrix} x' \\y' \\ z' \end{pmatrix}=xx'+yy'+zz'$$

- Le vecteur $(s,t)$ est orthogonal au vecteur $(-t, s)$ car leur produit scalaire est nul
- Si le produit scalaire est inférieur à 0, alors l'angle est obtus, si il est supérieur à 0, l'angle est aigu

---

>[!tip]+ Commutativité
>Pour tout vecteurs $\vec{u}$, $\vec{v}$, on a $$\vec{u}\cdot\vec{v}=\vec{v}\cdot\vec{u}$$

>[!tip]+ Associativité
>Pour tout vecteurs $\vec{u}$, $\vec{v}$, et tout réel $\lambda$, on a $$(\lambda\vec{u}) \cdot\vec{v}=\lambda(\vec{u}\cdot\vec{v})$$

>[!tip]+ Distributivité
>Pour tout vecteurs $\vec{u},\vec{v},\vec{w}$, on a $$(\vec{u}+\vec{v})\cdot \vec{w}= (\vec{u}\cdot\vec{w}) + (\vec{v}\cdot\vec{w})$$

## Projeté orthogonale
Soit $\vec{i}$ un vecteur unitaire, et $\vec{u}$ un vecteur quelconque. On note $\vec{u}'$ la projeté du vecteur $\vec{u}$ sur une droite de direction $\vec{i}$, on a alors $$\vec{u}'= (\vec{u}\cdot\vec{i})\vec{i}$$

$\vec{u}'$ est le vecteur minimisant la norme de la différence $\vec{u}-\vec{u}'$ (distance)

![[Pasted image 20220913101911.png]]

Le projeté de $\vec{u}+\vec{v}$ est le vecteur $\vec{u}'+\vec{v}'$.
Autrement dit, **le projeté de la somme est la somme des projetés**

## Produit vectoriel
Pour les vecteurs de l'espace (uniquement), on peut définir le produit vectoriel entre $\vec{u}$ et $\vec{v}$ des vecteurs de l'espace tel que $$\vec{u} \land \vec{v}= \vec{w}$$ avec $$\vec{w}=\begin{pmatrix} y_{A}z_{B} - z_{A}y_{B} \\ -(x_{A}z_{B}-z_{A}x_{B}) \\ x_{A}y_{B} -x_{B}y_{A} \end{pmatrix}$$

![[Pasted image 20220918182404.png]]

Autrement dit, c'est une application (dans l'espace) $$f: (\vec{u}, \vec{v}) \longmapsto \vec{w}$$

défini géometriquement de la manière suivante
![[Pasted image 20220913160015.png]]

- La norme de $\vec{w}$ est l'aire du parallèlograme engendré par les vecteurs $\vec{u}$ et $\vec{v}$
