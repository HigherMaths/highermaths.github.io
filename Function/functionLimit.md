# 函数的极限

在自变量的某个变化过程中, 如果对应的函数值无限接近于某个确定的数, 那么这个确定的数就叫做这一变化过程中 {% em %} 函数的极限{% endem %}

$$ {\lim \atop n \to \infty } x_n = a $$ 即 $$ {\lim \atop n \to \infty }f(n) = a $$

$$ \leftrightarrow  $$ 当 $$ n \to \infty $$ 时, $$ f(n) $$ 无限接近于确定的数 $$ a $$

$$ \leftrightarrow   \forall \varepsilon \gt 0 , \exists N \gt 0 $$ , 当 $$ n \gt N  $$ 时, 有 $$ \lvert f(n) - a \rvert \lt \varepsilon $$ 

主要研究两种情况:
1. $$ x \to x_0 $$ 时, 对应的函数值 $$ f(x) $$ 的变化情形
1. $$ x \to \infty $$ 时, 对应的函数值 $$ f(x) $$ 的变化情形

## 自变量趋于有限值时函数的极限

{% em %} 定义 {% endem %}  设函数 $$ f(x) $$ 在点 $$ x_0 $$ 的某一去心邻域内有定义, 如果存在常数 $$ A $$, $$ \forall \varepsilon \gt 0 , \exists \delta \gt 0 $$ , 当 $$ 0 \lt \lvert x - x_0 \rvert \lt \delta $$ 时, 有 

$$ \lvert f(x) - A \rvert \lt \varepsilon $$, 

那么常数 $$ A $$ 就叫做函数 $$ f(x) $$ 当 $$ x \to x_0 $$ 时的极限, 记作

$$ {\lim \atop x \to x_0 }f(x) = A $$ 或 $$ f(x) \to A $$ ( 当 $$ x \to x_0 $$ )

## 自变量趋于无穷大时函数的极限

 设函数 $$ f(x) $$ 当 $$ |x| $$ 大于某一正数时有定义, 如果在 $$ x \to \infty $$ 过程中, 对应的函数值 $$ f(x) $$ 无限接近于确定的数值 $$ A $$, 则称 $$ A $$ 为 $$ f(x) $$ 当 $$ x \to \infty $$ 是的极限

{% em %} 定义 {% endem %} 设函数 $$ f(x) $$ 当 $$ |x| $$ 大于某一正数时, 有定义, 如果存在常数 $$A$$ , 对于任意给定的正数 $$ \varepsilon $$ (不论它多小), 总存在着正数 $$X$$, 使得当 $$ x $$ 满足不等式 $$ |x| > X $$, 对应的函数值 $$ f(x) $$都满足不等式

$$ \lvert f(x) - A \rvert \lt \varepsilon $$

那么常数 $$ A $$ 就叫做函数 $$ f(x) $$当 $$ x \to \infty $$时的极限,记作:

$$ {\lim \atop x \to \infty}f(x) = A , $$ 或 $$f(x) \to A $$ (当 $$ x \to \infty $$)

## 函数极限的性质

就以 " $$ {\lim \atop (x \to x_0)}f(x) $$ 这种情势为代表给出关于函数极限性质的一些定理, 并就其中的一个给出证明

### 定理一 函数极限的唯一性

如果 $$ {\lim \atop x \to x_0}f(x) $$ 存在, 那么这极限唯一

### 定理二 函数及吸纳的局部有界性

如果 $$ {\lim \atop x \to x_0}f(x) $$存在，　那么存在常数　$$ M > 0 $$和　$$ \delta > 0 $$ , 使得当 $$ 0 < |x - x_0| < \delta $$ 时, 有 $$ |f(x)| \leq M $$

### 定理三 函数极限的局部保号性

如果 $$ {\lim \atop x \to x_0}f(x) = A $$, 且 $$ A > 0 $$ ( 或 $$ A < 0 $$ ), 那么存在 $$ \delta > 0 $$, 使得当 $$ 0 < |x - x_0 | < \delta $$ 时, 有 $$ f(x) > 0 $$ (或 $$ f(x)< 0 $$ ).

### 定理四 函数极限与数列及吸纳的关系

若极限 $$ {\lim \atop x \to x_0}f(x)$$存在, $$ {x_n} $$ 为函数 $$ f(x) $$ 的定义域内任一收敛于 $$ x_0 $$ 的数列, 且满足 $$ x_n \neq x_0 (n \in N_+) $$, 那么相应的函数值数列 $$ {f(x_n)} $$ 必收敛, 且 $$ {\lim \atop n \to \infty}f(x_n) = {\lim \atop x \to x_0}f(x) $$ 