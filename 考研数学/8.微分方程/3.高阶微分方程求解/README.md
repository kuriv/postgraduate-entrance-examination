# 高阶微分方程求解

* [二阶常系数齐次线性微分方程](#二阶常系数齐次线性微分方程)
* [二阶常系数非齐次线性微分方程](#二阶常系数非齐次线性微分方程)
* [经典例题](#经典例题)

## 二阶常系数齐次线性微分方程

$$
方程 y ^ {\prime\prime} + p{y ^ {\prime}} + qy = 0 称为二阶常系数齐次线性微分方程，其中 p ， q 为常数.
$$

$$
对于 y ^ {\prime\prime} + p{y ^ {\prime}} + qy = 0 ，其对应的特征方程为 r ^ 2 + pr + q = 0 .
\\
若 p ^ 2 - 4q \gt 0 ，设 r_1 ， r_2 是特征方程的两个不等实根，即 r_1 \neq r_2 ，则通解为 y = C_1{e ^ {{r_1}x}} + C_2{e ^ {{r_2}x}} .
\\
若 p ^ 2 - 4q = 0 ，设 r_1 ， r_2 是特征方程的两个相等实根，即 r_1 = r_2 = r ，则通解为 y = (C_1 + C_2x){e ^ {rx}} .
\\
若 p ^ 2 - 4q \lt 0 ，设 \alpha \pm \beta_i 是特征方程的一堆共轭复根，则通解为 y = e ^ {\alpha{x}}(C_1\cos{\beta{x}} + C_2\sin{\beta{x}}) .
$$

## 二阶常系数非齐次线性微分方程

$$

$$

## 经典例题

$$
设函数 y = y(x) 是微分方程 y ^ {\prime\prime} + y ^ {\prime} - 2y = 0 的解，且在 x = 0 处 y(x) 取得极值 3，求 y(x) .
\\
\because y ^ {\prime\prime} + y ^ {\prime} - 2y = 0 的特征方程为 r ^ 2 + r - 2 = 0 ，
\\
\therefore r_1 = -2 ， r_2 = 1 ，
\\
\therefore 通解为 y(x) = C_1{e ^ {-2x}} + C_2{e ^ {x}} ，
\\
\because y(x) 在 x = 0 处取得极值 3 ，
\\
\therefore C_1 + C_2 = 3 ， y ^ {\prime} (x) = -2{C_1}{e ^ {-2x}} + {C_2}{e ^ x}|_{x = 0} = 0 ，
\\
\therefore
\begin{cases}
C_1 = 1 ， \\
C_2 = 2
\end{cases}
\\
\therefore y(x) = e ^ {-2x} + 2{e ^ x} .
$$

$$
设函数 y = f(x) 满足微分方程 y ^ {\prime\prime} + 2{y ^ {\prime}} + 5y = 0 ，且 f(0) = 1 ， f ^ {\prime} (0) = -1 ，求 f(x) .
\\
\because y ^ {\prime\prime} + 2{y ^ {\prime}} + 5y = 0 的特征方程为 r ^ 2 + 2r + 5 = 0 ，
\\
\therefore r_1 = -1 + 2i ， r_2 = -1 - 2i ，
\\
\therefore 通解为 y = f(x) = e ^ {-x}(C_1\cos{2}x + C_2\sin{2}x) ，
\\
\therefore
\begin{cases}
C_1 = 1 \\
C_2 = 0
\end{cases}
\\
\therefore f(x) = e ^ {-x}\cos{2x} .
$$

