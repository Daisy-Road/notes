# Algorithme d'Euclide
Soit $f$ et $g$ des polynômes non-nuls.
Alors il existe des polynômes $q,r$ tels que $deg(r) < deg(g)$ et de sorte que $$f(x)=q(x)g(x)+r(x)$$
On s'arrête lorsque que $deg(r) < deg(g)$
L'idée est de déterminer un terme $k$ de $q(x)$ qui annule le premier terme de gauche puis de multiplifier $k$ par $g(x)$ puis enfin soustraire le résultat à l'expression de gauche.

Si on trouve une racine $c$ du polynôme, par TH1 on a $g(x)=(x-c)$

![[Pasted image 20220719142052.png]]




