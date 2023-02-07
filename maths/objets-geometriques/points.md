# Points
On considère un point comme un n-uplet.

## Addition
Soit $A=(a_{1},...,a_{n})$ et $B=(b_{1},...,b_{n})$.
On définit l'addition des points $A$ et $B$ telle que $$A+B = (a_{1}+b_{1},...,a_{n}+b_{n})$$

Cela forme un parallélograme de côtés $O,A,B,A+B$, on a donc $\overline{OA}$ // $\overline{B(A+B)}$ et $\overline {OB}$ // $\overline{A(A+B)}$

## Distance entre les points
La distance entre deux points $P=(x_{1},y_{1})$ et $Q=(x_{2},y_{2})$ se note,
$$d(P,Q)=|P-Q|=\sqrt{(x_{1}-x_{2})^{2}+(y_{1}-y_{2})^{2}}$$

>[!tip]+ Propriété
>Soit $r$ un nombre positif. Si $A,B$ sont des points, alors
>$$d(rA,rB)=r \cdot d(A,B)$$

>[!tip]+ Propriété
>Soit $c$ un nombre. Alors
>$$d(cA,cB)=|c| \cdot d(A,B)$$

## Dilatation par un scalaire
Soit $A=(a_{1},a_{2})$.
Si $r$ est un nombre positif, alors $rA=(ra_{1},ra_{2})$ est la dilatation/homothétie de $A$ par $r$, on note cette association,
$$A \mapsto rA$$

Soit $D_{r}$ une dilatation par $r$. $$D_{r}=\begin{pmatrix} r & 0 \\ 0 & r \end{pmatrix}$$

Soit $D_{a,b}$ une dilatation par $a,b$. $$D_{r}=\begin{pmatrix} a & 0 \\ 0 & b \end{pmatrix}$$

>[!tip] 
>Soit $c$ un scalaire et $A,B$ des points. $$c(A+B)=cA+cB$$

>[!tip] 
>Soit $c_{1},c_{2}$ des scalaires et $A$ un point.
>$$(c_{1}+c_{2})A=c_{1}A+c_{2}A$$


- si $bA=cA$ alors $b=c$

### Aire
Si $S$ est une région du plan et $r$ une dilatation uniforme, alors l'aire de $rS = r^{2}A(S)$ 

*Exemple si $r$ n'est pas uniforme*,

>Soit $F_{a,b}$ une dilatation. Soit $(u,v)$ un lieu de points.
>Soit $C$ le cercle d'équation $u^{2} + v^{2} = 1$ avec $A(C)=\pi$.
>
>Alors $A(F_{a,b}(C))=ab \cdot A(C) = ab\pi$
