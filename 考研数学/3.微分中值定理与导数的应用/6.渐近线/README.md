# 渐近线

* [铅直渐近线](#铅直渐近线)
* [水平渐近线](#水平渐近线)
* [斜渐近线](#斜渐近线)
* [经典例题](#经典例题)

## 铅直渐近线

$$
如果 \lim_{x \to x_0+} f(x) = \infty ，或者 \lim_{x \to x_0-} f(x) = \infty ，则 x = x_0 为 f(x) 的铅直渐近线（此处的 x_0 是函数无定义点、定义区间端点、分段函数分段点）.
\\
如： x = 0 是 y = \frac{1}{x} 的铅直渐近线， x = k\pi + \frac{\pi}{2} （k \in Z） 是 y = \tan{x} 的铅直渐近线.
$$

## 水平渐近线

$$
如果 \lim_{x \to +\infty} f(x) = A_1 ，则 y = A_1 为 f(x) 的水平渐近线.
\\
如果 \lim_{x \to -\infty} f(x) = A_2 ，则 y = A_2 为 f(x) 的水平渐近线.
\\
如果 \lim_{x \to +\infty} f(x) = \lim_{x \to -\infty} f(x) = A ，则 y = A 为 f(x) 的水平渐近线.
\\
如： y = 0 是 y = e ^ x 的水平渐近线.
$$

## 斜渐近线

$$
如果 \lim_{x \to +\infty} \frac{f(x)}{x} = a_1 (a_1 \neq 0) ， \lim_{x \to +\infty} [f(x) - {a_1}x] = b_1 ，则 y = {a_1}x + b_1 是 f(x) 的斜渐近线.
\\
如果 \lim_{x \to -\infty} \frac{f(x)}{x} = a_2 (a_2 \neq 0) ， \lim_{x \to -\infty} [f(x) - {a_2}x] = b_2 ，则 y = {a_2}x + b_2 是 f(x) 的斜渐近线.
\\
如果 \lim_{x \to +\infty} \frac{f(x)}{x} = \lim_{x \to -\infty} \frac{f(x)}{x} = a (a \neq 0) ， \lim_{x \to +\infty} [f(x) - ax] = \lim_{x \to -\infty} [f(x) - ax] = b ，则 y = ax + b 是 f(x) 的斜渐近线.
$$

## 经典例题

$$
如：求曲线 y = f(x) 的渐近线.
\\
先找函数无定义点、定义区间端点、分段函数分段点，如果 \lim_{x \to x_0+} f(x) = \infty ，或者 \lim_{x \to x_0-} f(x) = \infty ，则 x = x_0 为铅直渐近线，
\\
然后判别 \lim_{x \to +\infty} f(x) 或者 \lim_{x \to -\infty} f(x) 是否为常数，如果是常数，则存在水平渐近线，
\\
如果不是常数，则最后判别 \lim_{x \to \infty} \frac{f(x)}{x} 是否为非零常数 a ，再求出 b = \lim_{x \to \infty} [f(x) - ax] ，当 a 、 b 都存在时，则存在斜渐近线.
$$

$$
如：求 f(x) = \frac{2x ^ 3}{x ^ 2 - 3x + 2} 的斜渐近线.
\\
\because a = \lim_{x \to \infty} \frac{f(x)}{x} = \lim_{x \to \infty} \frac{\frac{2x ^ 3}{x ^ 2 - 3x + 2}}{x} = \lim_{x \to \infty} \frac{2x ^ 2}{x ^ 2 - 3x + 2} = 2 ，
\\
\because b = \lim_{x \to \infty} [f(x) - ax] = \lim_{x \to \infty} [\frac{2x ^ 3}{x ^ 2 - 3x + 2} - 2x] = \lim_{x \to \infty} \frac{2x ^ 3 - 2x ^ 3 + 6x ^ 2 - 4x}{x ^ 2 - 3x + 2} = \lim_{x \to \infty} \frac{6x ^ 2 - 4x}{x ^ 2 - 3x + 2} = 6 ，
\\
\therefore 直线 y = 2x + 6 是 f(x) = \frac{2x ^ 3}{x ^ 2 - 3x + 2} 在 x \to \infty 时的斜渐近线.
$$

$$
如：求曲线 y = \frac{1}{x} + \ln(1 + e ^ x) 的渐近线.
\\
\because \lim_{x \to 0} [\frac{1}{x} + \ln(1 + e ^ x)] = \infty ，
\\
\therefore 直线 x = 0 是曲线 y = \frac{1}{x} + \ln(1 + e ^ x) 的铅直渐近线，
\\
\because \lim_{x \to -\infty} [\frac{1}{x} + \ln(1 + e ^ x)] = 0 ，
\\
\therefore 直线 y = 0 是曲线 y = \frac{1}{x} + \ln(1 + e ^ x) 在 x \to -\infty 时的水平渐近线，
\\
\because \lim_{x \to +\infty} \frac{f(x)}{x} = \lim_{x \to +\infty} [\frac{\frac{1}{x} + \ln(1 + e ^ x)}{x}] = \lim_{x \to +\infty} [\frac{1}{x ^ 2} + \frac{\ln(1 + e ^ x)}{x}] = \lim_{x \to +\infty} \frac{\ln[e ^ x(e ^ {-x} + 1)]}{x} = \lim_{x \to +\infty} \frac{\ln{e ^ x} + \ln(e ^ {-x} + 1)}{x} = 1 ，
\\
\because \lim_{x \to +\infty} [f(x) - b] = \lim_{x \to +\infty} [\frac{1}{x} + \ln(1 + e ^ x) - x] = \lim_{x \to +\infty} \ln[e ^ x(e ^ {-x} + 1)] - x = \ln{e ^ x} + \ln(e ^ {-x} + 1) - x = 0 ，
\\
\therefore 直线 y = x 是曲线 y = \frac{1}{x} + \ln(1 + e ^ x) 在 x \to +\infty 时的斜渐近线.
$$



