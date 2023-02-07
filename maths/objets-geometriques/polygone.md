# Polygone
On peut décomposer un polygone $K_{n}$ de $n$ côtés en $n$ triangles congruents.

Soit $T_{n}$ un de ces triangles, soit $b_{n}$ sa base et $h_{n}$ sa hauteur
L'aire $A(T_{n})$ du triangle est de $\frac{1}{2} \cdot b_{n}h_{n}$

Le périmètre $P_{n}$ de $K_{n}$ est $n \cdot b_{n}$
Alors l'aire du polygone $K_{n}$ est de $\frac{1}{2} \cdot nbh = \frac{1}{2} \cdot P_{n}h$.

Autrement dit, 
$$A(K_{n})=n \cdot A(T_{n})$$

*remarque...* 

Soit $c$ le périmètre d'un cercle $C$ de rayon $r$ qui circonscrit le polygone.
Plus $n$ augmente et plus
- $A(K_{n})$ approche l'aire de $C$ 
- $P_{n}$ approche le périmètre de $C$
- $h_{n}$ approche le rayon de $C$

Autrement dit, $\lim\limits_{n \rightarrow \infty} A(K_{n}) = \lim\limits_{n \rightarrow \infty} \frac{1}{2} \cdot P_{n}h_{n} = \frac{1}{2} \cdot cr$

$\frac{1}{2}cr$ est donc l'aire de $C$
Et donc, $$\pi r^{2}=\frac{1}{2}cr => c = 2\pi r$$
