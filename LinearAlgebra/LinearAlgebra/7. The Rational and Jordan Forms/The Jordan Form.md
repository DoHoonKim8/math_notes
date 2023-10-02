$T$가 finite dimensional한 vector space $V$ 위에서의 linear operator이고, $T$의 minimal polynomial이 linear polynomial들의 곱으로 factor가 된다고 하자. 이때, primary decomposition theorem에 의해서 $V$가 $(T-c_iI)^{r_i}$의 null space들의 direct sum으로 표현된다. 이 때 $T$를 restrict한 operator를 $T_i$라고 하면, $(T_i-c_iI)$가 nilpotent operator가 됨을 알 수 있다. $T_i$는 $N_i + c_iI$와 같음을 알 수 있다.
Nilpotent operator로 subspace를 다시 cycle decompose하고, companion matrix의 direct sum으로 표현됨을 알 수 있다. Nilpotent operator의 minimal polynomial은 $x^{r_i}$이고(by Primary Decomposition Theorem), companion matrix의 크기는 오른쪽으로 갈수록 점점 작아짐을 알 수 있다.

linear operator의 minimal polynomial이 linear polynomial들의 곱으로 표현된다면,
먼저 primary decomposition으로 vector space를 direct sum으로 표현할 수 있고,
각 subspace를 cyclic decompose를 통해 한 번 더 direct sum으로 표현할 수 있다.

각 subspace = $(T-c_iI)^{r_i}$의 null space
각 subspace의 cyclic subspace의 개수 = $(T-c_iI)$의 nullity
=> $T$ is diagonalizable하기 위해서는 $(T-c_iI)$의 nullity가 $(T-c_iI)^{r_i}$의 nullity와 같아야 한다.

이런 형태의 matrix를 **Jordan form**이라고 부른다.

