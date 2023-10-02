Theorem 12 (Primary Decomposition Theorem).
Let $T$ be a linear operator on the finite dimensional space $V$ over the field $F$. Let $p$ be the minimal polynomial for $T$,
$$
p = p_1^{r_1} \dots p_k^{r_k}
$$
where the $p_i$ are the distinct irreducible monic polynomials over $F$, and the $r_i$ are positive integers. Let $W_i$ be the null space of $p_i(T)^{r_i}$ for $i = 1, \dots, k$. Then
- $V$ is the direct sum of $W_1, \dots, W_k$
- $W_1, \dots, W_k$ are invariant subspaces under $T$
- if $T_i$ is the induced operator on $W_i$ by $T$, the minimal polynomial for $T_i$ is $p_i^{r_i}$

Definition.
Let $N$ be a linear operator on $V$ over the field $F$. $N$ is called **nilpotent** if there exists positive integer $r$ s.t. $N^r = 0$

Example.
$T$의 minimal polynomial이 linear polynomial들의 곱으로 factor될 때, primary decomposition theorem에 의해서 각각 $(T-c_iI)^{r_i}$의 null space들의 direct sum으로 표현됨을 알 수 있다.

Theorem 13.
Let $T$ be a linear operator on the finite-dimensional vector space $V$ over the field $F$. Suppose that the minimal polynomial for $T$ decomposes over $F$ into a product of linear polynomials. Then there is a diagonalizable operator $D$ on $V$ and a nilpotent operator $N$ on $V$ such that
- $T = D + N$
- $DN = ND$
The diagonalizable operator $D$ and the nilpotent operator $N$ are uniquely determined by (i), (ii) and each of them is a polynomial in $T$.

$D$는 $c_1E_1 + \dots + c_kE_k$ 형태이고, $N$은 $(T-c_1I)E_1 + \dots + (T-c_kI)E_k$ 형태이다. 이 둘은 commute하고, 각각 $T$에 대한 polynomial 형태이다. Vector space가 algebraically closed field 위에서 정의돼 있다면, 임의의 linear operator $T$는 위와 같은 성질을 만족하는 $D, N$의 합으로 표현할 수 있다.



