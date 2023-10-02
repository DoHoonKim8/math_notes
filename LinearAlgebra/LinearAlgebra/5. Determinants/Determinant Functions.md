임의의 $n \times n$ matrix에 대응되는 scalar 값인 Determinant가 존재하고, unique한 걸 증명하기 위해 이 장에서는 특정 property를 만족하는 determinant function을 정의하고, 이 determinant function이 최종적으로 unique하다는 사실을 증명한다.

Definition. n-linear

Lemma. a linear combination of n-linear functions is n-linear.

Definition. alternating
- $D(A) = 0$ if two rows of $A$ are equal
- If $A'$ is obtained from interchanging two rows of $A$, then $D(A') = -D(A)$

Definition. Determinant functions
$D$가 $n \times n$ matrix over $F$ 를 $F$로 대응하는 함수일 때,
n-linear, alternating, $D(I) = 1$
이면 $D$를 determinant function이라고 한다.

Lemma.
$D$ 가 n-linear function이고, 인접한 두 row가 같은 임의의 $n \times n$ 행렬 $A$에 대해서 $D(A) = 0$을 만족한다면, $D$는 alternating function이다.

Theorem 1. ($n \times n$ matrix에 대한 determinant function이 존재함을 보임)

