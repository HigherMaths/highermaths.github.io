# 极限存在准则

{% em %} 准则 I
{% endem %}
夹逼准则

重要极限  $$ {\lim \atop x \to 0}{\frac{\sin x}{x}} = 1 $$

{% em %} 准则 II
{% endem %}
单调有界数列收敛准则

重要极限  $$ {\lim \atop x \to \infty}\lgroup 1 + \frac{1}{x} \rgroup^x = e $$

## 夹逼准则

{% em %} 准则 I
{% endem %}
设数列 $$ \{ x_n \} $$ , $$ \{ y_n \} $$ 及 $$ \{ z_n \} $$ 满足: 
1. 存在某个正整数 $$ n_0 $$, 当 $$ n > n_0 $$ 时, 有
  1. $$ y_n \leq x_n \leq z_n $$;
1. $$ {\lim \atop n \to \infty}y_n = a , {\lim \atop n \to \infty}z_n = a $$, 
则 $$ {\lim \atop n \to \infty}x_n $$ 存在且 $$ {\lim \atop n \to \infty}x_n = a $$

{% em %} 准则 I'
{% endem %}如果
1. 存在 $$ x_0 $$ 的某个去心邻域 $$ {o \atop U}(x_0) $$ (或正整数 $$ X $$), 当 $$ x \in {o \atop U}(x_0) $$ (或 $$ |x| > X $$)时, 有 $$ g(x) \leq f(x) \leq h(x) $$;
1. $$ {\lim \atop x \to x_0}g(x) = A , {\lim \atop x \to x_0}h(x) = A $$ (或 $$ {\lim \atop x \to x_\infty}g(x) = A , {\lim \atop x \to x_\infty}h(x) = A $$)

则 $$ {\lim \atop x \to x_0}f(x)$$ 存在且等于 $$ A $$, (或$$ {\lim \atop x \to x_\infty}f(x)$$  存在且等于 $$ A $$)

上面的准则 I 和 I' 称为 {% em %}夹逼准则 {% endem %}

## **单调有界数列收敛准则**
{% em %} 定义
{% endem %}
如果数列 $$ {x_n} $$ 满足 $$ x_1 \leq x_2 \leq \cdots \leq x_n \leq \cdots $$, 则称改数列是 {% em %}单调增加{% endem %}的; 如果数列 $$ {x_n} $$ 满足 $$ x_1 \geq x_2 \geq \cdots \geq x_n \geq \cdots $$, 则称改数列是 {% em %}单调减少{% endem %}的.

单调增加或者单调减少的数列总成为{% em %}单调数列{% endem %}