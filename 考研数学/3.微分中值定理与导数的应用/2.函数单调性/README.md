# 函数单调性

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
如果函数 f(x) 满足在闭区间 [a , b] 上连续，在开区间 (a , b) 内可导，
\\
当在 (a , b) 内 f ^ {\prime} (x) \ge 0 ， 且等号仅在有限多个点处成立，则函数 f(x) 在 [a , b] 上单调增加，
\\
当在 (a , b) 内 f ^ {\prime} (x) \le 0 ， 且等号仅在有限多个点处成立，则函数 f(x) 在 [a , b] 上单调减少.
$$

## 经典例题

$$
如：判断函数 y = x - \sin{x} 在 [-\pi , \pi] 上的单调性.
\\
\because y\prime = 1 - \cos{x} \ge 0 ，
\\
\therefore 函数 y = x - \sin{x} 在 [-\pi , \pi] 上单调增加.
$$

$$
如：判断函数 y = \sqrt[3]{x ^ 2} 的单调性.
\\
\because y\prime = \frac{2}{3\sqrt[3]{x}} ，
\\
\because 当 x = 0 时，函数的导数不存在，
\\
\therefore 将定义域 (-\infty , +\infty) 分成 (-\infty , 0) 与 (0 , +\infty) ，
\\
当 x \in (-\infty , 0) 时， y\prime \le 0 ，
\\
当 x \in (0 , +\infty) 时， y\prime \ge 0 ，
\\
\therefore 函数 y = \sqrt[3]{x ^ 2} 在 (-\infty , 0) 上单调减少，在 (0 , +\infty) 上单调增加.
$$

$$
如：确定函数 f(x) = 2{x ^ 3} - 9{x ^ 2} + 12x - 3 的单调区间.
\\
\because f ^ {\prime} (x) = 6{x ^ 2} - 18x + 12 = 6(x ^ 2 - 3x + 2) = 6(x - 1)(x - 2) ，
\\
\because 当 f ^ {\prime} (x) = 0 时，求得 x_1 = 1 ， x_2 = 2 ，
\\
\therefore 将定义域 (-\infty , +\infty) 分成 (-\infty , 1) 与 (1 , 2) 与 (2 , +\infty) ，
\\
当 x \in (-\infty , 1) 时， f ^ {\prime} (x) \ge 0 ，
\\
当 x \in (1 , 2) 时， f ^ {\prime} (x) \le 0 ，
\\
当 x \in (2 , +\infty) 时， f ^ {\prime} (x) \ge 0 ，
\\
\therefore 函数 f(x) = 2{x ^ 3} - 9{x ^ 2} + 12x - 3 在 (-\infty , 1] 上单调增加，在 [1 , 2] 上单调减少， 在 [2 , +\infty) 上单调增加.
$$

$$
如：证明当 x \gt 1 时， 2\sqrt{x} \gt 3 - \frac{1}{x} .
\\
证明如下：令 f(x) = 2\sqrt{x} - 3 + \frac{1}{x} ，
\\
\because f ^ {\prime}( x) = \frac{1}{\sqrt{x}} - \frac{1}{x ^ 2} = \frac{\sqrt{x} \cdot x - 1}{x ^ 2} ，
\\
\because 当 f ^ {\prime} (x) = 0 时，求得 x = 1 ，
\\
当 x \in (1 , +\infty) 时， f ^ {\prime} (x) \ge 0 ，
\\
\therefore 函数 f(x) = 2\sqrt{x} - 3 + \frac{1}{x} 在 [1 , +\infty) 上单调增加，
\\
\because f(1) = 0 ，
\\
\therefore 当 x \gt 1 时， 2\sqrt{x} \gt 3 - \frac{1}{x} .
$$



