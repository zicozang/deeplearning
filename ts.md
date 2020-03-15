
## 7. 상관 <sub>Correlation</sub>

상관은 2개 변수 간에 어떤 선형적인 관계가 있는지를 분석하는 방법이다.  
좀 더 자세하게 얘기하면 2개 변수의 공분산을 정규화한 것으로,  
변수 간의 상관관계의 정도를 상관계수<sub>Correlation Coefficient</sub>로 나타낸다.

$$Cor(x,y) = \frac{Cov(x,y)}{std(x) \times std(y)}$$

- $std(x)$는 표본변수 $x$의 표준편차를 나타내고, $std(y)$는 표본변수 $y$의 표준편차다.
- $Cor(x,y)$는 공분산을 정규화한 것이므로 $[-1,1]$사이의 값을 가진다.

공분산과 달리 상관관계 값은 방향성과 함께 상관관계의 정도를 나타낸다.  
값이 1에 가까울수록 **양의 강한 상관관계**, -1에 가까우면 **음의 강한 상관관계**를 의미하며  
값이 0인 경우는 선형적으로 상관관계가 없다는 것을 의미한다.

- $Cor(x,y) > 0$ 양의 상관관계
- $Cor(x,y) = 1$ x와 y가 동일
- $Cor(x,y) < 0$ 음의 상관관계
- $Cor(x,y) = -1$ x와 y가 반대 방향으로 동일
- $Cor(x,y) = 0$ x와 y는 선형적인 상관관계가 없음

[그림 7-1] 상관관계   
<img width="500" src="https://internal.ncl.ac.uk/ask/numeracy-maths-statistics/images/R_value.png" title="">

상관관계를 나타내는 상관계수는 피어슨<sub>Pearson</sub>, 스피어만<sub>Spearman</sub>, 캔달<sub>Kendal</sub> 등 여러가지 있으나  
가장 많이 사용하는 것은 피어슨 상관계수다.
