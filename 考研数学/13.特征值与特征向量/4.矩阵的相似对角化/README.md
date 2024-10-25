# 矩阵的相似对角化

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
设 A 为 n 阶矩阵，若存在 n 阶可逆矩阵 P ，使得 {P ^ {-1}}AP  = \Lambda ，其中 \Lambda 是对角矩阵，则称 \Lambda 可相似对角化，记为 A \sim \Lambda ，称 \Lambda 是 A 的相似标准形.
$$

## 经典例题

$$
设 A 为 2 阶矩阵且 A ^ 2 - A = 2E ， P = [\alpha , A\alpha] ，求 {P ^ {-1}}AP ，并判断 A 是否可相似于对角矩阵.
\\
\because A ^ 2 - A = 2E ，
\\
\therefore A ^ 2 - A - 2E = 0 ， {A ^ 2}\alpha - A\alpha - 2\alpha = 0 ， {A ^ 2}\alpha = A\alpha + 2\alpha ，
\\
\therefore AP = A[\alpha , A\alpha] = [A\alpha , {A ^ 2}\alpha] = [A\alpha , A\alpha + 2\alpha] = P
\begin{pmatrix}
0 & 2 \\
1 & 1
\end{pmatrix} ，
\\
\therefore {P ^ {-1}}AP = {P ^ {-1}}P
\begin{pmatrix}
0 & 2 \\
1 & 1
\end{pmatrix}
=
\begin{pmatrix}
0 & 2 \\
1 & 1
\end{pmatrix} ，
\\
\because |\lambda{E} - A| =
\begin{vmatrix}
\lambda & -2 \\
-1 & \lambda - 1
\end{vmatrix}
= \lambda(\lambda - 1) - 2 = (\lambda - 2)(\lambda + 1) = 0 ，
\\
\therefore A 的特征值为 2 ， -1 ， A 相似于对角矩阵
\begin{pmatrix}
0 & 2 \\
1 & 1
\end{pmatrix} .
$$

$$
设 A 为 3 阶矩阵，已知 \alpha_1 ， \alpha_2 ， \alpha_3 是线性无关的 3 维列向量，且满足 A\alpha_1 = \alpha_1 + \alpha_2 + \alpha_3 ， A\alpha_2 = 2\alpha_2 + \alpha_3 ， A\alpha_3 = 2\alpha_2 + 3\alpha_3 ，
\\
求矩阵 B ，使得 A[\alpha_1 , \alpha_2 , \alpha_3] = [\alpha_1 , \alpha_2 , \alpha_3]B ，求矩阵 A 的特征值，求可逆矩阵 P ，使得 {P ^ {-1}}AP 为对角矩阵.
\\
\because A[\alpha_1 , \alpha_2 , \alpha_3] = [A\alpha_1 , A\alpha_2 , A\alpha_3] = [\alpha_1 + \alpha_2 + \alpha_3 ， 2\alpha_2 + \alpha_3 , 2\alpha_2 + 3\alpha_3] = [\alpha_1 , \alpha_2 , \alpha_3]B ，
\\
\therefore B =
\begin{pmatrix}
1 & 0 & 0 \\
1 & 2 & 2 \\
1 & 1 & 3 \\
\end{pmatrix} .
\\
\because \alpha_1 ， \alpha_2 ， \alpha_3 是线性无关的 3 维列向量，
\\
\therefore [\alpha_1 ， \alpha_2 ， \alpha_3] 可逆，
\\
\because A[\alpha_1 , \alpha_2 , \alpha_3] = [\alpha_1 , \alpha_2 , \alpha_3]B ，
\\
\therefore {[\alpha_1 , \alpha_2 , \alpha_3] ^ {-1}}A[\alpha_1 , \alpha_2 , \alpha_3] = B ， A 相似于 B ，且 A 的特征值与 B 的特征值相同，
\\
\therefore |\lambda{E} - B| =
\begin{vmatrix}
\lambda - 1 & 0 & 0 \\
-1 & \lambda - 2 & -2 \\
-1 & -1 & \lambda - 3
\end{vmatrix}
=
{(\lambda - 1) ^ 2}(\lambda - 4) = 0 ，
\\
\therefore B 与 A 的特征值均为 1 ， 1 ， 4 .
\\
当 \lambda_1 = \lambda_2 = 1 时， (E - A)x =
\begin{pmatrix}
0 & 0 & 0 \\
-1 & -1 & -2 \\
-1 & -1 & -2
\end{pmatrix}
\begin{pmatrix}
x_1 \\
x_2 \\
x_3
\end{pmatrix}
= 0 ，
\\
\therefore \xi_1 = [-1 , 1 , 0] ^ {T} ， \xi_2 = [-2 , 0 , 1] ^ {T} ，
\\
当 \xi_3 = 4 时， (4E - A)x =
\begin{pmatrix}
3 & 0 & 0 \\
-1 & 2 & -2 \\
-1 & -1 & 1
\end{pmatrix}
\begin{pmatrix}
x_1 \\
x_2 \\
x_3
\end{pmatrix}
= 0 ，
\\
\therefore \xi_3 = [0 , 1 , 1] ^ {T} ，
\\
令 Q = [\xi_1 , \xi_2 , \xi_3] =
\begin{pmatrix}
-1 & -2 & 0 \\
1 & 0 & 1 \\
0 & 1 & 1
\end{pmatrix}
，则 {Q ^ {-1}}BQ = \Lambda =
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 4
\end{pmatrix} ，
\\
\because {[\alpha_1 , \alpha_2 , \alpha_3] ^ {-1}}A[\alpha_1 , \alpha_2 , \alpha_3] = B ，
\\
\therefore {Q ^ {-1}}{[\alpha_1 , \alpha_2 , \alpha_3] ^ {-1}}A{[\alpha_1 , \alpha_2 , \alpha_3]}Q = \Lambda =
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 4
\end{pmatrix}
= {({[\alpha_1 , \alpha_2 , \alpha_3]}Q) ^ {-1}}A{[\alpha_1 , \alpha_2 , \alpha_3]}Q = {P ^ {-1}}AP ，
\\
\therefore P = {[\alpha_1 , \alpha_2 , \alpha_3]}Q = [-\alpha_1 + \alpha_2 , -2\alpha_1 + \alpha_3 , \alpha_2 + \alpha3] .
$$



