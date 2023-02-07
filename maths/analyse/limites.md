# Limites de fonction
On nomme limite d'une fonction $f(x)$ la valeur vers laquelle tend l'image de $x$ par $f$ lorsque l'on fait varier $x$ sur son domaine de définition.

FI = forme indéterminé

Il y a 4 FI

- $+\infty -\infty$
- $\infty \cdot 0$
- $\large\frac{\infty}{\infty}$
- $\frac{0}{0}$

## Général

![[Pasted image 20220925193653.png]]

![[Pasted image 20220925231242.png]]

## Opérations sur les limites
Soit $f$ et $g$ des fonctions.
Soit $l$ et $l'$ les valeurs de leurs limites dans $\mathbb{R}$.

> **Par somme:** $lim \space f + lim \space g$
>
![[Screenshot from 2022-03-25 20-26-41.png]]

> **Par produit**: $lim \space f \cdot lim \space g$
> 
![[Screenshot from 2022-03-25 20-23-15.png]]

> **Par quotient**: $\huge\frac{lim \space f}{lim \space g}$
> 
![[Screenshot from 2022-03-25 20-36-45.png]]

On notera ces 3 opérations très communes pour les quotients avec $n=l$ pour la lisibilité,

$$\frac{n}{\infty}=0 \space ; \frac{n}{0}=\infty \space; \frac{0}{n}=0$$

### Limite de composé de fonction
Soit $(g \circ f)(x)$ une composé de fonction, on souhaite calculer sa limite en $a$, pour se faire on calcule la limite de $f(x)$ en $a$ pour obtenir une valeur $b$,

$$\lim\limits_{x \rightarrow a} f(x) = b$$

Ensuite, on calcule la limite en $b$ de $g(x)$ pour obtenir une valeur $c$,

$$\lim\limits_{x \rightarrow b} g(x) = c$$

Par conséquent, la limite de $(g \circ f)(x)$ en $a$ est la valeur $c$,

$$\lim\limits_{x \rightarrow a} (g \circ f)(x) = c$$

### Cas particulier des fonctions rationnels
Cas valable **uniquement** en $\pm \infty$.


Soit $f(x)$ une fonction rationnel,

$\lim\limits_{x \rightarrow \infty} f(x) = \lim\limits_{x \rightarrow \infty}$ de son terme de plus haut degré.

## Branches infinies
Soit $f$ une fonction et $C_{f}$ sa courbe.
$C_{f}$ admet une **branche infinie** dans les 3 cas suivants:

---

Soit $x_{0} \in \mathbb{R}$,

>$\lim\limits_{x \rightarrow x_{0}} f(x) = \infty$
>$=>$ Asymptote **verticale** d'équation $x=x_{0}$

---

>$\lim\limits_{x \rightarrow \infty} f(x) = l$
$=>$ Asymptote **horizontale** d'équation $y=l$

---

$\lim\limits_{x \rightarrow \infty} f(x) = \infty$

Si on se trouve dans ce cas présent, on fait la limite de $\Large\frac{f(x)}{x}$ avec $x\rightarrow\infty$, on note $X$ cette limite.

Si $X= \infty$

> Pas d'asymptote mais direction asymptotique verticale

Si $X=0$

> Pas d'asymptote mais direction asymptotique horizontale

Si $X=a$, on calcule la limite de $f(x)-ax$ avec $x \rightarrow \infty$, on note $Y$ cette limite.

Si $Y=\infty$

> Pas d'asymptote mais une direction asymptotique oblique d'équation $y=ax$

Si $Y=b$

> Asymptote oblique d'équation $y=ax+b$

---

### Cas particulier
Soit $f(x)=ax+b+\varphi(x)$.

Si $\lim\limits_{x \rightarrow \infty} \varphi(x) = 0$ alors $f(x)$ admet une aymptote oblique d'équation $y=ax+b$.

## Gestion FI
Pour lever une forme indéterminé, le moyen le plus simple est de **factoriser** la fonction par le **terme dominant** puis **simplifier**.

Cela ne marche néanmoins pas pour $\frac{0}{0}$, pour lever cette FI, il y a 3 moyens,

>Règle de l'hopital
>
>$$\lim\limits_{x \rightarrow a} \frac{u}{v} = \frac{0}{0} => \lim\limits_{x \rightarrow a} \frac{u}{v} = \lim\limits_{x \rightarrow \infty} \frac{u'}{v'}$$


>Si $f(x)=\frac{\varphi(x)-\varphi(a)}{x-a}$ alors on cherche $\lim\limits_{x \rightarrow a} f(x) = \varphi'(x)$

> Si $f$ est rationnelle, c'est à dire si $f(x)=\frac{P(x)}{Q(x)}$,
> et que l'on a $\lim\limits_{x \rightarrow a} f(x) = \frac{0}{0}$
> $=>\lim\limits_{x \rightarrow a} f(x)=\huge\frac{(x-a)P_{1}(x)}{(x-a)Q_{1}(x)}$