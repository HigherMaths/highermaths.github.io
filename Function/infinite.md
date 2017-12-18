# 无穷大与无穷小

$$ {\lim \atop x \to 2} \lgroup { {\ln x} \over{\sqrt{x^2 - 1}}} + e^{1 \over{x-3}} \rgroup $$

### 无穷小

{% em %} 定义
{% endem %}
 如果 $$ f(x) $$ 当 $$ x \to x_0 $$ (或$$ x \to \infty $$)时的极限为零, 则称 $$ f(x) $$ 为当 $$ x \to x_0 $$ (或 $$ x \to \infty $$)时的{% em %}无穷小{% endem %}. 
特别地, 以零为极限的 $$ \{ x_n \} $$ 也称为 $$ n \to \infty $$ 时的{% em %}无穷小{% endem %}.

1. 除了常数 0 时无穷小, 其他任何常数, 即便是这个数的绝对值很小很小, 都不是无穷小
1. 无穷小时以0为极限的函数

{% em %} 定理
{% endem %}
在自变量 $$ x $$ 的同一变化过程中, 函数 $$ f(x) $$ 有极限 $$ A $$ 的充分必要条件是

$$ f(x) = A + \alpha (x) $$ , 其中 $$ \alpha (x) $$ 是无穷小.

### 无穷大

如果函数 $$ f(x) $$ 当 $$ x \to x_0 $$ ( 或 $$ x \to \infty $$) 时, 其绝对值 $$ \lvert f(x) \rvert $$ 无限增大, 则称函数 $$ f(x) $$  为当 $$ x \to x_0 $$ ( 或 $$ x \to \infty $$) 时的 {% em %} 无穷大 {% endem %}

{% em %} 定义
{% endem %}
设函数 $$f(x)$$ 在 $$ x_0 $$ 的某一去心邻域内有多定义 ( 或 $$ |x| $$ 大于某一正数时有定义). $$ \forall M > 0 , \exists \delta > 0 $$ ( 或 $$ X > 0$$), 当 $$ 0 < \lvert x - x_0 \rvert < \delta $$ (或 $$ |x|> X $$)时, 恒有 $$ |f(x)| > M $$, 则称函数 $$ f(x) $$ 为 $$ x \to x_0 $$ (或 $$ x \to \infty $$)时的 **无穷大**

1. 我们也说 “函数的极限为无穷大”，并记作
  $$ {\lim \atop x \to x_0}f(x) = \infty $$ 或 $$ {\lim \atop x \to \infty}f(x) = \infty $$，等等 
  如果 $$ {\lim \atop x \to {x_0}^-}f(x) = \infty $$ 或 $$ {\lim \atop x \to {x_0}^+}f(x) = \infty $$,则  
  直线 $$ x = x_0 $$ 是函数 $$ y = f(x) $$ 的图形的 **铅直渐近线**
1. $$ {\lim \atop x \to x_0}f(x) = + \infty $$, $$ {\lim \atop x \to \infty}f(x) = + \infty $$, $$ {\lim \atop x \to x_0}f(x) = - \infty $$ , 等等

{% em %} 定理
{% endem %} 在自变量 $$x$$ 的同一变化过程中，
如 果 $$f(x)$$ 是无穷大，则 $$ \frac{1}{f(x)}$$ 是无穷小；
如 果$$ f(x)$$ 是无穷小，且 $$ f(x) \neq 0 $$ ，则 $$ \frac{1}{f(x)}$$ 是无穷大. 
