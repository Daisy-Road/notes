
# Déterminant d'Ordre 3
![[Pasted image 20230114153010.png]]

On peut obtenir le déterminant en expandant par rapport à n'importe quelle ligne ou colonne d'une façon analogue avec $a_{i,j} \times det(A_{i,j})$, et en appliquant le bon signe à chaque terme:

![[Pasted image 20230114153314.png]]

## Propriétés
![[Pasted image 20230118164533.png]]
![[Pasted image 20230118164600.png]]
![[Pasted image 20230118164635.png]]
![[Pasted image 20230118164707.png]]
![[Pasted image 20230118164731.png]]

### Linéarité
Soit $x_{j}$ un nombre avec $j\in {1,\dots , n}$.
Si $$A^{1} = \sum^{n}_{j=1}C^{j}$$ alors $$det(A^{1}, A^{2}, A^{3}) = \sum^{n}_{j=1}det(C^{j},A^{2}, A^{3})$$