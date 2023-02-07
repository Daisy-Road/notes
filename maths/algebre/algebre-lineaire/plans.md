# Plans
Soit $P$ un point de l'espace, et $\overrightarrow{ON}$ un vecteur.
On définit le plan orthogonale à $\overrightarrow{ON}$ et passant par $P$ comme étant l'ensemble de tous les points $X$ de sorte que le vecteur $\overrightarrow{PX}$ soit orthogonale à $\overrightarrow{ON}$

![[Pasted image 20220805121021.png]]

Autrement dit, on a $$(X-P) \cdot N=0 <=> X\cdot N=P \cdot N$$


## Équation du plan
Dans l'espace, le vecteur $N=(a,b,c)$ est orthogonale au plan déterminé par l'équation $$X\cdot N=P\cdot N <=> ax+by+cz=d$$

## Parallélisme/Orthogonalisme/Angle
Deux plans de l'espace sont parallèles si leurs vecteurs normaux sont parallèles.
Ils sont orthogonales si leurs vecteurs normaux sont orthogonales.
L'angle entre deux plan est définie comme l'angle entre leurs vecteurs normaux.

- le vecteur orthogonale au plan est aussi appelé le vecteur normal

## Distance point/plan
![[Pasted image 20220805173916.png]]

La distance entre $Q$ et le plan $K$ est égale à la norme du vecteur $\overrightarrow{QQ'}$ qui est donc la projection du vecteur $\overrightarrow{QP}$ sur $\overrightarrow{QQ'}$ qui est donc la projection du vecteur $Q-P$ sur le vecteur unitaire de $N$ qui est $\frac{N}{||N||}$, on en conclut que $$d(Q,K)=\frac{|(Q-P)\cdot N|}{||N||}$$