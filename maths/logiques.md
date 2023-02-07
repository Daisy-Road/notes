# Logiques
La logique permet de déduire des nouvelles informations d'anciennes informations.

- Il est important de distinguer une logique correcte d'une information correcte

## Propositions
Une proposition est une phrase qui est soit définitivement vraie, soit définitivement fausse.
On doit pouvoir lui assigner une valeur de vérité

$P:$ *proposition*

Si la proposition contient une variable $x$, on peut la noter $P(x)$

- Il est utile de décomposer une proposition en sous-propositions

## ET/OU/NON
| Et      | Ou     | Non    |
| ------- | ------ | ------ |
| $\land$ | $\vee$ | $\sim$ | 


![[Pasted image 20220817150737.png]] ![[Pasted image 20220817150805.png]] ![[Pasted image 20220817150841.png]] 

## Propositions conditionnelles 
Une proposition conditionnelle est une proposition de la forme $$R: \text{ Si }P\text{ alors }Q$$
que l'on peut noter $$R: P=>Q$$ ou $$R: (\sim P)\vee Q$$

Il faut voir cette proposition comme une promesse que $Q$ sera vraie sous condition de $P$, tant qu'elle n'est pas brisé alors $R$ sera vraie.
Autrement dit, tant qu'aucune contradiction survient, $R$ sera vraie.

![[Pasted image 20220817223016.png]]

- Si $P=>Q$ est vraie, alors il est impossible que $P$ soit vraie et $Q$ fausse, donc pour que $P$ soit vraie, il est nécessaire que $Q$ soit vraie, i.e $P$ est vraie seulement si $Q$ l'est
- On nomme $Q=>P$ la **réciproque** de $P=>Q$
- $P=>Q = (\sim P)\vee Q$

---

Si $P(x)$ et $Q(x)$ sont des phrases ouvertes, alors la proposition $P(x)=>Q(x)$ est compris comme $\forall x \in X, P(x)=>Q(x)$

>[!tip]+ Déf
>Si $P$ et $Q$ sont des propositions ou des phrases ouvertes, alors $$\text{"If }P \text{, then }Q \text{,"}$$
>est une proposition.
>Cette proposition est vraie si il est impossible pour $P$ d'être vraie pendant que $Q$ est fausse.
>Elle est fausse si il y a au moins une instance dans laquelle $P$ est vraie mais $Q$ est fausse

## Propositions biconditionnelles
Une proposition biconditionnelle est une proposition de la forme $$P<=>Q$$

![[Pasted image 20220818214040.png]]
![[Pasted image 20220818213915.png]]

- $P<=>Q = (P=>Q)\land(Q=>P)=(P\land Q)\vee(\sim P\land \sim Q)$

## Tables de vérités
Il est utile de faire une table de vérité pour analyser une proposition

*exemples*
>$P$ ou $Q$ est vraie, mais pas les deux à la fois
>![[Pasted image 20220819131216.png]]

>![[Pasted image 20220819131236.png]]

## Équivalence logique
Deux propositions sont logiquement équivalentes si et seulement si elles ont une table de vérité identique.

![[Pasted image 20220819232614.png]]

![[Pasted image 20220819232902.png]] 

![[Pasted image 20220819233004.png]]

## Quantificateurs
### Définition 1
Les symboles $\forall$ et $\exists$ sont appelés des **quantificateurs**.
$\forall$ veut dire "Pour tout" ou "Pour chaque"
$\exists$ veut dire "Il existe" ou "Il y a"

---

$\forall$ se nomme le **quantificateur universel**
$\exists$ se nomme le **quantificateur existentiel**

Une proposition commençant par $\forall$ est appelée une proposition **universellement quantifiées**
Une proposition commençant par $\exists$ est appelée une proposition **existentiellement quantifiées**

- L'ordre des quantificateurs est très important

>[!tip]+ Propriété
>On suppose que $X$ est un ensemble et $Q(x)$ une proposition à propos de $x$ pour chaque $x\in X$.
>Les propositions suivantes ont la même signification :
>$$\forall x \in X, Q(x)$$
>$$(x\in X) => Q(x)$$

### Négation
>[!tip]+ Propriété
>$$\sim(\forall x \in X, P(x))=\exists x \in X, \sim P(x)$$
>$$\sim(\exists x \in X, P(x))=\forall x \in X, \sim P(x)$$

![[Pasted image 20220821184448.png]]


## Inférence logique
Si les deux propositions du haut sont vrais, alors celle du bas est vrai

![[Pasted image 20220822115340.png]]

![[Pasted image 20220822120116.png]]
