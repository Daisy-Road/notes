# Fonctions
Soit $S$ un ensemble de nombres. Une **fonction définit sur** $S$  est une association à qui pour chaque élément de $S$ associe un nombre.

Soit $f$ une fonction et $x$ un élément de $S$, on note cette association $$f: x \longmapsto f(x)$$

- On nomme $S$ le domaine de la fonction et l'ensemble des nombres $f(x)$ le codomaine de la fonction
- La **valeur/image** d'une fonction est un nombre
- Il faut considérer le domaine, le codomaine et son graphe

Une application $$\mathbb{R^{2}} \longmapsto \mathbb{R}$$ 
est une fonction définit sur $\mathbb{R^{2}}$ car son image est un **nombre**

## Graphe
Le graphe d'une fonction $f$ définit sur un ensemble $S$ est l'ensemble de tous les points $$(x,f(x))$$
C'est l'image de l'application $$x \longmapsto (x,f(x))$$


## Opérations
Soit $f,g$ des fonctions définies sur le même ensemble $S$

### Sommes
On définie la somme $f+g$  comme étant la fonction à qui pour un élément $x$ de $S$ on y associe la valeur $$f(x) + g(x)$$
Autrement dit, $$f+g: x \longmapsto f(x)+g(x)$$
L'addition de fonctions hérite des propriétés de l'additions de nombres. Elle est donc associative, commutative.

#### Associativité
Soit $h$ une fonction définie sur $S$
On a, $$(f+g)+h = f+(g+h)$$
#### Commutativité
$$f+g=g+f$$
#### Élément neutre
Soit $0$ la fonction zéro définie sur $S$ ayant pour valeur $0$ pour tout élément $x$ de $S$ 
On a, $$f + 0 = 0 + f = f$$
### Produit
On définie le produit $fg$ comme étant la fonction associant pour tout élément $x$ de $S$ la valeur $f(x)g(x)$
Autrement dit, $$fg: x \longmapsto f(x)g(x)$$
La multiplication de fonctions hérite des propriétés de la multiplication de nombres. Elle est donc associative, commutative, distributive (par rapport à l'addition) et possède un élement neutre et un élément absorbant.

#### Associativité
Soit $h$ une fonction définie sur $S$
On a, $$(fg)h=f(gh)$$
#### Commutativité
$$fg=gf$$

#### Distributivité
Soit $h$ une fonction définie sur $S$
On a, $$((f+g)h)(x)=(fh +gh)(x)$$$$(f+g)h=fh +gh$$


#### Élément neutre et élément absorbant
Soit $1$ la fonction constante définie sur $S$ ayant pour valeur $1$ pour tout élément $x$ de $S$
On a, $$1f=f$$Soit $0$ la fonction zéro définie sur $S$ ayant pour valeur $0$ pour tout élément $x$ de $S$
On a, $$0f= 0$$

## Injectivité
Pour savoir si $f$ est **injective**, il faut voir si pour tout $a,b\in S,f(a)=f(b) => a = b$ ou bien inversement si $a \neq b => f(a) \neq f(b)$.

## Surjectivité 
Pour savoir si $f$ est **surjective**, il faut voir si $y=f(x)$ pour tout $y \in \mathbb{R}$.

## Bijectivité
Si $f$ est **injective** et **surjective**, alors $f$ est **bijective**.

exemple: $f(x)=ax+b$
