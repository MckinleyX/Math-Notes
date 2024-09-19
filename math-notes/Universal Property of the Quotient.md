Let $G$ be a group$ $N \triangleleft G$. If $f : G \to G'$ is a group homomorphism such that $N \subset \ker f$. Then there exists a unique $\bar{f} : G/N \to G'$ such that $\bar{f} \circ \pi = f$, making this diagram commute:
```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}
	G & {G'} \\
	{G/N}
	\arrow["f", from=1-1, to=1-2]
	\arrow["\pi"', from=1-1, to=2-1]
	\arrow["{\exists! \bar{f}}"', dashed, from=2-1, to=1-2]
\end{tikzcd}

\end{document}
```
