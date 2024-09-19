# 2nd Sylow Theorem
If $H$ is a $p$-subgroup of a finite group $G$, and if $P$ is *any* Sylow $p$-subgroup of $G$, then there exists $x \in G$ with $H \subset xP^{-1}x$.
$\Pf$ $H$ acts on the set $S$ of left cosets of $P \subset G$, by left-translation. ($H \curvearrowright G/P$). (So for all $h \in H, g \in G$, $h(gP) = (hg)P$.)
By the [[Fixed Point Lemma]], $|S^H| \equiv |S| \pmod{p}$. 
Then $p \nmid [G:P] = |S|$, since $P$ is a maximal $p$-group.
As a result $|S^H| \neq 0$ so there exists $g \in G$ such that $h \cdot gP = gP$ for all $h \in H$. Then $g^{-1} h g$ \in P$, so $g^{-1}Hg \subseteq P \implies H \subseteq gPg^{-1}$. $$\qed$$