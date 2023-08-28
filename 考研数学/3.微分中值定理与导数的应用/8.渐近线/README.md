# 渐近线

* [铅直渐近线](#铅直渐近线)
* [水平渐近线](#水平渐近线)
* [斜渐近线](#斜渐近线)
* [经典例题](#经典例题)
  * [例题一](#例题一)

## 铅直渐近线

$$
如果 \lim_{x \to x_0}f(x) = \infty ，则 x = x_0 为 f(x) 的铅直渐近线.
\\
如： x = 0 是 y = \frac{1}{x} 的铅直渐近线， x = k\pi + \frac{\pi}{2} （k \in Z） 是 y = \tan{x} 的铅直渐近线.
$$

## 水平渐近线

$$
如果 \lim_{x \to \infty}f(x) = A ，则 y = A 为 f(x) 的水平渐近线.
\\
如： y = 0 是 y = e ^ x 的水平渐近线.
$$

## 斜渐近线

$$
如果存在常数 a 、 b ，使得 \lim_{x \to \infty}[f(x) - ax - b] = 0 ，则 y = ax + b 为 f(x) 的斜渐近线.
\\
其中： a = \lim_{x \to \infty}\frac{f(x)}{x} ， b = \lim_{x \to \infty}[f(x) - ax] .
$$

## 经典例题

### 例题一

$$
如：求 f(x) = \frac{2x ^ 3}{x ^ 2 - 3x + 2} 的斜渐近线.
\\
\because a = \lim_{x \to \infty}\frac{f(x)}{x} = \lim_{x \to \infty}\frac{\frac{2x ^ 3}{x ^ 2 - 3x + 2}}{x} = \lim_{x \to \infty}\frac{2x ^ 2}{x ^ 2 - 3x + 2} = 2 ，
\\
\because \lim_{x \to \infty}[f(x) - ax] = \lim_{x \to \infty}[\frac{2x ^ 3}{x ^ 2 - 3x + 2} - 2x] = \lim_{x \to \infty}\frac{2x ^ 3 - 2x ^ 3 + 6x ^ 2 - 4x}{x ^ 2 - 3x + 2} = \lim_{x \to \infty}\frac{6x ^ 2 - 4x}{x ^ 2 - 3x + 2} = 6 ，
\\
\therefore y = 2x + 6 是 \frac{2x ^ 3}{x ^ 2 - 3x + 2} 的斜渐近线.
$$



