# Fonctions polynomials 
Soit $f$ un fonction définie sur un ensemble $S$.
Soit $a_{0},...,a_{n}$ des nombres avec $a_{n}\neq 0$.
On appelle $f$ un polynôme si on a pour tout $x$ $$f(x)=a_{n}x^{n}+a_{n-1}x^{n-1}+...+a_{0}=\Sigma_{k=0}^{n}a_{k}x^{k}$$
Tout polynôme peut s'écrire d'une façon unique sous cette forme.
Autrement dit, les nombres $a_{0},...,a_{n}$ sont propres à $f$, on les appelle ses **coefficients**, avec $a_{n}$ le coefficient **principale** si $a_{n} \neq 0$ et $a_{0}$ le **terme constant**.

- $deg(fg)=deg(f)+deg(g)$

## Polynôme identiquement nul
Par définition, on appelle $f$ le polynôme nul si et seulement si $$f(x)=0$$
pour **tout** nombre $x$

---

> [!info]+ Théorème 1
Soit $f$ un polynôme de degré $\le n$ et soit $c$ une de ses racines.
Alors il existe un polynôme $g$ de degré $\le n-1$ de sorte que pour tout nombre on a $$ f(x)=(x-c)g(x)$$  $g(x) = a_{n}x^{n-1} + les\space autres\space termes$


>[!info]+ Théorème 2
Soit $f$ un polynôme. Soit Soit $a_{0},...,a_{n}$ de telle sorte que $a_{n}\neq 0$ et de sorte que l'on a $$f(x)=\Sigma_{k=0}^{n}a_{k}x^{k}$$
pour tout $x$. Alors $f$ a tout au plus $n$ racines. 


>[!info]+ Corollaire TH2
Soit $f$ un polynôme pouvant s'écrire sous la forme $$f(x)=\Sigma_{i=0}^{n}a_{i}x^{i}$$ et aussi sous la forme $$f(x)=\Sigma_{i=0}^{n}b_{i}x^{i}$$
Alors $$a_{i}=b_{i}$$

--- 

![[Pasted image 20221024174232.png]]