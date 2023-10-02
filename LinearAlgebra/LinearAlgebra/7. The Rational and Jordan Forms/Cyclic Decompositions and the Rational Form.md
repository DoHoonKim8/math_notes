Definition.
$T$-admissible

$W$ is $T$-invariant and the complementary subspace is also $T$-invariant then $W$ is $T$-admissible

Theorem 3.(Cyclic Decomposition Theorem)
$V$: finite-dimensional vector space
Let $W_0$ be proper $T$-admissible subspace, then there exist non-zero vectors $\alpha_1, \dots, \alpha_r$ such that $V$ is direct sum of $W_0, Z(\alpha_1; T), \dots, Z(\alpha_r; T)$, and the corresponding $T$-annihilators $p_1, \dots, p_r$ such that $p_{i+1}$ divides $p_i$ for $i = 1, \dots, r-1$.

- Some points
	- $p_1$ is the $T$-conductor of $V$ into $W_0$

$V$가 non-zero vector들 $\alpha_1, \dots \alpha_k$들이 존재해서 $Z(\alpha_1; T), \dots, Z(\alpha_k; T)$들의 direct sum으로 이루어질 때, $T$-annihilator of $\alpha_1$이 $T$의 minimal polynomial과 같다. 따라서 $T$의 minimal polynomial과 $T$의 characteristic polynomial이 같으면, $\alpha_1$이 $T$의 cyclic vector가 된다. 반대로 $T$가 cyclic vector를 가진다면, $T$의 minimal polynomial의 degree가 vector space의 dimension과 같아져, 결국 $T$의 characteristic polynomial과 같아지게 된다.

Theorem 4.
$T$: linear operator on a finite-dimensional vector space $V$
$p, f$ be the minimal and characteristic polynomial for $T$
- $p$ divides $f$
- $p$ and $f$ have the same prime factors, except for multiplicities
- If
	$$
	p = f_1^{r_1} \dots f_k^{r_k}
$$
then
$$
f = f_1^{d_1} \dots f_k^{d_k} \;
$$
$V$를 $T$를 이용해서 cycle decomposition을 하면, 각 cyclic vector들의 $T$-annihilator가 cyclic subspace위에 $T$를 restrict한 operator의 minimal polynomial이자, characteristic polynomial이 된다. 그리고 각 cyclic subspace들은 $T$에 대해 invariant하기 때문에, cyclic vector들의 $T$-annihilator들의 곱이 $T$의 characteristic polynomial이 된다.


**rational form**
$T$를 이용해 $V$를 cycle decomposition하고 나면, 각 cyclic subspace들에 $T$를 restrict한 operator들은 cyclic ordered basis에 의해 companion matrix로 represent된다. 그리고 companion matrix에 의해 표현되는 다항식은 각 operator들의 minimal polynomial, 즉 $T$-annihilator가 된다.
이렇게 companion matrix들의 direct sum으로 표현되는 matrix를 rational form이라고 부른다.

