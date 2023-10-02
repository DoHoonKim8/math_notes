Def.
$f$: a bilinear form on $V$
the matrix of $f$ in the ordered basis $A_{ij}=f(\alpha_i, \alpha_j)$

bilinear form의 matrix의 basis를 변경하면 어떻게 될까?
$$
	[f]_{\mathcal{B}'} = P^t[f]_{\mathcal{B}}P
$$
$P$는 $\mathcal{B}'$에 대한 coordinate를 $\mathcal{B}$에 대한 coordinate로 변환하는 matrix

bilinear form의 rank를 정의할 수 있다.

Corollary.
$f$가 $n$-dimensional인 vector space 위에서의 bilinear form이라면, 다음 조건들이 동치이다.
- rank(f) = n
- for every non-zero $\alpha$, there exists $\beta$ s.t. $f(\alpha, \beta) \neq 0$
- for every non-zero $\beta$, there exists $\alpha$ s.t. $f(\alpha, \beta) \neq 0$
위의 조건을 하나라도 만족하면 $f$를 non-degenerate라고 함