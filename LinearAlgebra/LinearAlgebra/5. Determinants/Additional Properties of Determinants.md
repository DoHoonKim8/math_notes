matrix의 한 row(column)의 multiple을 다른 row(column)에 더했을 때, 원래 matrix의 determinant와 동일한 값을 가진다.

$$
det A = \sum_{i=1}^n(-1)^{i+j}A_{ij}detA(i|j)
$$

$C_{ij} = (-1)^{i+j}detA(i|j)$ is called the cofactor of $i, j$ entry of $A$

$$
det A = \sum_{i=1}^nC_{ij}A_{ij}
$$
fact:
$\sum_{i=1}^nC_{ij}A_{ik} = 0$ if $j \neq k$

adjoint matrix of A is the transpose of the matrix which $(i, j)$ entry is the cofactor of $i, j$ entry of $A$
$(adj A)_{ij} \;= \;C_{ji} \;= \;(-1)^{i+j}det A(j|i)$

$(adj A)A \;= \;(det A)I$

also, $A(adj A) \;= \;(det A)I$

Theorem 4.
$A$가 $n \times n$ matrix일 때, $A$가 invertible하기 위한 필요충분조건은 $det A \neq 0$인 것이다. $A$가 invertible하다면, $A$의 unique한 inverse는 다음과 같다:
$$
A^{-1} = (det A)^{-1}(adj \;A)
$$
$A$가 어느 commutative ring에서 정의됐는지에 따라 $(det A)^{-1}$가 존재하지 않을 수도 있기 때문에 주의 필요.

### Cramer's rule
