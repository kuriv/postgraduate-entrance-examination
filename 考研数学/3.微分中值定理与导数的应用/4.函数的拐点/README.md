# 函数的拐点

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
第一充分条件：设函数 f(x) 在 x_0 处连续，且在 x_0 的某去心邻域 u ^ o (x_0 , \delta) 内二阶导数存在，如果在该点的左、右邻域内 f ^ {\prime\prime} (x) 变号，则点 (x_0 , \delta) 为拐点.
$$

$$
第二充分条件：设函数 f(x) 在 x_0 的邻域内三阶可导，且 f ^ {\prime\prime} (x) = 0 ， f ^ {\prime\prime\prime} (x) \neq 0 ，则点 (x_0 , \delta) 为拐点.
$$

$$
第三充分条件：设函数 f(x) 在 x_0 处 n 阶可导，且 f ^ {{(m)}} (x_0) = 0 (m = 2 ， 3 , \cdots , n - 1) ， f ^ {(n)} (x_0) \neq 0 ，则当 n 为奇数，点 (x_0 , \delta) 为拐点.
$$

## 经典例题

$$
如：求曲线 y = 2x ^ 3 + 3x ^ 2 - 12x + 14 的拐点.
\\
\because y\prime = 6x ^ 2 + 6x - 12 ， y\prime\prime = 12x + 6 ，
\\
\because 当 y\prime\prime = 0 时， x = -\frac{1}{2} ，
\\
\therefore 将定义域 (-\infty , +\infty) 分成 (-\infty , -\frac{1}{2}) 与 (-\frac{1}{2} , +\infty) ，
\\
当 x \in (-\infty , -\frac{1}{2}) 时， y\prime\prime \lt 0 ，
\\
当 x \in (-\frac{1}{2} , +\infty) 时， y\prime\prime \gt 0 ，
\\
\because y|_{x = -\frac{1}{2}} = 20\frac{1}{2} ，
\\
\therefore (-\frac{1}{2} , 20\frac{1}{2}) 是曲线 y = 2x ^ 3 + 3x ^ 2 - 12x + 14 的拐点.
$$

$$
如： 求曲线 y = 3x ^ 4 - 4x ^ 3 + 1 的拐点及凹、凸的区间.
\\
\because y\prime = 12x ^ 3 - 12x ^ 2 ， y\prime\prime = 36x ^ 2 - 24x = 36x(x - \frac{2}{3}) ，
\\
\because 当 y\prime\prime = 0 时，求得 x_1 = 0 ， x_2 = \frac{2}{3} ，
\\
\therefore 将定义域 (-\infty , +\infty) 分成 (-\infty , 0) 与 (0 , \frac{2}{3}) 与 (\frac{2}{3} , +\infty) ，
\\
当 x \in (-\infty , 0) 时， y\prime\prime \gt 0 ，
\\
当 x \in (0 , \frac{2}{3}) 时， y\prime\prime \lt 0 ，
\\
当 x \in (\frac{2}{3} , +\infty) 时， y\prime\prime \gt 0 ，
\\
\therefore 曲线 y = 3x ^ 4 - 4x ^ 3 + 1 在 (-\infty , 0] 上是凹的，在 [0 , \frac{2}{3}] 上是凸的，在 [\frac{2}{3} , +\infty) 上是凹的，
\\
\because y|_{x = 0} = 1 ， y|_{x = \frac{2}{3}} = \frac{11}{24} ，
\\
\therefore (0 , 1) 和 (\frac{2}{3} , \frac{11}{24}) 是曲线 y = 3x ^ 4 - 4x ^ 3 + 1 的拐点.
$$



