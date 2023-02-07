# Opérations sur des points
## Homothétie ( multiplication )
Soit $A=(a_{1},a_{2})$.
Si $r$ est un nombre positif, alors $rA=(ra_{1},ra_{2})$ est la dilatation/homothétie de $A$ par $r$, on note cette association,
$$A \mapsto rA$$

Soit $D_{r}$ une dilatation par $r$. $$D_{r}=\begin{pmatrix} r & 0 \\ 0 & r \end{pmatrix}$$

Soit $D_{a,b}$ une dilatation par $a,b$. $$D_{r}=\begin{pmatrix} a & 0 \\ 0 & b \end{pmatrix}$$


### Aire
Si $S$ est une région du plan et $r$ une dilatation uniforme, alors l'aire de $rS = r^{2}A(S)$ 

*Exemple si $r$ n'est pas uniforme*,

>Soit $F_{a,b}$ une dilatation. Soit $(u,v)$ un lieu de points.
>Soit $C$ le cercle d'équation $u^{2} + v^{2} = 1$ avec $A(C)=\pi$.
>
>Alors $A(F_{a,b}(C))=ab \cdot A(C) = ab\pi$

## Réflexion
On définit la réflexion par l'origine $O$ comme étant l'association pour tout point $A=(a_{1},a_{2})$ qui associe $-A=(-a_{1},-a_{2})$. On écrit cela,
$$A \mapsto -A$$
Si on note $R$ cette réflexion, alors
$$R(A)=-A$$

## Théorème 1
Soit $r$ un nombre positif. Si $A,B$ sont des points, alors
$$d(rA,rB)=r \cdot d(A,B)$$

## Théorème 2
Soit $c$ un nombre. Alors
$$d(cA,cB)=|c| \cdot d(A,B)$$

## Divers
- si $bA=cA$ alors $b=c$