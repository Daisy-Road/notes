# Dérivée d'une fonction
![[Pasted image 20220925231921.png]]
La méthode générale:

$$\frac{\Delta y}{\Delta x}=\frac{f(x)-f(a)}{x-a}$$
$$=> f'(a)= \lim\limits_{x \rightarrow a} \frac{f(x)-f(a)}{x-a}$$

Équation de la tangente au point d'abscisse $a$:

$$y=f'(a)(x-a)+f(a)$$

Une dérivée peut aussi s'écrire sous la forme,

$$\frac{df}{dx}$$

## Fonctions élémentaires

| $f(x)$  |     | $C$ | $x^2$ | $x^3$    | $x^n$      | $\sqrt{x}$            | $\frac{1}{x}$       | $\frac{1}{x^{n}}$     | $cos(x)$  | $sin(x)$ |
| ------- | --- | --- | ----- | -------- | ---------- | --------------------- | ------------------- | --------------------- | --------- | -------- |
| $f'(x)$ |     | $0$ | $2x$  | $3x^{2}$ | $nx^{n-1}$ | $\frac{1}{2\sqrt{x}}$ | $- \frac{1}{x^{2}}$ | $- \frac{n}{x^{n+1}}$ | $-sin(x)$ | $cos(x)$ |

## Opérations

| **forme de** $f$  | $u+v$   | $ku$ **avec** $k \in \mathbb{R}$ | $uv$        | $u^{n}$      | $\sqrt{u}$             | $\frac{1}{u}$        | $\frac{u}{v}$           | $(v \circ u)'$          | 
| ----------------- | ------- | -------------------------------- | ----------- | ------------ | ---------------------- | -------------------- | ----------------------- | ----------------------- |
| **forme de** $f'$ | $u'+v'$ | $ku'$                            | $u'v + v'u$ | $nu'u^{n-1}$ | $\frac{u'}{2\sqrt{u}}$ | $- \frac{u'}{u^{2}}$ | $\frac{u'v-v'u}{v^{2}}$ | $u' \cdot (v' \circ u)$ |



![[Pasted image 20220925232044.png]]

- $x$ est un pt d'inflexion <=> $f^{''}(x)=0$
- la dérivée de $u^{n}$ est très importante et à prioriser 

---
Si $f(x)=x^{k}$, alors $f^{(k)}(x) = k!$