DL "Approximer" une fonction dérivable
- autour d'un point ( local )
- par un polynôme

Formule de Taylor $$f(x)=\Sigma_{k=0}^{n}f^{(k)}(0)\frac{x^{k}}{k!}$$
plus un reste

![[Pasted image 20221119233731.png]]

- Si on est pas au point 0 ou que ce n'est pas un DL usuelle, il est préférable d'appliquer la formule de taylor directement


## Compositions
Soit $f$ et $g$ deux fonctions, le $DL_{n}(x_{0})$ de $g\circ f$ est particulier.

Il faut faire le $DL$ de $f$ en $x_{0}$ puis prendre sa limite pour $x \rightarrow x_{0}$ afin de déterminer un point $y_{0}$, où l'on va déterminer le $DL$ de $g$ en ce point, puis ensuite on calcule la composition avec ces deux $DL$ avec troncature etc...

L'image du $DL$ de $f$ pour $x$ au voisinage de $x_{0}$ peut nous emener sur le voisinage d'un autre point $y_{0}$, donc il est nécessaire d'avoir le $DL$ d'une fonction $g$ défini sur ce voisinage pour pouvoir l'appliquer sur celui de $f$

## Propositions TD

### P1
Soit $f$ une fonction de classe $C^{\infty}$ au voisinage de $a$.
Soit $P$ le polynôme du $DL_{n}(a)$ de $f'$, nous avons alors $$DL_{n+1}(a)\text{ de } f = f(a) + \int P \,dx$$

---

![[Pasted image 20221112151831.png]]

![[Pasted image 20221112154958.png]]

![[Pasted image 20221112165018.png]]

![[Pasted image 20221112165036.png]]

---
$x = x_0 + h$
![[Pasted image 20221112180626.png]]

![[Pasted image 20221113120718.png]]

![[Pasted image 20221113143040.png]]

![[Pasted image 20221113144644.png]]
![[Pasted image 20221113144723.png]]

![[Pasted image 20221113144806.png]]