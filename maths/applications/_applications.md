# Applications
Soit $S, S'$ des ensembles. Une **application** de $S$ vers $S'$ est une association $$f: S \longmapsto S'$$
qui pour chaque élément $x$ de $S$ associe un élément $f(x)$ de $S'$.

## Identités
On définit l'application identité $I_{S}$ pour tout ensemble $S$, telle que $$I_{S}(x)=x$$ pour tout $x$ de $S$.

>[!tip]+ Propriété 1
>Soit $I: S \mapsto S$ l'application identité et soit $f: S \mapsto S$ une application.
>Alors $$I\circ f= f\circ I=f$$

## Compositions
Soit $f: S \mapsto T$ et $g: U \mapsto V$ des applications.
On suppose que $T$ est un **sous-ensemble** de $U$.
Ainsi, on peut alors former la composée d'application $g\circ f$ pour laquelle sa valeur à un élément $x$ de $S$ est
$$(g\circ f)(x)=g(f(x))$$

- La composition d'applications est associatives

>[!tip]+ Propriété 2
>Si $f: S \mapsto T$, $g: T \mapsto U$, $h: U\mapsto V$ sont des applications, alors $$(h\circ g)\circ f=h\circ(g\circ f)$$

## Réciproques
Soit $f: S\longmapsto T$ une application.
 On définit l'application réciproque de $f$, comme étant une application $$g: T \longmapsto S$$ de sorte que la composée de $f$ et $g$ soit l'identité de $S$ et $T$.
 Respectivement on a : $$g\circ f = I_{S}$$ et $$f\circ g=I_{T}$$

---

On note usuellement l'application réciproque de $f$ ainsi $$f^{-1}: T \longmapsto S$$

---

>[!tip]+ Propriété 3
>Soit $f: S\longmapsto T$.
>On suppose que $g: T \mapsto S$ et $h: T\mapsto S$ sont des applications réciproques de $f$.
>Alors $$g=h$$

## Itérations
Soit $f: S\longmapsto S$ une application d'un ensemble sur lui-même.
On peut alors **itérer** $f$

Si $x$ est un élément de $S$, on peut avoir les itérations de valeurs suivantes : $$f(x),f(f(x)),f(f(f(x))), \dots$$

que l'on peut écrire $$f^{2}(x)=f(f(x))$$ $$f^{3}(x)=f(f(f(x)))$$ $$\vdots$$

De manière générale, $$f^{k}(x)=f(f(f(\dots f(x) \dots)))$$

Ainsi, l'image de $x$ par $f^{k}$ est $f^{k}(x)$

- $f^{k+1}=f\circ f^{k}$

>[!tip]+ Propriété 4
>Pour tout entiers $m,n$ et pour toute application $f: S\longmapsto S$ possédant une application réciproque, on a la formule
>$$f^{m+n}=f^{m}\circ f^{n}$$

>[!tip]+ Propriété 5
>$$f^{0}=I_{S}$$

>[!tip]+ Propriété 6
>On suppose que $f^{-1}$ existe.
>Alors on définit $$f^{-k}=(f^{-1})^k$$
>On a donc $$f^{k}\circ f^{-k}=f^{0}=I$$

>[!tip]+ Propriété 6
>Si $f^{n}=I$, pour certaines puissances positives de $f$, alors $$f^{-1}=f^{n-1}$$ et $$f=f^{n+1}$$