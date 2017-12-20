# 极限运算法则

在这儿，我们主要讨论两种运算法则

## 极限的四则运算法则

“$$\lim$$” 下面没有标明自变量的变化过程的，我们约定结论对 $$ x \to x_0 $$、$$x \to x_\infty$$、$$x \to {x_0}^+ $$ 等所有变化过程都成立

{% em %}定理
{% endem %}
有限个无穷小的和是无穷小  
有界函数与无穷小的乘积是无穷小.

{% em %}注
{% endem %}
这里函数的有界性只要求在无穷小的自变量变化范围内成立.

{% em %}推论
{% endem %}
常数与无穷小的乘积是无穷小.  
有限个无穷小的乘积是无穷小.

{% em %}注
{% endem %}
无穷小的和、差、积仍是无穷小。

{% em %}定理
{% endem %}
如果 $$ {\lim f(x) = A}$$，$$ \lim g(x) = B$$ , 那么
1. $$ \lim [f(x) \pm g(x)] = \lim f(x) \pm \lim g(x) = A \pm B$$；
1. $$\lim [f(x) \cdot g(x)] = \lim f(x) \cdot \lim g(x) = A \cdot B$$；
1. 若又有 $$ B \neq 0 $$, 则 $$ \lim \frac{f(x)}{g(x)} = \frac{\lim f(x)}{\lim g(x)} = \frac{A}{B} $$ .

{% em %}注
{% endem %}
1. 次定理就是极限的**四则运算法则**, 也即函数的和、差、积、商（$$B \neq 0$$）的极限等于函数极限的和、差、积、商.
1. {% em %}推论
{% endem %}
若$$ c $$ 为常数, 则 $$ \lim[cf(x)] = c\lim f(x) = cA$$，若 $$ n $$ 为正整数, 则 $$ \lim[f(x)]^n = [\lim f(x)]^n = A^n $$.
1. {% em %}定理
{% endem %}
设有数列 $$ \{x_n\} $$ 和 $$ \{y_n\} $$ , 如果 $$ {\lim \atop n \to \infty}x_n = A$$, $$ {\lim \atop n \to \infty}y_n = B$$, 那么
* $$ {\lim \atop n \to infty}(x_n \pm y_n) = A \pm B $$;
* $$ {\lim \atop n \to infty}(x_n \cdot y_n) = A \cdot B $$;
* 当 $$ y_n \neq 0 (n = 1,2,\mathellipsis)$$, $$ B \neq 0 $$ 时 $$ {\lim \atop n \to \infty}\frac{x_n}{y_n} = \frac{A}{B}$$.

## 符合函数的极限运算法则

{% em %}定理
{% endem %}
设函数 $$ y = f[g(x)] $$ 由函数 $$ y = f(u) $$ 和 $$ u = g(x) $$ 复合而成, $$ f[g(x)] $$ 在点 $$ x_0 $$ 的某一去心邻域内有定义, 若 $$ {\lim \atop x \to x_0 }g(x) = u_0 $$, $$ {\lim \atop u \to u_0}f(u) = A $$, 且存在 $$ \delta_0 > 0 $$, 当 $$ x \in {o \atop U} (x_0, \delta_0)$$ 时, 有 $$ g(x) \neq u_0 $$,则  
  $$ {\lim \atop x \to x_0}f[g(x)] = {\lim \atop u \to u_0}f(u) = A $$

{% em %}注
{% endem %}
1. 此定理的条件是保证 $$ {\lim \atop x \to x_0}f[g(x)] $$ 的极限存在;
1. 在一定条件, 此定理对自变量的其他变化情形也成立, 如若 $$ {\lim \atop x \to \infty}g(x) = u_0, {\lim \atop u \to u_0}f(u) = A$$, 则 
  $$ {\lim \atop x \to x_0}f[g(x)] = {\lim \atop u \to u_0}f(u) = A $$
1. 此定理是在求极限是进行变量代换的依据 