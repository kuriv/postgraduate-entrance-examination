# 实对称矩阵的相似对角化

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
对任意的 n 阶实对称矩阵 A ，存在 n 阶正交矩阵 Q ，使得 {Q ^ {T}}AQ = {Q ^ {-1}}AQ =
\begin{pmatrix}
\lambda_1 & & \\
& \lambda_2 & \\
& & \ddots & \\
& & & \lambda_n
\end{pmatrix}
，其中 \lambda_i (1 \le i \le n) 是 A 的全部特征值.
$$

$$
若 A 为 n 阶实对称矩阵，则其用正交矩阵 Q 相似对角化的基本步骤如下：
\\
先求 A 的特征值 \lambda_1 ， \lambda_2 ， \cdots ， \lambda_n ，
\\
然后求 A 的对应于特征值 \lambda_1 ， \lambda_2 ， \cdots ， \lambda_n 的特征向量 \xi_1 ， \xi_2 ， \cdots ， \xi_n ，
\\
若需要的话，将 \xi_1 ， \xi_2 ， \cdots ， \xi_n 正交化、单位化为 \eta_1 ， \eta_2 ， \cdots ， \eta_n ，
\\
令 Q = [\eta_1 ， \eta_2 ， \cdots ， \eta_n] ，则 Q 为正交矩阵，且 {Q ^ {-1}}AQ = {Q ^ {T}}AQ = \Lambda .
$$

## 经典例题

$$
\
\
如：设 A =
\begin{pmatrix}
0 & -1 & 4 \\
-1 & 3 & a \\
4 & a & 0
\end{pmatrix}
，正交矩阵 Q 使 {Q ^ {T}}AQ 为对角矩阵，若 Q 的第 1 列为 \frac{1}{\sqrt{6}}[1 , 2 , 1] ^ {T} ，求 a ， Q .
\\
\because Q 的第 1 列为 \frac{1}{\sqrt{6}}[1 , 2 , 1] ^ {T} ，
\\
\therefore [1 , 2 , 1] ^ {T} 是矩阵 A 的一个特征向量，
\\
\therefore A
\begin{pmatrix}
1 \\
2 \\
1
\end{pmatrix}
=
\begin{pmatrix}
0 & -1 & 4 \\
-1 & 3 & a \\
4 & a & 0
\end{pmatrix}
\begin{pmatrix}
1 \\
2 \\
1
\end{pmatrix}
=
\lambda_1
\begin{pmatrix}
1 \\
2 \\
1
\end{pmatrix} ，
\\
\therefore
\begin{cases}
-2 + 4 = \lambda_1 ， \\
-1 + 6 + a = 2\lambda_1 ， \\
4 + 2a = \lambda_1 ，
\end{cases}
\lambda_1 = 2 ， a = -1 ，
\\
\therefore A =
\begin{pmatrix}
0 & -1 & 4 \\
-1 & 3 & -1 \\
4 & -1 & 0
\end{pmatrix} ，
\\
\therefore |\lambda{E} - A| =
\begin{vmatrix}
\lambda & 1 & -4 \\
1 & \lambda - 3 & 1 \\
-4 & 1 & \lambda
\end{vmatrix}
= (\lambda - 2)(\lambda - 5)(\lambda + 4) = 0 ，
\\
\therefore A 的特征值为 \lambda_1 = 2 ， \lambda_2 = 5 ， \lambda_3 = -4 ，
\\
当 \lambda_1 = 2 时， \xi_1 = [1 , 2 , 1] ^ {T} ，
\\
当 \lambda_2 = 5 时， \xi_2 = [1 , -1 , 1] ^ {T} ， \eta_2 = \frac{1}{\sqrt{3}}[1 , -1 , 1] ^ {T} ，
\\
当 \lambda_3 = -4 时， \xi_3 = [-1 , 0 , 1] ^ {T} ， \eta_3 = \frac{1}{\sqrt{2}}[-1 , 0 , 1] ^ {T} ，
\\
\therefore Q =
\begin{pmatrix}
\frac{1}{\sqrt{6}} & \frac{1}{3} & -\frac{1}{\sqrt{2}} \\
\frac{2}{\sqrt{6}} & -\frac{1}{\sqrt{3}} & 0 \\
\frac{1}{\sqrt{6}} & \frac{1}{\sqrt{3}} & \frac{1}{\sqrt{2}}
\end{pmatrix} ，且 {Q ^ {T}}AQ =
\begin{pmatrix}
2 & 0 & 0 \\
0 & 5 & 0 \\
0 & 0 & -4
\end{pmatrix} .
$$

$$
如：设 A =
\begin{pmatrix}
2 & 0 & 0 \\
-1 & 3 & -1 \\
4 & -1 & 0
\end{pmatrix}
， B =
\begin{pmatrix}
5 & 0 & 0 \\
-5 & -1 & 3 \\
4 & 3 & -1
\end{pmatrix}
，求 A ， B 是否相似.
\\
\because A 的特征值为 \lambda_1 = 2 ， \lambda_2 = 5 ， \lambda_3 = -4 ，且 A \sim \Lambda =
\begin{pmatrix}
2 & 0 & 0 \\
0 & 5 & 0 \\
0 & 0 & -4
\end{pmatrix} ，
\\
\because |\mu{E} - B| =
\begin{vmatrix}
\mu - 5 & 0 & 0 \\
5 & \mu + 1 & -3 \\
-4 & -3 & \mu + 1
\end{vmatrix}
= (\mu - 2)(\mu - 5)(\mu + 4) ，
\\
\therefore B 的特征值为 \mu_1 = 2 ， \mu_2 = 5 ， \mu_3 = -4 ，
\\
\therefore B \sim \Lambda \sim
\begin{pmatrix}
2 & 0 & 0 \\
0 & 5 & 0 \\
0 & 0 & -4
\end{pmatrix}
\sim A .
$$



