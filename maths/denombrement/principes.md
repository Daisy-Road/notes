# Principes de dénombrement

>[!info]+ Principe de Multiplication
>On suppose qu'en faisant une liste de longueur $n$ il existe $a_{i}$ choix possibles pour l'entree $i$ avec $i\in \{1, \dots ,n\}$.
>Alors le nombre totale de listes pouvant être faite de cette manière est le produit $$a_{1}\cdot a_{2} \cdot \dots \cdot a_{n}$$

>[!info]+ Principe d'Addition
>On suppose qu'un ensemble fini $X$ peut se décomposer comme une réunion $X=\bigcup_{i=1}^{n}X_{i}$ où $X_{i}\cap X_{j} = \emptyset$ quand $i\neq j$.
>Alors $$|X|=\Sigma_{i=1}^{n}|X_{i}|$$

>[!info]+ Principe de Soustraction
>Si $X$ est une sous-ensemble d'un ensemble fini $U$, alors $|\overline{X}|=|U|-|X|$