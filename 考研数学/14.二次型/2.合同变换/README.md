# 合同变换

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
设 A ， B 为 n 阶矩阵，若存在可逆矩阵 C ，使得 {C ^ {T}}AC = B ，则称 A 与 B 合同，记作 A \cong B ，此时对应的二次型 f(x) 与 g(y) 为合同二次型.
$$

$$
若二次型中只含有平方项，没有交叉项，即形如 d_1{x_1 ^ 2} + d_2{x_2 ^ 2} + \cdots + d_n{x_n ^ 2} 的二次型称为标准形.
$$

$$
若标准形中，系数 d_i (i = 1 , 2 , \cdots , n) 的取值范围为 \{1 , -1 , 0\} ，即形如 x_1 ^ 2 + \cdots + x_p ^ 2 - x_{p + 1} ^ 2 - \cdots - x_{p + q} ^ 2 的二次型称为规范形.
$$

$$
无论选取什么样的可逆线性变换，将二次型化成标准形或规范形，其正项个数 p ，负项个数 q 都是不变的， p 称为正惯性指数， q 称为负惯性指数.
$$

## 经典例题

$$
化二次型 f(x_1 , x_2 , x_3) = x_1 ^ 2 + 2x_1x_2 + 2x_1x_3 - x_2 ^ 2 - 2x_2x_3 - x_3 ^ 2 为标准形，并写出所作的可逆线性变换.
\\
\because f(x_1 , x_2 , x_3) = (x_1 + x_2 + x_3) ^ 2 - x_2 ^ 2 - x_3 ^ 2 - 2x_2x_3 - x_2 ^ 2 - 2x_2x_3 - x_3 ^ 3 = (x_1 + x_2 + x_3) ^ 2 - 2{x_2 ^ 2} - 2{x_3 ^ 2} - 4x_2x_3
\\
= (x_1 + x_2 + x_3) ^ 2 - 2{(x_2 + x_3) ^ 2} ，
\\
令
\begin{cases}
x_1 + x_2 + x_3 = y_1 ， \\
x_2 + x_3 = y_2 ， \\
x_3 = y_3 ，
\end{cases}
则
\begin{cases}
x_1 = y_1 - y_2 ， \\
x_2 = y_2 - y_3 ， \\
x_3 = y_3 ，
\end{cases}
\\
\therefore f(x_1 , x_2 , x_3) \xrightarrow{x = Cy} y_1 ^ 2 - 2{y_2 ^ 2} ，其中 C =
\begin{pmatrix}
1 & -1 & 0 \\
0 & 1 & -1 \\
0 & 0 & 1
\end{pmatrix} .
$$

$$
将二次型 f(x_1 , x_2 , x_3) = x_1x_2 + x_1x_3 - x_2x_3 化为规范形，并求所用的可逆线性变换.
\\
令
\begin{cases}
x_1 = y_1 + y_2 ， \\
x_2 = y_1 - y_2 ， \\
x_3 = y_3 ，
\end{cases}
则 f(x_1 , x_2 , x_3) = y_1 ^ 2 - y_2 ^ 2 + y_1y_3 + y_2y_3 - y_1y_3 + y_2y_3 = y_1 ^ 2 - y_2 ^ 2 + 2y_2y_3 = y_1 ^ 2 - (y_2 - y_3) ^ 2 + y_3 ^ 2 ，
\\
令
\begin{cases}
z_1 = y_1 ， \\
z_2 = y_2 - y_3 ， \\
z_3 = y_3 ，
\end{cases}
则
\begin{cases}
y_1 = z_1 ， \\
y_2 = z_2 + z_3 ， \\
y_3 = z_3 ，
\end{cases}
\\
\therefore f(x_1 , x_2 , x_3) \xrightarrow{x = Cz} z_1 ^ 2 - z_2 ^ 2 + z_3 ^ 2 ，其中 C =
\begin{pmatrix}
1 & 1 & 1 \\
1 & -1 & -1 \\
0 & 0 & 1
\end{pmatrix} .
$$

$$
用正交变换化二次型 f(x_1 , x_2 , x_3) = 2{x_1 ^ 2} + 5{x_2 ^ 2} + 5{x_3 ^ 2} + 4x_1x_2 - 4x_1x_3 - 8x_2x_3 为标准形，并求所作的正交变换.
\\
\because A =
\begin{pmatrix}
2 & 2 & -2 \\
2 & 5 & -4 \\
-2 & -4 & 5
\end{pmatrix}
， |\lambda{E} - A| =
\begin{pmatrix}
\lambda - 2 & -2 & 2 \\
-2 & \lambda - 5 & 4 \\
2 & 4 & \lambda - 5
\end{pmatrix} ，
\\
\therefore \lambda_1 = \lambda_2 = 1 ， \lambda_3 = 10 ，
\\
\therefore \xi_1 = [-2 , 1 , 0] ^ {T} ， \xi_2 = [2 , 0 , 1] ^ {T} ， \xi_3 = [1 , 2 , -2] ^ {T} ，
\\
将 \lambda_1 = \lambda_2 = 10 对应的特征向量 \xi_1 ， \xi_2 标准正交化，
\\
令 \eta_1 = \xi_1 = [-2 , 1 , 0] ^ {T} ，则 \eta_2 = \xi_2 - \frac{(\xi_2 , \eta_1)}{(\eta_1 , \eta_1)}\eta_1 = [\frac{2}{5} , \frac{4}{5} , 1] ^ {T} = [2 , 4 , 5] ^ {T} ，
\\
再将 \eta_1 ， \eta_2 ， \xi_3 单位化，
\\
\therefore \eta_1 = [-\frac{2}{\sqrt{5}} , \frac{1}{\sqrt{5}} , 0] ^ {T} ， \eta_2 = [\frac{2}{3\sqrt{5}} , \frac{4}{3\sqrt{5}} , \frac{5}{3\sqrt{5}}] ^ {T} ， \eta_3 = [\frac{1}{3} , \frac{2}{3} , -\frac{2}{3}] ^ {T} ，
\\
令正交矩阵 Q = [\eta_1 , \eta_2 , \eta_3] ，
\\\
\
\therefore f(x_1 , x_2 , x_3) = {x ^ {T}}Ax \xrightarrow{x = Qy} {y ^ {T}}{Q ^ {T}}AQy = y_1 ^ 2 + y_2 ^ 2 + 10{y_3 ^ 2} ，其中正交变换为
\begin{pmatrix}
-\frac{2}{\sqrt{5}} & \frac{2}{3\sqrt{5}} & \frac{1}{3} \\
\frac{1}{\sqrt{5}} & \frac{4}{3\sqrt{5}} & \frac{2}{3} \\
0 & \frac{5}{3\sqrt{5}} & -\frac{2}{3}
\end{pmatrix}
\begin{pmatrix}
y_1 \\
y_2 \\
y_3
\end{pmatrix} .
$$



