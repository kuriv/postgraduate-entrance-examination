# 函数的凹凸性

* [定理内容](#定理内容)
* [经典例题](#经典例题)
  * [例题一](#例题一)
  * [例题二](#例题二)
  * [例题三](#例题三)
  * [例题四](#例题四)

## 定理内容

$$
定义：如果函数 f(x) 满足在闭区间 [a , b] 上连续，且在 (a , b) 内具有一阶和二阶导数，
\\
若在 (a , b) 内 f(x)\prime\prime \gt 0 ，则 f(x) 在 [a , b] 上的图形是凹的，
\\
若在 (a , b) 内 f(x)\prime\prime \lt 0 ，则 f(x) 在 [a , b] 上的图形是凸的.
$$

## 经典例题

### 例题一

$$
如：判定曲线 y = \ln ^ x 的凹凸性.
\\
\because 定义域为 (0 , +\infty) ，且 y\prime = \frac{1}{x} ， y\prime\prime = -\frac{1}{x ^ 2} ，
\\
当 x \in (0 , +\infty) 时， y\prime\prime \lt 0 ，
\\
\therefore 曲线 y = \ln ^ x 在 (0 , +\infty) 上是凸的.
$$

### 例题二

$$
如：判定曲线 y = x ^ 3 的凹凸性.
\\
\because 定义域为 (-\infty , +\infty) ，且 y\prime = 3x ^ 2 ， y\prime\prime = 6x ，
\\
\because 当 y\prime\prime = 0 时， x = 0 ，
\\
\therefore 将定义域 (-\infty , +\infty) 分成 (-\infty , 0] 与 [0 , +\infty) ，
\\
当 x \in (-\infty , 0) 时， y\prime\prime \lt 0 ，
\\
当 x \in (0 , +\infty) 时， y\prime\prime \gt 0 ，
\\
\therefore 曲线 y = x ^ 3 在 (-\infty , 0] 上是凸的，在 [0 , +\infty) 上是凹的.
$$

### 例题三

$$
如：求曲线 y = 2x ^ 3 + 3x ^ 2 - 12x + 14 的拐点.
\\
\because 定义域为 (-\infty , +\infty) ，且 y\prime = 6x ^ 2 + 6x - 12 ， y\prime\prime = 12x + 6 ，
\\
\because 当 y\prime\prime = 0 时， x = -\frac{1}{2} ，
\\
\therefore 将定义域 (-\infty , +\infty) 分成 (-\infty , -\frac{1}{2}] 与 [-\frac{1}{2} , +\infty) ，
\\
当 x \in (-\infty , -\frac{1}{2}) 时， y\prime\prime \lt 0 ，
\\
当 x \in (-\frac{1}{2} , +\infty) 时， y\prime\prime \gt 0 ，
\\
\because y|_{x = -\frac{1}{2}} = 20\frac{1}{2} ，
\\
\therefore (-\frac{1}{2} , 20\frac{1}{2}) 是曲线 y = 2x ^ 3 + 3x ^ 2 - 12x + 14 的拐点.
$$

### 例题四

$$
如： 求曲线 y = 3x ^ 4 - 4x ^ 3 + 1 的拐点及凹、凸的区间.
\\
\because 定义域为 (-\infty , +\infty) ，且 y\prime = 12x ^ 3 - 12x ^ 2 ， y\prime\prime = 36x ^ 2 - 24x = 36x(x - \frac{2}{3}) ，
\\
\because 当 y\prime\prime = 0 时，求得 x_1 = 0 ， x_2 = \frac{2}{3} ，
\\
\therefore 将定义域 (-\infty , +\infty) 分成 (-\infty , 0] 与 [0 , \frac{2}{3}] 与 [\frac{2}{3} , +\infty) ，
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



