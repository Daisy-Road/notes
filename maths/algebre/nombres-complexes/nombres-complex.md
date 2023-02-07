# Ensemble $\mathbb{C}$

L'ensemble des nombres complexes se note $\mathbb{C}$. 
$\mathbb{R} \subseteq \mathbb{C}$.

$\mathbb{C} = \{ a+ib : a,b \in \mathbb{R}\}$ avec $i$ un nombre imaginaire tel que $i^2=-1$

$a$ est appelé la partie réel et se note $Re(z)$
$b$ est appelé la partie imaginaire et se note $Im(z)$

Les opérations de l'ensemble sont commutatifs, associatifs, etc...

Le plan des complexes est représenté avec l'axe des réels à l'horizontale et l'axe des imaginaires à la verticale.

![[Pasted image 20220325093303.png]]

On note $i^{n}=i^{x}$ avec $n,x \in \mathbb{Z}$ et $x$ le reste de la division euclidienne de $n$ par $4$.

## Conjugaison
On appelle le conjugé de $z \in \mathbb{C}$ le nb $z$ tel que $Im(z)$ soit de signe opposé.
Que l'on note $\overline{z}$

Si $z=a+ib$, on note $\overline{z}=a-ib$

*propriétés algébriques*

- $\overline{z_{1}+z_{2}} = \overline{z_1}+\overline{z_{2}}$
- $\overline{z_{1} - z_{2}}=\overline{z_{1}}-\overline{z_{2}}$
- $\overline{z_{1} \cdot z_{2}} = \overline{z_{1}}\cdot \overline{z_{2}}$
- $\huge\overline{(\frac{z_{1}}{z_{2}})} = \frac{\overline{z_{1}}}{\overline{z_{2}}}$
- $\overline{z^{n}}=(\overline{z})^{n}$
- $z\overline{z}=|z|^{2}$


## Module
Le module ou "valeur absolue" d'un nombre complexe est la **distance** qui le sépare de l'origine sur le plan.
On le note $|z|$

Soit $z=a+ib$, alors $|z|=\sqrt{a^{2}+b^{2}}$

*propriétés algébriques*

- $|z_{1}\cdot z_{2}| = |z_{1}| \cdot |z_{2}|$
- $\large |\frac{z_{1}}{z_{2}}| = \frac{|z_{1}|}{|z_{2}|}$
- $|z^{n}|=|z|^{n}$


## Argument
On appelle l'argument d'un nombre complexe l'angle en radian que l'on note $arg(z)$ ou $\theta$ entre le module et l'axe positif des réels sur le plan.

Soit $z=a+ib \in \mathbb{C}$, on détermine l'argument de $z$ que l'on note $arg(z)$ en utilisant la trigonométrie, on a donc,

$cos(\theta)=\frac{a}{|z|}$ et $sin(\theta)=\frac{b}{|z|}$

$\theta$ est donc l'angle en radian correspondant

*propriétés algébriques* identique au logarithme

## Forme exponentiel/polaire
On note $e^{i\theta}=cos(\theta)+i sin(\theta)$ avec $\theta$ l'argument de $z$.

Soit $z=a+ib \in \mathbb{C}$, on peut écrire ce nombre sous forme polaire tel que $z=|z|e^{i\theta}$



