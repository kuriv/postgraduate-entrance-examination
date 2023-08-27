# 柯西中值定理

* [定理内容](#定理内容)
* [经典例题](#经典例题)
  * [例题一](#例题一)
  * [例题二](#例题二)

## 定理内容

$$
定义：如果函数 f(x) 及 F(x) 满足在闭区间 [a , b] 上连续，在开区间 (a , b) 内可导，且对任一 x \in (a , b) ， F(x) \neq 0 ，
\\
那么在 (a , b) 内至少存在一点 \xi (a \lt \xi \lt b) ，使得 \frac{f(b) - f(a)}{F(b) - F(a)} = \frac{f(\xi)\prime}{F(\xi)\prime} .
$$

## 经典例题

### 例题一

$$
令参数方程 y = 
\begin{cases}
x = f(t) ， \\
y = g(t)
\end{cases}
\\
则可知点 A(f(a) , g(a)) ，点 B(f(b) , g(b)) ，
\\
\therefore k_{AB} = \frac{g(b) - g(a)}{f(b) - f(a)} ，
\\
\therefore \frac{dy}{dx}|_{t = \xi} = \frac{g(\xi)\prime}{f(\xi)\prime} ，
\\
由柯西中值定理得， \frac{g(b) - g(a)}{f(b) - f(a)} = \frac{g(\xi)\prime}{f(\xi)\prime} ，
\\
\therefore 由此可见，柯西中值定理实际上是拉格朗日中值定理在参数方程下的推广.
$$

### 例题二

$$
如：设 f(x) 在 [a , b] 连续，在 (a , b) 内可导 (a \gt 0) ，证明 \exists\xi \in (a , b) ，使得 \frac{f(b) - f(a)}{b - a} = \frac{{\xi ^ 2}{f(\xi)\prime}}{ab} .
\\
证明如下：先将等式两边同时除以 ab ，则 \frac{f(b) - f(a)}{\frac{1}{a} - \frac{1}{b}} = \frac{{\xi ^ 2}{f(\xi)\prime}}{1} ，
\\
随后将右式上方 \xi ^ 2 移到下方分母处，则 \frac{f(b) - f(a)}{\frac{1}{a} - \frac{1}{b}} = \frac{f(\xi)\prime}{\frac{1}{\xi ^ 2}} ，
\\
再将等式两边同时乘以 -1 ，则 \frac{f(b) - f(a)}{-\frac{1}{a} + \frac{1}{b}} = \frac{f(\xi)\prime}{-\frac{1}{\xi ^ 2}} ，即 \frac{f(b) - f(a)}{\frac{1}{b} -\frac{1}{a}} = \frac{f(\xi)\prime}{-\frac{1}{\xi ^ 2}} ，
\\
令 g(x) = \frac{1}{x} ，则 g(b) = \frac{1}{b} ， g(a) = \frac{1}{a} ，且 g(\xi)\prime = -\frac{1}{\xi ^ 2} ，
\\
\therefore \frac{f(b) - f(a)}{\frac{1}{b} -\frac{1}{a}} = \frac{f(b) - f(a)}{g(b) - g(a)} ， \frac{{f(\xi)\prime}}{-\frac{1}{\xi ^ 2}} = \frac{f(\xi)\prime}{g(\xi)\prime} ，
\\
\therefore \frac{f(b) - f(a)}{b - a} = \frac{{\xi ^ 2}{f(\xi)\prime}}{ab} .
$$



