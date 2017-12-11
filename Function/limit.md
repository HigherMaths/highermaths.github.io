# 数列的极限


数列是个特殊的函数   & 由特殊到一般  
数列极限是我们极限思想的起源  & 由简单到复杂  
数列极限是相对简单的而且直观的  &  由具体到抽象


## 数列的定义

如果按照某一法则, 对每个正整数 $$ n $$ , 对应着一个确定的实数 $$ x_n $$, 这些实数 $$ x_n $$ 按照下标 $$ n $$ 从小到大排列得到的一个序列

$$ x_1, x_2, x_3, . . . , x_n, ... $$

就叫做数列, 简记为 $$ \{ x_n \} $$.

数列中的每一个数叫做 {% em %}数列的项{% endem %}, 第 $$ n $$ 项 $$ x_n $$ 称之为数列的一般项或{% em %}通项{% endem %}

## 数列极限的定义

设 $$ \{ x_n \} $$ 为一数列, 如果存在常数 $$ a $$, 对于任意给定的正数 $$ \varepsilon $$, 总存在着一个正整数 $$ N $$, 使得对于 $$ n > N $$ 时的一切 $$ n $$, 不等式 $$ \lvert x_n -a \rvert < \varepsilon $$ 均成立, 则称常数 $$ a $$ 时数列 $$ \{ x_n \} $$ 的极限, 或者称数列 $$ \{ x_n \} $$ 收敛于 $$ a $$, 

记作 $$ {\lim \atop {n \to \infty} } x_n = a $$ , 或 $$ x_n \to a ( n \to \infty ) $$

如果上述 $$ a $$ 不存在, 则称数列 $$ \{ x_n \} $$ {% em %}没有极限{% endem %}, 或者说数列 $$ \{ x_n \} $$ 是发散的, 也说 $$ {\lim \atop {n \to \infty} } x_n $$ 不存在 

* 定义中 $$ \varepsilon $$ 的 "任意给定" 性极其重要;
* $$ N $$ 与 $$ \varepsilon $$ 有关, 它由 $$ \varepsilon $$ 的给定而确认
* $$ \forall $$ 表示 "任意给定",  $$ \exists $$ 表示 "存在" ;
  * $$ { \lim \atop {n \to \infty }} x_n = a \Leftrightarrow \forall \varepsilon > 0, \exists N > 0 $$ , 当 $$ n > N $$ 时, 恒有 $$ \lvert x_n -a \rvert < \varepsilon $$
* "数列 $$ \{ x_n \} $$ 的极限为 $$ a $$ "的几何解释:
  * 当 $$ n > N $$ 时, $$ x_n $$ 的点均落在 $$ ( a - \varepsilon , a + \varepsilon ) $$ 内, 至多有限个(至多有 $$ N $$ 个)是落在 $$ (a - \varepsilon , a + \varepsilon ) $$ 外的