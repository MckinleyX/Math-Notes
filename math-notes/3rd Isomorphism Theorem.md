If $H,K$ are normal subgroups of $G$ such that
$K \subset H$, then $H/K$ is a normal subgroup of $G/K$, and 
$(G/K)/(H/K) \simeq G/H$.
$\Pf$ Let $\pi_H$, $\pi_K$ be the natural morphisms as below:
```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd} G & {G/H} \\ {G/K} \arrow["{\pi_H}", from=1-1, to=1-2] \arrow["{\pi_k}"', from=1-1, to=2-1] \arrow["{\exists!\bar{\pi}_H}"', dashed, from=2-1, to=1-2] \end{tikzcd}
\end{document}
```
Since $K \subset \ker \pi_H$, by the [[Universal Property of the Quotient]], there exists
a unique homomorphism from $G/K$ to $G/H$ making this diagram commute.

Also, by the [[1st Isomorphism Theorem]] we have that $(G/K)/\ker(\bar{\pi}_H) \simeq \Img\bar\pi_H$.
Well, $\ker(\bar\pi_H)$ is exactly $\pi_K(\ker(\pi_H)) = \pi_K(H) = H/K$, and $\Img \bar\pi_H$ is $G/H$ since
$\pi_K$ and $\pi_H$ are both surjective. $\qed$ $$\qed$$