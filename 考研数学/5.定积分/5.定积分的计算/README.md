# 定积分的计算

* [定理内容](#定理内容)
* [换元积分法](#换元积分法)
* [分部积分法](#分部积分法)
* [重要结论](#重要结论)
* [经典例题](#经典例题)

## 定理内容

$$
若 f(x) 在 [a , b] 上有原函数 F(x) ，则 \int_a ^ {b}{f(x)}dx = F(b) - F(a) .
$$

$$
若 f(x) 在 [a , b] 上分段有原函数，则 \int_a ^ {b}{f(x)}dx = \int_a ^ {c}{f(x)}dx + \int_c ^ {b}{f(x)}dx = F_1(c_{-0}) - F_1(a) + F_2(b) - F_2(c_{+0}) .
$$

## 换元积分法

$$
设 f(x) 在 [a , b] 上连续，函数 x = \phi(t) 满足 \phi(\alpha) = a ， \phi(\beta) = b ， 且在 [\alpha , \beta] 上有连续的导数，值域为 R_{\phi} = [a , b] ，
\\
\int_a ^ {b}{f(x)}dx = \int_\alpha ^ {\beta}{f[\phi(t)]\phi(t)\prime}dt .
$$

## 分部积分法

$$
\int_a ^ {b}{u(x)v(x)\prime}dx = u(x)v(x)\prime|_a ^ {b} - \int_a ^ {b}{v(x)u(x)\prime}dx .
$$

## 重要结论

$$
设 f(x) 为连续的偶函数，则 \int_{-a} ^ {a}{f(x)}dx = 2\int_0 ^ {a}{f(x)}dx .
\\
设 f(x) 为连续的奇函数，则 \int_{-a} ^ {a}{f(x)}dx = 0 .
$$

$$
设 f(x) 是以 T 为周期的连续函数，则对任意的实数 a ，都有 \int_a ^ {a + T}{f(x)}dx = \int_0 ^ {T}{f(x)}dx .
\\
即在长度为一个周期的区间上的定积分，与该区间的起点位置无关.
$$

$$
设 f(x) 为连续函数，则 \int_a ^ {b}{f(x)}dx = \int_a ^ {b}{f(a + b - x)}dx （区间再现公式）.
$$

$$
华里士公式：
\\
\int_0 ^ {\frac{\pi}{2}}{\sin ^ n {x}}dx = \int_0 ^ {\frac{\pi}{2}}{\cos ^ n {x}}dx = 
$$









## 经典例题

$$
设 f(x + \frac{1}{x}) = \frac{x + x ^ 3}{1 + x ^ 4} ，求 \int_2 ^ {2\sqrt{2}}{f(x)}dx .
\\
\because f(x + \frac{1}{x}) = \frac{x + x ^ 3}{1 + x ^ 4} = \frac{x + \frac{1}{x}}{x ^ 2 + \frac{1}{x ^ 2}} = \frac{x + \frac{1}{x}}{(x + \frac{1}{x}) ^ 2 -2} ，
\\
\therefore f(x) = \frac{x}{x ^ 2 -2} ，
\\
\therefore \int_2 ^ {2\sqrt{2}}{f(x)}dx = \int_2 ^ {2\sqrt{2}}{\frac{x}{x ^ 2 -2}}dx = \frac{1}{2}\int_2 ^ {2\sqrt{2}}{\frac{1}{x ^ 2 -2}}d(x ^ 2 - 2) = \frac{1}{2}\ln{(x ^ 2 - 2)}|_2 ^ {2\sqrt{2}} = \frac{1}{2}(\ln{6} - \ln{2}) = \frac{1}{2}\ln{3} .
$$







