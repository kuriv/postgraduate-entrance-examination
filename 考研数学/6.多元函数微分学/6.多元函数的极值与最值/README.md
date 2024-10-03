# 多元函数的极值与最值

* [定理内容](#定理内容)
* [无条件极值](#无条件极值)
* [条件最值](#条件最值)
* [经典例题](#经典例题)

## 定理内容

$$
若存在点 (x_0 , y_0) 的某个邻域，使得在该邻域内的任意一点 (x , y) 均有 f(x , y) \le f(x_0 , y_0) ，则称点 (x_0 , y_0) 为 f(x , y) 的极大值点.
\\
或在该邻域内的任意一点 (x , y) 均有 f(x , y) \ge f(x_0 , y_0) ，则称点 (x_0 , y_0) 为 f(x , y) 的极小值点.
$$

$$
设点 (x_0 , y_0) 为 f(x , y) 定义域内一点，若对于 f(x , y) 的定义域内任意一点 (x , y) 均有 f(x , y) \le f(x_0 , y_0) ，则称 f(x_0 , y_0) 为 f(x , y) 的最大值.
\\
若对于 f(x , y) 的定义域内任意一点 (x , y) 均有 f(x , y) \ge f(x_0 , y_0) ，则称 f(x_0 , y_0) 为 f(x , y) 的最小值.
$$

## 无条件极值

$$
记
\begin{cases}
f_{xx} ^ {\prime\prime} (x_0 , y_0) = A ，
\\
f_{xy} ^ {\prime\prime} (x_0 , y_0) = B ，
\\
f_{yy} ^ {\prime\prime} (x_0 , y_0) = C ，
\end{cases}
则 \Delta = AC - B ^ 2
\begin{cases}
\gt 0 \Rightarrow
\begin{cases}
A \gt 0 \Rightarrow 极小值，
\\
A \lt 0 \Rightarrow 极大值，
\end{cases}
\\
\lt 0 \Rightarrow 非极值 ，
\\
= 0 \Rightarrow 方法失效.
\end{cases}
$$

$$
设 z = f(x , y) 在点 (x_0 , y_0) 处
\begin{cases}
一阶偏导数存在，
\\
取极值，
\end{cases}
则 f_x ^ {\prime} (x_0 , y_0) = 0 ， f_y ^ {\prime} (x_0 , y_0) = 0 .
$$

## 条件最值

$$
求目标函数 u = (x , y , z) 在约束条件
\begin{cases}
\phi(x , y , z) = 0 ，
\\
\psi(x , y , z) = 0
\end{cases}
下的最值，
\\
先构造辅助函数 F(x , y , z , \lambda , \mu) = f(x , y , z) + \lambda\phi(x , y , z) + \mu\psi(x , y , z) ，
\\
令
\begin{cases}
F_x ^ {\prime} = f_x ^ {\prime} + \lambda\phi_x ^ {\prime} + \mu\psi_x ^ {\prime} = 0 ，
\\
F_y ^ {\prime} = f_y ^ {\prime} + \lambda\phi_y ^ {\prime} + \mu\psi_y ^ {\prime} = 0 ，
\\
F_z ^ {\prime} = f_z ^ {\prime} + \lambda\phi_z ^ {\prime} + \mu\psi_z ^ {\prime} = 0 ，
\\
F_{\lambda} ^ {\prime} = \phi(x , y , z) = 0 ，
\\
F_{\mu} ^ {\prime} = \psi(x , y , z) = 0 ，
\end{cases}
\\
根据实际问题，解上述方程组，可得备选点 p_i ，并求 f(p_i) ，取其最大值为 u_{max} ，最小值为 u_{min} .
$$

## 经典例题

$$
已知函数 z = z(x , y) 由方程 (x ^ 2 + y ^ 2)z + \ln{z} + 2(x + y + 1) = 0 确定，求 z(x , y) 的极值.
\\
对方程 (x ^ 2 + y ^ 2)z + \ln{z} + 2(x + y + 1) = 0 两端分别对 x 和 y 求偏导数可得，
\begin{cases}
2xz + (x ^ 2 + y ^ 2)\frac{\partial{z}}{\partial{x}} + \frac{1}{z}\frac{\partial{z}}{\partial{x}} + 2 = 0 ，
\\
2yz + (x ^ 2 + y ^ 2)\frac{\partial{z}}{\partial{y}} + \frac{1}{z}\frac{\partial{z}}{\partial{y}} + 2 = 0 ，
\end{cases}
\\
令 \frac{\partial{z}}{\partial{x}} = 0 和 \frac{\partial{z}}{\partial{y}} = 0 可得， x = -\frac{1}{z} ， y = -\frac{1}{z} ，
\\
将 x = -\frac{1}{z} 和 y = -\frac{1}{z} 代入方程 (x ^ 2 + y ^ 2)z + \ln{z} + 2(x + y + 1) = 0 可得， \ln{z} - \frac{2}{z} + 2 = 0 ，
\\
\therefore z = 1 ， x = -1 ， y = -1 ，
\\
继续两端分别对 x 和 y 求偏导数可得，
\begin{cases}
2z + 4x\frac{\partial{z}}{\partial{x}} + (x ^ 2 + y ^ 2)\frac{\partial ^ {2} {z}}{\partial{x} ^ {2}} - \frac{1}{z ^ 2}(\frac{\partial{z}}{\partial{x}}) ^ 2 + \frac{1}{z}\frac{\partial ^ {2} {z}}{\partial{x} ^ {2}} = 0 ，
\\
2x\frac{\partial{z}}{\partial{y}} + 2y\frac{\partial{z}}{\partial{x}} + (x ^ 2 + y ^ 2)\frac{\partial ^ {2} {z}}{\partial{x}\partial{y}} - \frac{1}{z ^ 2}(\frac{\partial{z}}{\partial{y}}) ^ 2 + \frac{1}{z}\frac{\partial ^ {2} {z}}{\partial{x}\partial{y}} = 0 ，
\\
2z + 4y\frac{\partial{z}}{\partial{y}} + (x ^ 2 + y ^ 2)\frac{\partial ^ {2} {z}}{\partial{y} ^ {2}} - \frac{1}{z ^ 2}(\frac{\partial{z}}{\partial{y}}) ^ 2 + \frac{1}{z}\frac{\partial ^ {2} {z}}{\partial{y} ^ {2}} = 0 ，
\end{cases}
\\
\therefore
A = \frac{\partial ^ {2} {z}}{\partial{x} ^ {2}}|_{(-1 , -1)} = -\frac{2}{3} ， B = \frac{\partial ^ {2} {z}}{\partial{x}\partial{y}}|_{(-1 , -1)} = 0 ， C = \frac{\partial ^ {2} {z}}{\partial{y} ^ {2}}|_{(-1 , -1)} = -\frac{2}{3} ，
\\
\because \Delta = AC - B ^ 2 \gt 0 ，且 A \lt 0 ，
\\
\therefore z(-1 , -1) = 1 是 z(x , y) 的极大值.
$$

$$
设 a , b 满足 \int_a ^ {b}{|x|}dx = \frac{1}{2} (a \le 0 ， b \ge 0) ，求曲线 y = x ^ 2 + ax 与直线 y = bx 所围成区域面积的最大值和最小值.
\\
\because \int_a ^ {b}{|x|}dx = \int_a ^ {0}{-x}dx + \int_{0} ^ {b}{x}dx = \frac{1}{2}a ^ 2 + \frac{1}{2}b ^ 2 = \frac{1}{2}(a ^ 2 + b ^ 2) = \frac{1}{2} ，
\\
\therefore a ^ 2 + b ^ 2 = 1 ，
\\
\because 曲线 y = x ^ 2 + ax 与直线 y = bx 的交点横坐标分别为 x_1 = 0 ， x_2 = b - a ，
\\
\therefore S = \int_{0} ^ {b - a}{[bx - (x ^ 2 + ax)]}dx = \frac{1}{2}b(b - a) ^ 2 - \frac{1}{3}(b - a) ^ 3 - \frac{1}{2}a(b - a) ^ 2 = \frac{1}{2}(b - a) ^ 3 - \frac{1}{3}(b - a) ^ 3 = \frac{1}{6}(b - a) ^ 3 ，
\\
\because \frac{1}{6}(b - a) ^ 3 的最值点与 (b - a) 的最值点是一样的，
\\
\therefore 令 F(a , b , \lambda) = b - a + \lambda(a ^ 2 + b ^ 2 - 1) ，
\\
\therefore
\begin{cases}
F_a ^ {\prime} = -1 + 2a\lambda = 0 ，
\\
F_b ^ {\prime} = 1 +  2b\lambda = 0 ，
\\
F_{\lambda} ^ {\prime} = a ^ 2 + b ^ 2 - 1 = 0 ，
\end{cases}
\\
当 a = -\frac{\sqrt{2}}{2} ， b = \frac{\sqrt{2}}{2} 时， S = \frac{\sqrt{2}}{3} ，
\\
当 a = 0 ， b = 1 时， S = \frac{1}{6} ，
\\
当 a = -1 ， b = 0 时， S = \frac{1}{6} ，
\\
\therefore 曲线 y = x ^ 2 + ax 与直线 y = bx 所围成区域面积的最大值为 \frac{\sqrt{2}}{3} ，最小值为 \frac{1}{6} .
$$



