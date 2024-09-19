# Orbits and Stabilizers
Given a group $G$ acting on a set $S$, the orbit $Gs$ of $s \in S$ is the set
$$\{gs \mid g \in G\}$$
and the stabilizer $G_s$ of $s \in S$ is the set
$$\{g \in G \mid gs = s\}.$$
$\text{\emph{Proposition.}}$ $$|Gs| = [G:G_s].$$
$\Pf$ Consider the a map of sets $f: \overbrace{G/G_s}^{\text{left cosets}} \to Gs$. Let $H = G_s$. Then let
$f(xH) = xs \in Gs$. It takes a bit more checking to verify that $f$ is a bijection, but intuitively it makes sense that the "kernel" of a map down to the orbit would be exactly the stabilizers. $$\qed$$