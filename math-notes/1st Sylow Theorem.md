# First Sylow Theorem
Let $G$ be a group of order $p^ab$ with $\gcd(a,b) = 1$.
Then $G$ has a subgroup of order $p^c$ for all
$1 \leq c \leq a$, and if $|H| = p^c$ with $c < a$, then $H$ is normal in a subgroup of order $p^{c+1}$ in $G$.

$\Pf$ Since $P \mid |G|$, there exists $g \in G$ of order $p$ (by a homework problem).
So $\langle g\rangle \subset G$ and has order $p$. Let $H \subset G$ with $|H| = p^c$, with $1 \leq c < a$. 
Then $P | [G:H]$, so $H \subsetneq N_G(H)$.

Then $1 < |N_G(H)/H| = [N_G(H)/H] \equiv [G:H] \pmod p$, so $N_G(H)/H$ has a subgroup $K/H$ of order $p$. Since $K \subset G$, $|K| = |K/H| \cdot |H| = p^{c+1}$, and 
$H \triangleleft K$, so we are done. $$\qed$$
$\text{\emph{Corollary.}}$ Suppose that $|G| = p^ab$ with $(p,b) = 1$, and $a \geq 1$. Let $H$ be a $p$-subgroup of $G$.
1. $H$ is a Sylow $p$-subgroup $\iff |H| = p^a$.
2. Every conjugate of a Sylow $p$-subgroup is a Sylow $p$-subgroup (weaker version of the [[2nd Sylow Theorem]]).
3. If $G$ has a unique Sylow $p$-subgroup, then $H \triangleleft G$.