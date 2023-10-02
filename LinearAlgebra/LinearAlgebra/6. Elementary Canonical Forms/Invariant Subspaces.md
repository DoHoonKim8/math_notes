Definition.
Let $T$ be a linear operator on $V$, and $W$ is a subspace of $V$. $W$ is **invariant under $T$** if $T(W)$ is contained in $W$.

Lemma.
Let $W$ be an invariant subspace for $T$. The characteristic polynomial for the restricted operator $T_W$ divides the characterisic polynomial for $T$. The minimal polynomial for the restricted operator $T_W$ also divides the minimal polynomial for $T$.

Definition.
Let $W$ be an invariant subspace for $T$ and let $\alpha$ be a vector in $V$.
The **T-conductor of $\alpha$ into W** is a set of polynomials such that $g$ in a set satisfies that $g(T)\alpha$ is contained in $W$.

Lemma.
If $W$ is a subspace invariant for $T$, then $W$ is invariant under every polynomial for $T$. Thus for every $\alpha$ in $V$ $T$-conductor of $\alpha$ into $W$ forms a polynomial ideal.

Lemma.
Let $V$ be a finite-dimensional vector space over the field $F$. Let $T$ be a linear operator on $V$. If the minimal polynomial of $T$ is factored by the following:
$$
(x-c_1)^{r_1} \dots (x-c_n)^{r_n}
$$
Let $W$ be a proper subspace of $V$ which is invariant under $T$ then there exists a vector $\alpha$ in $V$ such that
- $\alpha$ is not in $W$
- $(T-cI)\alpha$ is in $W$ for some characteristic value $c$

Theorem 5.
Let $V$ be a finite-dimensional vector space over the field $F$. Let $T$ be a linear operator on $V$. $T$ is **triangulable** if and only if the minimal polynomial of $T$ is the product of linear factors.

Corollary.
Let $F$ be an algebraically closed field. Every $n \times n$ matrix over $F$ is similar to a triangular matrix.

Theorem 6.
$T$ is diagonalizable if and only if the minimal polynomial for $T$ has the form
$$
(x-c_1) \dots (x-c_k)
$$
