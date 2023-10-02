Definition.

Lemma. TFAE
- $W_1, \dots, W_k$ are independent
- for each $j, 2 <= j <= k$ 

Example 13.
distinct characteristic value에 associate된 characteristic space들은 independent하다.
(Theorem 2의 Lemma 참고)

Theorem 9.
if $V$ is the direct sum of $W_1, \dots, W_k$ then there exist $k$ linear operators $E_1, \dots, E_k$ such that
- $E_i$ is the projection
- $E_iE_j = 0$ for $i \neq j$
- $I = E_1 + \dots + E_k$
- the range of $E_i$ is $W_i$
Conversely, 1, 2, 3번 성질을 만족하는 linear operator $E_i$가 있고 $E_i$들의 range를 $W_i$라고 할 때 $V$는 $W_i$들의 direct sum으로 표현될 수 있다.

vector space $V$가 $W_1, \dots, W_n$의 direct sum으로 표현될 때, $V$의 임의의 벡터들은 unique한 tuple $(\alpha_1, \dots, \alpha_n), \;\alpha_i \in W_i$로 나타낼 수 있다.