# Isométrie
Une isométrie est une application du plan qui conserve les distances entre les points.

---

## Théorème 1
Soit $F$ une **isométrie**. L'image d'un segment par $F$ est un segment. Cela veut dire que **l'image** d'un segment $\overline{PQ}$ par $F$ est le segment entre les points $F(P)$ et $F(Q)$.

### Corrolaire
**Une isométrie préserve les droites.** Cela signifie, que si $L$ est une droite dans le plan et $F$ une **isométrie**, alors $F(L)$ est aussi une droite.

Si $L$ est la droite qui passe par deux points distincts $P$ et $Q$, alors $F(L)$ est la droite passant par les points $F(P)$ et $F(Q)$.

---

## Théorème 2
Soit $F$ une **isométrie**. Soit $P,Q$ deux points distincts dans le plan. On suppose qu'ils sont des **points fixes**, c'est à dire:

$$F(P)=P\space\text{et}\space F(Q)=Q$$

Alors tous les points sur la droite passant par $P$ et $Q$ sont des **points fixes** de $F$.

*Preuve du TH dans le vault "essays".*

---

## Théorème 3
Soit $F$ une **isométrie**. Soit $P,Q,M$ trois points distincts qui ne sont pas sur une droite.
On suppose que $P,Q,M$ sont des **points fixes** de $F$; donc,

$$F(P)=P,\space\space\space F(Q)=Q,\space\space\space F(M)=M.$$

Alors $F$ est **l'identité**.

### Corrolaire
Soit $P,Q,M$ trois points distincts qui ne sont pas sur la même droite. Soit $F,G$ des **isométries** tel que

$$F(P)=G(P),\space\space\space F(Q)=G(Q),\space\space\space F(M)=G(M).$$
 
On suppose que $F^{-1}$ existe. Alors $F= G$.

## Théorème 4
Soit $P,Q$ des points distincts. Soit $F$ une isométrie qui laisse $P$ et $Q$ fixés.

Dans ce cas, soit $F$ est **l'identité**, soit $F$ est une **réflexion** à travers la droite $L$ passant par les points $P$ et $Q$.

## Théorème 5
Soit $F$ une isométrie qui laisse un point $O$ fixé. 

Alors $F$ est soit une **rotation**, soit une **rotation composée avec une réflexion** à travers une droite.

## Théorème 6
Soit $F$ une isométrie arbitraire du plan. Si $F$ ne laisse aucun point fixé.

Dans ce cas $F$ est soit une **translation**, soit une **translation composée avec une rotation**, soit la **composé d'une translation, d'une rotation, et d'une réflexion** à travers une droite.

## Toutes les isométries ont un inverse
Par TH 4,5, et 6 une isometrie $F$ peut s'écrire sous la forme 
d'une composé d'isométrie $F_{1}$, ou $F_{1} \circ F_{2}$, ou $F_{1} \circ F_{2} \circ F_{3}$ tel que $F_{1}, F_{2}, F_{3}$ ont chacune un inverse (car chacune est soit l'identité, soit une translation, soit une rotation, soit une réflexion).

Par conséquent, $F$ a pour inverse $F^{-1}_{1}$, ou $F^{-1}_{2} \circ F^{-1}_{1}$ ou $F^{-1}_{3} \circ F^{-1}_{2} \circ F^{-1}_{1}$

---

# Congruence
Soit $S, S'$ des ensembles de points dans le plan.
On dit que $S$ est congruent à $S'$ si il existe une isométrie $F$ tel que **l'image** de $S$ par $F$, c'est à dire $F(S)$, soit **égale** à $S'$.

## Théorème 7
Deux cercles avec le même rayon sont congruents.

## Théorème 8
Deux segments de même longueurs sont congruents.

## Théorème 9
Soit $\Delta PQM$ et $\Delta P'Q'M'$ des triangles rectangles dont leurs angles droits sont situés aux points $Q$ et $Q'$ respectivement.
On suppose que leurs "legs" correspondant ont la même longueur, c'est à dire:

$$d(P,Q)=d(P',Q')$$

et

$$d(Q,M)=d(Q',M')$$

Alors les triangles sont congruents.

## Théorème 10
Soit $\Delta PQM$ et $\Delta P'Q'M'$ des triangles dont leurs côtés correspondant ont la même longueur, c'est à dire

$$d(P,Q)=d(P',Q')$$
$$d(P,M)=d(P',M')$$
$$d(Q,M)=d(Q',M')$$

Ces triangles sont alors congruents.

## Axiome Isometrie et Aire
Soit $S$ une région du plan, qui a une aire égale à $a$. Soit $F$ une isométrie. Alors l'aire de $F(S)$ est aussi égale à $a$.

