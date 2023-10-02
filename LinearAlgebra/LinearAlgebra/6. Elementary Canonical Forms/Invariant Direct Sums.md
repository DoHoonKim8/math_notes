Theorem 10.

$V$가 $W_1, \dots, W_k$들의 direct sum으로 표현되고, 각 $W_i$와 associate된 projection $E_i$가 존재한다. $V$ 위에서 정의된 linear operator $T$에 대해서 $W_i$가 invariant할 필요충분 조건은 $T$와 각 $E_i$가 commute하는 것이다.

Theorem 11.

$T$가 finite dimensional한 vector space $V$에서 정의된 linear operator이고, $T$가 diagonalizable하고, $c_1, \dots, c_k$가 distinct한 characteristic value들이라고 할 때, linear operator $E_1, \dots, E_k$가 존재하고 다음 조건을 만족한다.

- $T = c_1E_1 + \dots + c_kE_k$
- $I = E_1 + \dots + E_k$
- $E_iE_j = 0$ if $i \neq j$
- $E_i$ is a projection
- the range of $E_i$ is the characteristic space for $T$ associated with $c_i$

Conversely, 만약 distinct한 scalars $c_1, \dots, c_k$가 존재하고, $k$개의 non-zero linear operator $E_1, \dots, E_k$가 존재해서 (i), (ii), (iii)을 만족한다면, $T$가 diagonalizable하다.

Theorem 11의 핵심은 1번 property에 있는 듯 하다. Diagonalizable한 linear operator $T$의 characteristic space들은 $T$에 대해 invariant하고, underlying space는 $T$의 characteristic space들의 direct sum으로 표현될 수 있다. 이 때 $T$를 각 characteristic space에 restriction한 operator들은 $c_iE_i$가 된다.
