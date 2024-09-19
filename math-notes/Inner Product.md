# Inner Product
An inner product on a real vector space $V$ is a map
$$ V \times V \to \RR\text{, denoted } (v,w) \mapsto \langle v,w \rangle,$$
satisfying, for all $v,w,y \in V$, and for all $\lambda \in \RR$:
1. $\langle v,w \rangle \geq 0$, with $\langle v,w \rangle \iff v = w$.
2. $\langle v,w \rangle = \langle w,v \rangle$
3. $\langle v,w \rangle \geq 0 + \langle w,y \rangle = \langle v+w, w \rangle$
4. $\lambda \langle v,w \rangle = \langle \lambda v,w \rangle$

Inner products on complex vector spaces behave much the same, except we have that
$\langle v,w \rangle = \overline{\langle w,v \rangle}$, where $\overline{x}$ denotes the complex conjugate of $x$.

Note that 2 combined with 4 implies that $\langle v, \lambda w \rangle = \overline \lambda \langle v,w \rangle$.

## Cauchy-Schwarz
Let $V$ be an inner product space. Then, 
$$ |\langle V,W \rangle| \leq \sqrt{\langle{v,v}\rangle \langle w,w \rangle}.$$
