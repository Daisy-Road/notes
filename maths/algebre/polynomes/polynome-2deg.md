# Polynome 2nd deg

On appelle polynôme du second degrés une expression tel que $P(x)=ax^{2}+bx+c$ avec $a,b,c \in \mathbb{R}$.
On nomme racines de $P(x)$ les valeurs de $x$ pour lesquels $P(x)=0$.
Si $\Delta > 0$ alors par TH1, $P(x)=a(x-c_{1})(x-c_{2})$ c'est sa forme **canonique**.

On nomme $\Delta=b^{2}-4ac$ le discriminant du polynôme.
Le signe de $P(x)$ dépend de $\Delta$ ainsi que du signe de $a$.
Le sommet $S$ de $P(x)$ a pour abscisse $x_{S}=\frac{-b}{2a}$

![[Pasted image 20220325191504.png]]


## Equation
Soit $P(x)=0$, on cherche donc les racines de $P(x)$, on procède de 2 manières,

- chercher des racines évidentes
- calculer $\Delta$

### Chercher des racines évidentes
On essaye des valeurs de $x$ compris entre -3 et 3.

Si on en trouve une, on peut appliquer la formule $x_{1}x_{2}=\frac{c}{a}$ avec $x_{1}$ et $x_{2}$ les racines de $P(x)$.

### Calculer $\Delta$
Soit $\Delta=b^{2}-4ac$.

Si $\Delta = 0$ alors $P(x)$ a une solution réel tel que,

$$x=\frac{-b}{2a}$$

Si $\Delta > 0$ alors $P(x)$ a deux solutions réels tel que,

$$x= \frac{-b\pm\sqrt{\Delta}}{2a}$$

Si $\Delta < 0$ alors $P(x)$ a deux solutions complexes,

$$x= \frac{-b\pm i\sqrt{-\Delta}}{2a}$$

## Equation coef complexe
Soit l'équation d'un polynôme du second degrés $az^{2}+bz+c=0$ avec $a,b,c \in \mathbb{C}$.

$\Delta = b^{2}+4ac$, avec $\Delta \in \mathbb{C}$

Soit $\delta$ une racine carré de $\Delta$, l'équation a pour solution,
$$z=\frac{-b\pm \delta}{2a}$$