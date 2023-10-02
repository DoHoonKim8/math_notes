Thm 10.
finite dimensional inner pd. space $V, W$ 가 있고, $dim V = dim W$이고, $T \in L(V, W)$가 있을 때, 다음 조건들이 동치이다.
- $T$ preserves inner product
- $T$ is an inner product isomorphism
- $T$ sends every orthonormal basis for $V$ onto an orthonormal basis for $W$
- $T$ sends some orthonormal basis for $V$ onto an orthonormal basis for $W$

Corollary.
$V, W$가 finite dimensional inner product space라고 할 때, $V, W$가 isomorphic할 필요충분조건은 $dim V = dim W$이다.
	$V$의 임의의 orthonormal basis를 $W$의 orthonormal basis에 mapping하는 linear transformation을 생각하면 됨.

**finite dimension이 아니라면, inner product를 preserve해도 isomorphism이 아닐 수도 있다.**

Theorem 11.
$V, W$가 inner product space이고, $T \in L(V, W)$이면, $T$가 inner product를 preserve할 필요충분조건은 $||T \alpha|| = ||\alpha||$ 이다.
(=>) trivial.
(<=) polarization identity

Definition.
**Unitary operator**는 inner product space $V$에서 자기 자신으로 가는 isomorphism이다.

Theorem 12.
Inner product space $V$에서 linear operator $U$가 있을 때, $U$가 unitary operator일 필요충분조건은 adjoint $U^*$가 존재하고, $UU^* = U^*U = I$ 를 만족하는 것이다.

Definition.
A complex $n \times n$ matrix $A$ is called unitary if $A^*A = I$
($A^*$는 conjugate transpose를 의미)

matrix $A$가 unitary일 필요충분조건은 $A$의 row들과 column들이 각각 orthonormal set을 이루는 것이다.

Theorem 13.
finite dimensional vector space $V$가 있고, $U$가 $V$ 위에서의 unitary operator일 필요충분조건은 $U$가 matrix $A$로 represent될 때, $A$가 unitary matrix가 되게 하는 orthonormal basis for $V$가 존재하는 것이다.

Definition.
A real or complex $n \times n$ matrix $A$ is orthogonal if $A^TA = I$

Theorem 14.
For every invertible complex $n \times n$ matrix $B$에 대해 $MB$가 unitary가 되게끔 하는 diagonal entry들이 positive, lower triangular인 unique한 matrix $M$이 존재한다.

$B$의 row들이 $\mathbb{C}^n$을 span하고, Gram-Schmidt process를 통해 orthonormal한 row들의 set을 만들어낼 수 있다. Orthonormal한 row들로 이루어진 matrix는 unitary matrix가 된다.

Definition.
Let $A$ is unitarily equivalent to $B$ if there exists unitary matrix $P$ s.t. $A = P^{-1}AP$

