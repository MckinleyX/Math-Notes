# Fixed-Point Lemma
$\text{\emph{Lemma.}}$ Let $S$ be a $p$-group. Then 
$$|S^G| \equiv |S| \pmod{p}$$
$\Pf$ Let $|G| = p^n$, acting on a set $S$. If $x \not \in S^G$ then $1 < |Gx|$. But we know that the size of the orbit $|Gx|$ must divide $|G|$ (since the orbit is a coset), and since $G$ is a $p$-group, $p \mid |Gx|$. But $S = S^G \sqcup \{\text{nontrivial orbits}\}$, but since all of the
nontrivial orbits are $0 \pmod p$, $S \equiv S^G \pmod{p}$. $$\qed$$