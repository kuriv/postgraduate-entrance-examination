# 微分方程的概念

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
表示未知函数及其导数与自变量之间关系的方程称为微分方程，微分方程中未知函数的最高阶导数的阶数称为微分方程的阶.
\\
如 y ^ {\prime\prime\prime} - y ^ {\prime\prime} + 6y = 0 就是三阶微分方程.
$$

$$
未知函数是一元函数的微分方程称为常微分方程，如 {y}dx - (x + \sqrt{x ^ 2 + y ^ 2})dy = 0 .
$$

$$
形如 a_n(x)y ^ {(n)} + a_{n - 1}(x)y ^ {(n - 1)} + \cdots a_1(x)y ^ {\prime} + a_0(x)y = f(x) 的微分方程称为 n 阶线性微分方程.
\\
当 a_k(x) (k = 0 , 1 , 2 , \cdots , n) 都是常数时，则称方程为 n 阶常系数线性微分方程.
\\
若 f(x) 恒为零，则称方程为 n 阶齐次线性微分方程，否则称方程为 n 阶非齐次线性微分方程.
$$

$$
如果微分方程的解中含有任意常数，且任意常数的个数与微分方程的阶数相同，这样的解叫作微分方程的通解.
\\
确定了通解中的任意常数以后，就得到微分方程的特解.
$$

## 经典例题

$$
设 y = y(x) 是二阶常系数线性微分方程 y ^ {\prime\prime} + py ^ {\prime} + qy = e ^ {3x} 满足初始条件 y(0) = y ^ {\prime} (0) = 0 的特解，求 \lim_{x \to 0} {\frac{\ln(1 + x ^ 2)}{y(x)}} .
\\
\because \lim_{x \to 0} {\frac{\ln(1 + x ^ 2)}{y(x)}} = \lim_{x \to 0} {\frac{x ^ 2}{y(x)}} = \lim_{x \to 0} {\frac{2x}{y ^ {\prime} (x)}} = \lim_{x \to 0} {\frac{2}{y ^ {\prime\prime} (x)}} ，
\\
\because y ^ {\prime\prime} (0) + p{y ^ {\prime}(0)} + q{y(0)} = e ^ {3x} ，
\\
\therefore y ^ {\prime\prime} (0) = 1 ，
\\
\therefore \lim_{x \to 0} {\frac{1 + x ^ 2}{y(x)}} = 2 .
$$



