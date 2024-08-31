# 函数的极值

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
定义（第一充分条件）：设函数 f(x) 在 x_0 处连续，且在 x_0 的某去心邻域 u ^ o (x_0 , \delta) 内可导，\\
\
若 x \in (x_0 - \delta , x_0) 时， f(x)\prime \gt 0 ，而 x \in (x_0 , x_0 + \delta) 时， f(x)\prime \lt 0 ，则 f(x) 在 x_0 处取得极大值，
\\
若 x \in (x_0 - \delta , x_0) 时， f(x)\prime \lt 0 ，而 x \in (x_0 , x_0 + \delta) 时， f(x)\prime \gt 0 ，则 f(x) 在 x_0 处取得极小值，
\\
若 x \in u ^ o (x_0 , \delta) 时， f(x)\prime 的符号保持不变，则 f(x) 在 x_0 处没有极值.
$$

$$
定义（第二充分条件）：设函数 f(x) 在 x_0 处具有二阶导数且 f(x)\prime = 0 ， f(x)\prime\prime \neq 0 ，
\\
当 f(x)\prime\prime \gt 0 时，函数 f(x) 在 x_0 处取得极小值，
\\
当 f(x)\prime\prime \lt 0 时，函数 f(x) 在 x_0 处取得极大值.
$$

$$
定义（第三充分条件）：设函数 f(x) 在 x_0 处 n 阶可导，且 f(x_0) ^ {(m)} = 0 (m = 1 ， 2 , \cdots , n - 1) ， f(x_0) ^ {(n)} \neq 0 ，
\\
当 n 为偶数时，且 f(x_0) ^ {(n)} \gt 0 时， f(x) 在 x_0 处取得极小值，
\\
当 n 为偶数时，且 f(x_0) ^ {(n)} \lt 0 时， f(x) 在 x_0 处取得极大值.
$$

## 经典例题

$$
如：求函数 f(x) = (x - 4)\sqrt[3]{(x + 1) ^ 2} 的极值.
\\
\because f(x)\prime = \frac{5(x - 1)}{3\sqrt[3]{x + 1}} ， f(x)\prime\prime = \frac{5 \cdot 3 \cdot \sqrt[3]{x + 1} + 5(x - 1) \cdot 3 \cdot \frac{1}{\sqrt[3]{(x + 1) ^ 2}}}{(3\sqrt[3]{x + 1}) ^ 2} ，
\\
\because 当 f(x)\prime = 0 时，求得 x = 1 ，且当 x = -1 时，函数的导数不存在，
\\
\therefore 将定义域 (-\infty , +\infty) 分成 (-\infty , -1) 与 (-1 , 1) 与 (1 , +\infty) ，
\\
当 x \in (-\infty , -1) 时， f(x)\prime \gt 0 ，
\\
当 x \in (-1 , 1) 时， f(x)\prime \lt 0 ，
\\
当 x \in (1 , +\infty) 时， f(x)\prime \gt 0 ，
\\
\therefore 极大值为 f(-1) = 0 ， 极小值为 f(1) = -3\sqrt[3]{4}.
$$

$$
如：求函数 f(x) = (x ^ 2 - 1) ^ 3 + 1 的极值.\\
\
\
\because f(x)\prime = 6x(x ^ 2 - 1) ^ 2 ， f(x)\prime\prime = 6(x ^ 2 - 1)(5x ^ 2 - 1) ，
\\
\because 当 f(x)\prime = 0 时，求得 x_1 = -1 ， x_2 = 0 ， x_3 = 1 ，
\\
\therefore 将定义域 (-\infty , +\infty) 分成 (-\infty , -1) 与 (-1 , 0) 与 (0 , 1) 与 (1 , +\infty) ，
\\
当 x \in (-\infty , -1) 时， f(x)\prime \lt 0 ，
\\
当 x \in (-1 , 0) 时， f(x)\prime \lt 0 ，
\\
当 x \in (0 , 1) 时， f(x)\prime \gt 0 ，
\\
当 x \in (1 , +\infty) 时， f(x)\prime \gt 0 ，
\\
\therefore 极小值为 f(0) = 0 .
$$



